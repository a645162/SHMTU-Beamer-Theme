# VSCode 中使用 LaTeX

## 安装插件

LaTeX Workshop

```
 "name": "latexmk",
            "command": "latexmk",
            // "args": [
            //     "-synctex=1",
            //     "-interaction=nonstopmode",
            //     "-file-line-error",
            //     "-pdf",
            //     "-outdir=%OUTDIR%",
            //     "%DOC%"
            // ],
            "args": [
                "-xelatex",
                "-synctex=1",
                "-interaction=nonstopmode",
                "-file-line-error",
                "%DOC%"
            ],
            "env": {}
```

# 参考
https://blog.csdn.net/Haulyn5/article/details/124128533
