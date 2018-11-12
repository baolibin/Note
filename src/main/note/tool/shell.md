
##### shell
    

##### grep -v
    ps -ef | grep "syslog"
        syslog     701     1  0 11:13 ?        00:00:00 /usr/sbin/rsyslogd -n
        baolibin  9502  9187  0 14:25 pts/20   00:00:00 grep --color=auto syslog

    ps -ef | grep "syslog"|grep -v "grep"
        syslog     701     1  0 11:13 ?        00:00:00 /usr/sbin/rsyslogd -n

    ps -ef | grep "syslog"|grep -v "grep"|awk '{print $2}'
        701
