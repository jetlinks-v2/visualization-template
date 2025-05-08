## 模版数据保存
在`init/info`文件夹下编写json文件，放置模板的实体配置信息，支持一个文件存放多个组件

其中`template`为模版实体，`pages`为画板页面实体
```json
[
  {
      "template": {}, 
      "pages": [
        {}
      ]
  }
]
```

## 初始化初始缩略图
在`init/thumbnail`文件夹下放置缩略图文件，将实体配置信息的`thumbnailUrl`字段更换为图片文件名称
