#Theme for [SLiM](http://slim.berlios.de/) with [NixOS](http://nixos.org/) thematics.
![preview](https://github.com/jagajaga/nixos-slim-theme/raw/master/preview.png)

## How to use

To use this slim theme in NixOS you set the `theme` option, like so:

```
  slim = {
    enable = true;
    theme = pkgs.fetchurl {
      url    = "https://github.com/mvaude/nixos-slim-theme/archive/3.0.tar.gz";
      sha256 = "0rsrwh4sigh4al6jfm8sg33n2y5wyryzdg3p0r9v3n6b8bqb3m0r";
    };
  };
```

Then you need to do `nixos-rebuild switch` and restart slim to apply the theme.
