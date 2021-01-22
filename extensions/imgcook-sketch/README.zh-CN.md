简体中文 | [English](https://github.com/imgcook/imgcook/blob/master/extensions/imgcook-sketch/README.zh-CN.md)

# imgcook for Sketch

您可以使用此插件导出草图文件的元数据，然后将其用于 Web 绝对布局。
它可以帮助您快速用代码描述设计草案。

## 安装

* [下载](https://github.com/imgcook/imgcook/releases)最新版本的插件
* 解压安装包
* 双击 imgcook.sketchplugin 文件安装

## 使用说明

选择一个画板或组，然后单击导出数据，您将在剪贴板上获得一个 json 数据。 此 json 数据可用于生成 ui 代码，我们将在不久的将来提供生成ui代码的服务。

<img width="535" alt="screen shot 1" src="https://img.alicdn.com/tfs/TB1YEYRzFzqK1RjSZSgXXcpAVXa-745-256.png">

<br/>

# 导出数据示例

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
