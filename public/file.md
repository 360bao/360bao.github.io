文件服务器网络地址，文件上传/下载等基于以下地址拼接。

测试环境：`https://res.bit-yuan.com/19`  

生产环境：待定

# 文件上传

接口地址：`/upload`

请求地址，如：`https://res.bit-yuan.com/19/upload` 

请求方式：`POST`

请求参数：无

请求body：文件FormData形式

响应数据：

```json
[
  "201804/logo.jpg",
  "201804/icon.jpg"
]
```

# 文件下载/图片预览

接口地址：`/download/<server_return_path>`

请求地址，如：`https://res.bit-yuan.com/19/download/201804/640.jpg`

请求方式：`GET`

请求参数：无