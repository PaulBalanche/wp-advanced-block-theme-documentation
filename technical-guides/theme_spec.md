---
description: Json file that defines some theme behaviours.
---

# Theme specification file

{% hint style="info" %}
**Default location:** themes/active\_theme/theme\_spec.json
{% endhint %}



### add\_ons

Lorem ipsum dolor sit amet consectetur adipiscing elit tempor gravida, fringilla hac sapien integer vivamus fermentum posuere.

```json
"add_ons": [
    "coffeekraken"
 ]
```

###

### allowed\_block\_types&#x20;

Lorem ipsum dolor sit amet consectetur adipiscing elit tempor gravida, fringilla hac sapien integer vivamus fermentum posuere.

```json
"allowed_block_types": [
    "core/paragraph",
    "core/list",
    "core/heading",
    "core/button",
    "custom/wpe-container",
    "custom/wpe-grid",
    "custom/wpe-column",
    "custom/wpe-component",
    "custom/wpe-slider",
    "custom/wpe-slide"
 ]
```

###

### assets

Lorem ipsum dolor sit amet consectetur adipiscing elit tempor gravida, fringilla hac sapien integer vivamus fermentum posuere.

```json
"assets": {
    "dev": {
      "type": "module",
      "defer": true,
      "src": "/src/js/index.ts",
      "env": "development"
    },
    "module": {
      "type": "module",
      "defer": true,
      "src": "/dist/js/index.esm.js",
      "env": "production"
    },
    "nomodule": {
      "nomodule": true,
      "defer": true,
      "src": "/dist/js/index.amd.js",
      "env": "production"
    },
    "style": {
      "id": "global",
      "defer": true,
      "src": "/dist/css/index.css"
    }
}
```

###

### container

Lorem ipsum dolor sit amet consectetur adipiscing elit tempor gravida, fringilla hac sapien integer vivamus fermentum posuere.

```json
"container": {
    "is_main": false
 }
```

###

### custom\_blocks\_routing

Lorem ipsum dolor sit amet consectetur adipiscing elit tempor gravida, fringilla hac sapien integer vivamus fermentum posuere.

```json
 "custom_blocks_routing": {
    "bare-container": "layout/wpe-container",
    "bare-layout": "layout/wpe-grid",
    "bare-cell": "layout/wpe-column",
    "button": "core/button",
    "image": "core/image",
    "text-image": "core/media-text",
    "components-slider": "layout/wpe-slider",
    "components-slide": "layout/wpe-slide"
 }
```

###

### i18n

Lorem ipsum dolor sit amet consectetur adipiscing elit tempor gravida, fringilla hac sapien integer vivamus fermentum posuere.

```json
"i18n": {
    "site-title": "Basic Wordpress boilerplate theme",
    "copyright": "© 2022 Basic Wordpress boilerplate theme"
 }
```

###

### media

Lorem ipsum dolor sit amet consectetur adipiscing elit tempor gravida, fringilla hac sapien integer vivamus fermentum posuere.

```json
"media": {
    "defaultMedia": "desktop",
    "queries": {
      "wide": {
        "minWidth": 2048,
        "maxWidth": null
      },
      "desktop": {
        "minWidth": 1280,
        "maxWidth": 2047
      },
      "tablet": {
        "minWidth": 640,
        "maxWidth": 1279
      },
      "mobile": {
        "minWidth": 0,
        "maxWidth": 639
      }
    }
}
```

###

### menus

Lorem ipsum dolor sit amet consectetur adipiscing elit tempor gravida, fringilla hac sapien integer vivamus fermentum posuere.

```json
"menus": {
    "primary": {
      "name": "Primary menu"
    },
    "footer": {
      "name": "Footer menu"
    }
}
```

###

### show\_admin\_bar

Lorem ipsum dolor sit amet consectetur adipiscing elit tempor gravida, fringilla hac sapien integer vivamus fermentum posuere.

```json
"show_admin_bar": false
```

###

### spacing

Lorem ipsum dolor sit amet consectetur adipiscing elit tempor gravida, fringilla hac sapien integer vivamus fermentum posuere.

Lorem ipsum dolor sit amet consectetur adipiscing elit tempor gravida, fringilla hac sapien integer vivamus fermentum posuere.

```json
"spacing": "coffeekraken"
```

###

### text\_domain

Lorem ipsum dolor sit amet consectetur adipiscing elit tempor gravida, fringilla hac sapien integer vivamus fermentum posuere.

```json
"text_domain": "wpe-basic-boilerplate-theme"
```

###

### Editor configuration

```json
 "editor": {
    "style": "dark",
    "backgroundColor": "#303335"
 }
```