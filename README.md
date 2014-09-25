HttpMailQueue
=============

requirements

python 2.6+
tornado


使用方法

1.启动
chmod +x ./mail_send_server && ./mail_send_server mailsend.conf

2.停止
./mail_send_server stop


3.添加新邮件到邮件队列

POST receiver(收件人邮箱)、title(邮件标题)、content(邮件内容) 参数到:
http://{yourip}:8888/mail

4.队列信息
http://{yourip}:8888/info


