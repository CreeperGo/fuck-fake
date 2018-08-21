# fuck-fake
closed-source patch... Linux only
LD_PRELOAD=patch.so路径(例如./patch.so 最好使用绝对路径) ./server

launch.sh<br>
  LD_PRELOAD=/home/server/patch.so /home/server/gctf/server

启动时sh launch.sh

clean.py 自动清理ip验证数据 建议cron 每天半夜执行
