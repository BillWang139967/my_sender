### senders
## 有独立的线程定时发送告警, 保证单位时间内不会有太多的告警骚扰到用户
## 被收敛的告警，在时间到了之后会自动合并，一次发送给用户
   (1)相同的警告会自动合并为一个，失败数会累加(当此项检测成功时会清零)
   (2)不同的警告会合并到一封邮件中
