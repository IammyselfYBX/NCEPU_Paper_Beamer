# 2021届本科生毕业论文
本项目是存放2021届本科生毕业论文的,
## 目录结构
```
.
├── font        # 存放 用到的字体
├── Paper       # 存放 论文
├── PPT         # 存放 报告PPT 
└── README.md   # 说明文档
```

## 安装字体
这里仅仅是使用 ```Linux``` 用户可能才需要,Windows与Mac用户不需要。
```bash
cp ./font/* /usr/share/fonts/my-fonts/
mkfontscale
mkfontdir
fc-cache -fsv #刷新
```

## 编译运行
### 编译论文
```bash
cd Paper
latexmk -f
```

### 编译PPT
```bash
cd PPT
latexmk -f
```



