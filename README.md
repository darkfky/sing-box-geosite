# sing-box-geosite

在links.txt添加规则集，自动生成 sing-box Source Format。fork后自己添加想要转换的规则集。

仓库 Settings ----> Actions ----> General ----> Workflow permissions ----> Read and write permissions 勾选上

规则集源文件写法eg:

```json
      {
        "type": "remote",
        "tag": "adblock",
        "format": "binary",
        "path": "./ruleset/adblock.srs",
        "url": "https://github.com/darkfky/sing-box-geosite/raw/refs/heads/main/rule/adblock_clash.srs"
      },
```

# 致谢（排名不分先后）

[@izumiChan16](https://github.com/izumiChan16)

[@ifaintad](https://github.com/ifaintad)

[@NobyDa](https://github.com/NobyDa)

[@blackmatrix7](https://github.com/blackmatrix7)

[@DivineEngine](https://github.com/DivineEngine)
