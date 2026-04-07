# sing-box-rules

Derived from https://github.com/Toperlock/sing-box-geosite

在links.txt添加规则集，自动生成 sing-box Source Format。fork后自己添加想要转换的规则集。生成结果发布到 `release` 分支。

仓库 Settings ----> Actions ----> General ----> Workflow permissions ----> Read and write permissions 勾选上

规则集源文件写法eg:

```json
{
  "tag": "geosite-openai",
  "type": "remote",
  "format": "source",
  "url": "https://raw.githubusercontent.com/7ongOrz/sing-box-rules/release/OpenAI.json",
  "download_detour": "auto"
}
```

# 致谢（排名不分先后）

[@izumiChan16](https://github.com/izumiChan16)

[@ifaintad](https://github.com/ifaintad)

[@NobyDa](https://github.com/NobyDa)

[@blackmatrix7](https://github.com/blackmatrix7)

[@DivineEngine](https://github.com/DivineEngine)

[@Toperlock](https://github.com/Toperlock)
