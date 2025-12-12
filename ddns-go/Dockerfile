FROM jeessy/ddns-go:latest

# 切换工作目录，便于挂载配置
WORKDIR /config

# 复制启动脚本
COPY run.sh /run.sh
RUN chmod +x /run.sh

# 启动命令
CMD ["/run.sh"]