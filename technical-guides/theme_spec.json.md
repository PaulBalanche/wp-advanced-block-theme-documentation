# theme\_spec.json

```json
"add_ons": [
    "coffeekraken"
]
```



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



```json
"container": {
        "is_main": false
}
```



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



```json
"gridConfig": {
        "variations": [
            {
                "name": "column-2",
                "title": "2 column",
                "icon": "column1",
                "attributes": { "gridCountColumns": 2 },
                "innerBlocks": [
                    {
                        "name": "custom/wpe-column",
                        "attributes": {"layout":{"desktop":{"width":1}}}
                    },
                    {
                        "name": "custom/wpe-column",
                        "attributes": {"layout":{"mobile":{"columnStart":1,"width":1,"rowStart":2,"height":1},"tablet":{"columnStart":2,"width":1,"rowStart":1,"height":1},"desktop":{"columnStart":2,"width":1,"rowStart":1,"height":1}}}
                    }
                ]
            },
            {
                "name": "column-3",
                "title": "3 column",
                "icon": "columns3",
                "attributes": { "gridCountColumns": 3 },
                "innerBlocks": [
                    {
                        "name": "custom/wpe-column",
                        "attributes": {"layout":{"desktop":{"width":1,"columnStart":3},"tablet":{"columnStart":3}}}
                    },
                    {
                        "name": "custom/wpe-column",
                        "attributes": {"layout":{"mobile":{"columnStart":1,"width":1,"rowStart":2,"height":1},"tablet":{"columnStart":2,"width":1,"rowStart":1,"height":1},"desktop":{"columnStart":2,"width":1,"rowStart":1,"height":1}}}
                    },
                    {
                        "name": "custom/wpe-column",
                        "attributes": {"layout":{"mobile":{"columnStart":1,"width":1,"rowStart":3,"height":1},"tablet":{"columnStart":1,"width":1,"rowStart":1,"height":1},"desktop":{"columnStart":1,"width":1,"rowStart":1,"height":1}}}
                    }
                ]
            },
            {
                "name": "column-4",
                "title": "4 column",
                "icon": "columns4",
                "attributes": { "gridCountColumns": 4 },
                "innerBlocks": [
                    {
                        "name": "custom/wpe-column",
                        "attributes": {"layout":{"desktop":{"width":1,"columnStart":3},"tablet":{"columnStart":1,"rowStart":2}}}
                    },
                    {
                        "name": "custom/wpe-column",
                        "attributes": {"layout":{"mobile":{"columnStart":1,"width":1,"rowStart":2,"height":1},"tablet":{"columnStart":2,"width":1,"rowStart":1,"height":1},"desktop":{"columnStart":2,"width":1,"rowStart":1,"height":1},"wide":{"columnStart":1,"width":1,"rowStart":2,"height":1}}}
                    },
                    {
                        "name": "custom/wpe-column",
                        "attributes": {"layout":{"mobile":{"columnStart":1,"width":1,"rowStart":3,"height":1},"tablet":{"columnStart":1,"width":1,"rowStart":1,"height":1},"desktop":{"columnStart":1,"width":1,"rowStart":1,"height":1},"wide":{"columnStart":1,"width":1,"rowStart":3,"height":1}}}
                    },
                    {
                        "name": "custom/wpe-column",
                        "attributes": {"layout":{"mobile":{"columnStart":1,"width":1,"rowStart":4,"height":1},"tablet":{"columnStart":2,"width":1,"rowStart":2,"height":1},"desktop":{"columnStart":4,"width":1,"rowStart":1,"height":1},"wide":{"columnStart":1,"width":1,"rowStart":4,"height":1}}}
                    }
                ]
            }
        ]
}
```



```json
"i18n": {
        "site-title": "Basic Wordpress boilerplate theme",
        "copyright": "© 2022 Basic Wordpress boilerplate theme"
}
```

```json
"spacing": "coffeekraken"
```

