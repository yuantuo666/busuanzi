# 不蒜子

> 自建不蒜子API
> 
> 基于 Golang + Redis 的简易访问量统计系统

  - 统计站点的 UV, PV
  - 统计文章页的 UV, PV

# 安装

1. `git clone -b 126 --depth=1 https://github.com/soxft/busuanzi.git && cd busuanzi`
2. `go build -o busuanzi main.go`
3. 根据提示修改 config.yml
4. 编辑 dist/busuanzi.js 替换链接为自己的, 也可以编辑ts文件自行编译
5. 通过命令 `./busuanzi -c config.yaml` 启动程序
