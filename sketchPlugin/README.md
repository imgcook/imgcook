# imgcook_sketch_plugin

You can use this plugin to export the metadata of the sketch file and then use it for web layout (absolute).
It can help you quickly describe the design draft in code.

## Installation

* [Download](https://github.com/taobaofed/imgcook/releases) the latest release of the plugin
* Un-zip
* Double-click on imgcook_vip.sketchplugin

## Instructions

Choose an artboard or group then click export data and you will get a json data on your clipboard. This json data can be used to generate ui code, and we will provide the service that generates ui code in the near future.

<img width="535" alt="screen shot 1" src="https://img.alicdn.com/tfs/TB1YEYRzFzqK1RjSZSgXXcpAVXa-745-256.png">

# export data example

``` json
{
  "type": "Block",
  "id": "Block-1",
  "__VERSION__": "2.0",
  "props": {
    "style": {
      "width": 702,
      "height": 200
    },
    "attrs": {
      "x": 0,
      "y": 0
    }
  },
  "children": [{
    "__VERSION__": "2.0",
    "props": {
      "style": {
        "width": 702,
        "height": 200,
        "backgroundColor": "rgba(255,255,255,1)",
        "borderRadius": 12
      },
      "attrs": {
        "x": 0,
        "y": 0
      }
    },
    "children": [],
    "type": "Shape",
    "id": "Shape-0"
  }, {
    "__VERSION__": "2.0",
    "props": {
      "style": {
        "width": 174,
        "height": 200
      },
      "attrs": {
        "x": 13,
        "y": 0,
        "downgrade": true,
        "source": "https://via.placeholder.com/174x200?text=174x200"
      }
    },
    "children": [],
    "type": "Image",
    "id": "Image-1"
  }, {
    "__VERSION__": "2.0",
    "props": {
      "style": {
        "width": 99,
        "height": 24,
        "fontFamily": "PingFangSC",
        "fontSize": "30",
        "color": "#FF5000",
        "lineHeight": "24rem",
        "fontWeight": 500
      },
      "attrs": {
        "x": 314,
        "y": 158,
        "text": "666.00",
        "fixed": false,
        "lines": 1
      }
    },
    "type": "Text",
    "id": "Text-5"
  }, {
    "__VERSION__": "2.0",
    "props": {
      "style": {
        "width": 20,
        "height": 20,
        "fontFamily": "PingFangSC",
        "fontSize": "20",
        "color": "#FF5000",
        "lineHeight": "20rem",
        "fontWeight": 500
      },
      "attrs": {
        "x": 294,
        "y": 162,
        "text": "￥",
        "fixed": false,
        "lines": 1
      }
    },
    "type": "Text",
    "id": "Text-7"
  }, {
    "__VERSION__": "2.0",
    "props": {
      "style": {
        "width": 164,
        "height": 26,
        "backgroundColor": "rgba(255,255,255,0.1)",
        "borderWidth": "1",
        "borderStyle": "solid",
        "borderColor": "#FF5000",
        "borderRadius": 4
      },
      "attrs": {
        "x": 215,
        "y": 56
      }
    },
    "children": [],
    "type": "Shape",
    "id": "Shape-9"
  }],
  "artboardImg": "http://ai-sample.oss-cn-hangzhou.aliyuncs.com/test/FmR0vOY7e5w_N5BQAE05HK5ulVmJ.png"
}
```
