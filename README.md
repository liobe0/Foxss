# 🦊 Foxss

Foxss 是一个高效的大规模 XSS 扫描工具，旨在帮助安全研究人员和开发人员快速发现和修复跨站脚本漏洞 (XSS)。

曾经写过一个工具，开源了，但转手就被别人抄了，所以这个工具如果要开源的话，等核心技术被挖掘完了再开源

## ✨ 特性

- 🔍 高效的 XSS 漏洞扫描引擎
- 🌐 仅支持GET请求
- 📊 详细的报告和统计信息
- 🛠️ 易于使用的命令行界面

## 🚀 安装

你可以通过以下命令来安装 Foxss：

```bash
git clone https://github.com/liobe0/Foxss.git
cd foxss
Telek -h
```

# 运行
```
.\Telek.exe -u "http://ctf.aabyss.cn/xss-labs/level1.php?name=test"
[+]Loading completed!
[+]存在漏洞的参数:q
[+]未存在漏洞的参数:x
[+]未存在漏洞的参数:y
[+]未存在漏洞的参数:act
```
