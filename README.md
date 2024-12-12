```sh
west build -d build/left -p -b  nice_nano_v2 -- -DSHIELD=corne_left -DCONFIG_ZMK_RGB_UNDERGLOW=y -DCONFIG_WS2812_STRIP=y && west build -d build/right -p -b  nice_nano_v2 -- -DSHIELD=corne_right -DCONFIG_ZMK_RGB_UNDERGLOW=y -DCONFIG_WS2812_STRIP=y
```