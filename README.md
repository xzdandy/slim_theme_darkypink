To use this theme in NixOS set your SLiM configuration settings like so:

```
services.displayManager.slim = {
    enable = true;
    theme = pkgs.fetchurl {
      url = "https://github.com/xzdandy/slim_theme_darkypink/archive/master.tar.gz";
      sha256 = "c50f14cfed6a9fea090b613029ff43ac206e3107404071506260360596389eb7";
    };
  };
```
