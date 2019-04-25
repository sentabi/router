# Spesifikasi
```

Linux AONT 3.4.11-rt19 #1 SMP PREEMPT Wed Jul 4 16:27:19 CST 2018 mips GNU/Linux

BusyBox v1.16.0 () multi-call binary.

# cpuinfo
system type             : 968380GERG
processor               : 0
cpu model               : Broadcom BMIPS4350 V8.0
BogoMIPS                : 598.01
wait instruction        : yes
microsecond timers      : yes
tlb_entries             : 32
extra interrupt vector  : no
hardware watchpoint     : no
ASEs implemented        :
shadow register sets    : 1
kscratch registers      : 0
core                    : 0
VCED exceptions         : not available
VCEI exceptions         : not available

processor               : 1
cpu model               : Broadcom BMIPS4350 V8.0
BogoMIPS                : 606.20
wait instruction        : yes
microsecond timers      : yes
tlb_entries             : 32
extra interrupt vector  : no
hardware watchpoint     : no
ASEs implemented        :
shadow register sets    : 1
kscratch registers      : 0
core                    : 0
VCED exceptions         : not available
VCEI exceptions         : not available

# memory
              total         used         free       shared      buffers
  Mem:        99732        95504         4228            0         4084
 Swap:            0            0            0
Total:        99732        95504         4228

# ps
  PID USER       VSZ STAT COMMAND
    1 root      3148 S    init
    2 root         0 SW   [kthreadd]
    3 root         0 SW   [ksoftirqd/0]
    4 root         0 SW   [kworker/0:0]
    5 root         0 SW   [kworker/u:0]
    6 root         0 SW   [migration/0]
    7 root         0 SW   [migration/1]
    8 root         0 SW   [kworker/1:0]
    9 root         0 SW   [ksoftirqd/1]
   11 root         0 SW<  [khelper]
   12 root         0 SW   [kworker/u:1]
   87 root         0 SW   [sync_supers]
   89 root         0 SW   [bdi-default]
   91 root         0 SW<  [kblockd]
   99 root         0 SW   [khubd]
  118 root         0 SW   [skbFreeTask]
  119 root         0 SW   [bcmFapDrv]
  137 root         0 SWN  [kswapd0]
  138 root         0 SW   [fsnotify_mark]
  140 root         0 SW<  [crypto]
  209 root         0 SW   [mtdblock0]
  214 root         0 SW   [mtdblock1]
  219 root         0 SW   [mtdblock2]
  224 root         0 SW   [mtdblock3]
  229 root         0 SW   [mtdblock4]
  234 root         0 SW   [mtdblock5]
  239 root         0 SW   [mtdblock6]
  244 root         0 SW   [mtdblock7]
  252 root         0 SW   [ubi_bgt0d]
  259 root         0 SW   [mtdblock8]
  275 root         0 DW   [DEBUGCORE]
  278 root         0 SW<  [linkwatch]
  288 root         0 SW<  [deferwq]
  712 root         0 SW   [ubi_bgt1d]
  719 root         0 SW   [mtdblock9]
  730 root         0 SW   [mtdblock10]
  738 root         0 SW   [ubifs_bgt1_1]
  742 root         0 SW   [ubi_bgt5d]
  749 root         0 SW   [mtdblock11]
  757 root         0 SW   [ubifs_bgt5_0]
  843 root         0 SW   [flush-ubifs_1_1]
  844 root         0 SW   [flush-ubifs_5_0]
 1135 root         0 SW   [ubi_bgt2d]
 1142 root         0 SW   [mtdblock12]
 1168 root         0 DW   [led_task]
 1196 root      1784 S    /webs/thttpd -dd /webs/
 1203 root         0 SW   [btn_poll_task]
 1204 root         0 SW   [btn_event_task]
 1208 root      3156 S    sh /bcm/script/data_guardian.sh
 1216 root      3136 S    /sbin/klogd
 1238 root         0 SW   [bcmsw_rx]
 1254 root         0 SW   [bcmsw]
 1265 root         0 DW   [Pon]
 1310 root         0 DW   [KLPD_K]
 1313 root         0 SW   [bcmFlwStatsTask]
 1324 root         0 SW   [wfd2-thrd]
 1329 root         0 SW   [wl0-kthrd]
 1332 root         0 SW   [wfd0-thrd]
 1348 root         0 SW   [kworker/1:2]
 1598 root      1432 S    /sbin/msgmgr
 1609 root      5220 S    /sbin/evtmgr
 1617 root      2552 S    /sbin/ramond
 1621 root      2024 S    /sbin/sched
 1629 root      5124 S    /sbin/wifihostd
 1634 root      5124 S    /sbin/wifihostd
 1635 root      5124 S    /sbin/wifihostd
 1766 root     23580 S    ./voip
 1767 root      1788 S    /sbin/diagnosis
 1768 root      1516 S    /sbin/deamon /bcm/bin/deamon.cfg
 1773 root      1416 S    rfvid
 1789 root      1416 S    rfvid
 1790 root      1416 S    rfvid
 1795 root      3144 S    /sbin/getty -L -f /etc/issue 115200 ttyS0 vt100
 1805 root     19004 S    cfgmgr
 1810 root     23580 S    ./voip
 1811 root     23580 S    ./voip
 1812 root     23580 S    ./voip
 1813 root     23580 S    ./voip
 1814 root     23580 S    ./voip
 1815 root     19004 S    cfgmgr
 1843 root     19004 S    cfgmgr
 1878 root     23580 S    ./voip
 1884 root     23580 S    ./voip
 1885 root     23580 S    ./voip
 1886 root     23580 S    ./voip
 1887 root     23580 S    ./voip
 1891 root     23580 S    ./voip
 1892 root     23580 S    ./voip
 1894 root     23580 S    ./voip
 1900 root     23580 S    ./voip
 1902 root     23580 S    ./voip
 1903 root     23580 S    ./voip
 1904 root     23580 S    ./voip
 1905 root     23580 S    ./voip
 1906 root     23580 S    ./voip
 1907 root     23580 S    ./voip
 1908 root     23580 S    ./voip
 1909 root     23580 S    ./voip
 1910 root     23580 S    ./voip
 1912 root     23580 S    ./voip
 2047 root      3384 S    /sbin/uplinkmgr
 2049 root      2856 S    /sbin/ups
 2051 root      3412 S    /sbin/portmgr
 2054 root      2856 S    /sbin/ups
 2055 root      2856 S    /sbin/ups
 2056 root      8152 S    /sbin/parser
 2058 root      3384 S    /sbin/uplinkmgr
 2060 root      3384 S    /sbin/uplinkmgr
 2061 root      3384 S    /sbin/uplinkmgr
 2067 root      8152 S    /sbin/parser
 2068 root      8152 S    /sbin/parser
 2069 root      8152 S    /sbin/parser
 2071 root      8152 S    /sbin/parser
 2087 root     12344 S    /sbin/omciMgr
 2094 root      2220 S    lanhostd -m 0
 2103 root      5736 S    /sbin/cfmmgr
 2105 root      5736 S    /sbin/cfmmgr
 2106 root      5736 S    /sbin/cfmmgr
 2107 root      5736 S N  /sbin/cfmmgr
 2108 root      5736 S N  /sbin/cfmmgr
 2122 root     12344 S    /sbin/omciMgr
 2123 root     12344 S    /sbin/omciMgr
 2124 root     12344 S    /sbin/omciMgr
 2125 root     12344 S    /sbin/omciMgr
 2126 root     12344 S    /sbin/omciMgr
 2127 root     12344 S    /sbin/omciMgr
 2128 root     12344 S    /sbin/omciMgr
 2129 root     12344 S    /sbin/omciMgr
 2202 root      8152 S    /sbin/parser
 2385 root      1652 S    udhcpd /etc/udhcpd.conf
 2404 root      1492 S    /sbin/dnsproxy -D Home -v 0 -f 0x7 -g -p 0
 2905 root      2196 S    /usr/sbin/dropbear -r /configs/dropbear/dropbear_dss
 2957 root      1576 S    dhcp6s -f -c /etc/dhcp6s.conf br0
 2962 root      1100 S    /usr/local/sbin/radvd -C /etc/radvd.conf -m stderr
 2971 root      3304 S    /sbin/wand
 3016 root         0 SW   [voice-aoRT]
 3017 root         0 SW   [voice-HTSK]
 3018 root         0 SW   [voice-SLIC]
 3019 root         0 SW   [voice-HRTBEAT]
 3020 root         0 SW   [voice-VRGDISP]
 3021 root         0 SW   [voice-HCAS]
 3022 root         0 SW   [voice-TPD]
 3023 root         0 SW   [voice-ISTW]
 3026 root     23580 S    ./voip
 3237 root      3140 S    /sbin/syslogd -l 4 -s 1024 -b 2 -f /tmp/syslog.conf
 3238 root      3148 S    crond -b
 3291 root     19004 S    cfgmgr
 3475 root      2128 S    pppd pon_881_0_1 file /etc/ppp/options_ppp111 unit 1
 3504 root      1604 S    udhcpc -i pon_1081_5_1 -o 0
 3533 root      1604 S    udhcpc -i pon_981_0_1 -o 0
 3538 root      3864 S    stunnel /usr/configs/stunnel.conf
 3637 root      1772 S    utelnetd -p 23 -t 300
 4102 root      6704 S    /sbin/tr -d /configs/tr069_conf/
 4149 root      6704 S    /sbin/tr -d /configs/tr069_conf/
 4150 root      6704 S    /sbin/tr -d /configs/tr069_conf/
 4174 root     23580 S    ./voip
 4175 root     23580 S    ./voip
 4176 root     23580 S    ./voip
 4269 root     19004 S    cfgmgr
 4354 root      5336 S    /usr/sbin/tunnelmgr
 4486 root      1436 S    /bin/lld2d br0
 4491 root      1660 S    /bin/nas
 4517 root      6704 S    /sbin/tr -d /configs/tr069_conf/
 4520 root      2040 S    dhcpsnoop
 8582 root         0 SW   [kworker/0:2]
11635 root      3204 S    -sh
14094 root      3136 S    sleep 120
14287 root      3140 R    ps

# shell
/bin/sh

# open port
tcp        0      0 10.249.254.131:5060     0.0.0.0:*               LISTEN      1766/voip
tcp        0      0 127.0.0.1:6666          0.0.0.0:*               LISTEN      1766/voip
tcp        0      0 127.0.0.1:1234          0.0.0.0:*               LISTEN      4102/tr
tcp        0      0 0.0.0.0:22              0.0.0.0:*               LISTEN      2905/dropbear
tcp        0      0 0.0.0.0:23              0.0.0.0:*               LISTEN      3637/utelnetd
tcp        0      0 0.0.0.0:7547            0.0.0.0:*               LISTEN      4102/tr
tcp        0      0 :::80                   :::*                    LISTEN      1196/thttpd
tcp        0      0 :::22                   :::*                    LISTEN      2905/dropbear
tcp        0      0 :::443                  :::*                    LISTEN      3538/stunnel
udp        0      0 0.0.0.0:67              0.0.0.0:*                           2385/udhcpd
udp        0      0 127.0.0.1:45678         0.0.0.0:*                           1629/wifihostd
udp        0      0 127.0.0.1:45679         0.0.0.0:*                           1629/wifihostd
udp        0      0 192.168.1.254:57460     0.0.0.0:*                           2094/lanhostd
udp        0      0 127.0.0.1:38032         0.0.0.0:*                           4491/nas
udp        0      0 10.249.254.131:5060     0.0.0.0:*                           1766/voip
udp        0      0 :::547                  :::*                                2957/dhcp6s
udp        0      0 :::53                   :::*                                2404/dnsproxy
udp        0      0 :::57276                :::*                                2404/dnsproxy
udp        0      0 fe80::1:34000           :::*                                2957/dhcp6s

```

# /etc/passwd
```
root:x:0:0:root:/root:/bin/false
ONTUSER:x:0:0:Linux User,,,:/home/ONTUSER:/bin/sh
AdminGPON:x:0:0:Linux User,,,:/configs/home/AdminGPON:/bin/sh

# stunnel.conf

debug = 0
[https]
accept  = :::443
connect = 80

cert = /configs/cacert.pem
##only support high strength ciphers
ciphers= AES256
TIMEOUTclose = 0

```

## IPTABLES RULES
```
Chain INPUT (policy DROP)
target     prot opt source               destination         
TCPMSS     tcp  --  0.0.0.0/0            0.0.0.0/0            tcp flags:0x06/0x02 TCPMSS set 1412
TCPMSS     tcp  --  0.0.0.0/0            0.0.0.0/0            tcp flags:0x06/0x02 TCPMSS set 1460
ACCEPT     all  --  0.0.0.0/0            0.0.0.0/0           
INPUT_DOS_PROT  all  --  0.0.0.0/0            0.0.0.0/0           
INPUT_LAN2WANITFIP_BLOCK  all  --  0.0.0.0/0            0.0.0.0/0           
INPUT_PORTSCAN_BLACK  all  --  0.0.0.0/0            0.0.0.0/0           
INPUT_RTP_BLOCK  all  --  0.0.0.0/0            0.0.0.0/0           
INPUT_FW_PREFIX  all  --  0.0.0.0/0            0.0.0.0/0           
INPUT_FW_BLACK  all  --  0.0.0.0/0            0.0.0.0/0           
INPUT_FW_WHITE  all  --  0.0.0.0/0            0.0.0.0/0           

Chain FORWARD (policy ACCEPT)
target     prot opt source               destination         
REJECT     udp  --  0.0.0.0/0            0.0.0.0/0            udp dpt:68 reject-with icmp-port-unreachable
TCPMSS     tcp  --  0.0.0.0/0            0.0.0.0/0            tcp flags:0x06/0x02 TCPMSS set 1412
FORWARD_FW_PREFIX  all  --  0.0.0.0/0            0.0.0.0/0           
FORWARD_FW_BLACK  all  --  0.0.0.0/0            0.0.0.0/0           
FORWARD_FW_WHITE  all  --  0.0.0.0/0            0.0.0.0/0           

Chain OUTPUT (policy ACCEPT)
target     prot opt source               destination         
TCPMSS     tcp  --  0.0.0.0/0            0.0.0.0/0            tcp flags:0x06/0x02 TCPMSS set 1412
TCPMSS     tcp  --  0.0.0.0/0            0.0.0.0/0            tcp flags:0x06/0x02 TCPMSS set 1460

Chain ACK_LOG_AND_DROP (7 references)
target     prot opt source               destination         
LOG        all  --  0.0.0.0/0            0.0.0.0/0            limit: avg 3/min burst 3 LOG flags 7 level 7 prefix "ACK_DROP "
DROP       all  --  0.0.0.0/0            0.0.0.0/0           

Chain ACK_LOG_AND_REJECT (7 references)
target     prot opt source               destination         
LOG        all  --  0.0.0.0/0            0.0.0.0/0            limit: avg 3/min burst 3 LOG flags 7 level 7 prefix "ACK_REJTCP "
REJECT     tcp  --  0.0.0.0/0            0.0.0.0/0            reject-with tcp-reset

Chain DOS_LOG_AND_DROP (16 references)
target     prot opt source               destination         
LOG        all  --  0.0.0.0/0            0.0.0.0/0            limit: avg 6/min burst 12 LOG flags 7 level 7 prefix "DOS_DROP "
DROP       all  --  0.0.0.0/0            0.0.0.0/0           

Chain DOS_PROT_ICMP (1 references)
target     prot opt source               destination         
RETURN     icmp --  0.0.0.0/0            0.0.0.0/0            limit: avg 1250/sec burst 1250
DOS_LOG_AND_DROP  icmp --  0.0.0.0/0            0.0.0.0/0           

Chain DOS_PROT_TCP (1 references)
target     prot opt source               destination         
RETURN     tcp  --  0.0.0.0/0            0.0.0.0/0            ctstate NEW limit: avg 1666/sec burst 2500
DOS_LOG_AND_DROP  tcp  --  0.0.0.0/0            0.0.0.0/0            ctstate NEW
RETURN     tcp  --  0.0.0.0/0            0.0.0.0/0            ctstate INVALID limit: avg 500/sec burst 1500
DOS_LOG_AND_DROP  tcp  --  0.0.0.0/0            0.0.0.0/0            ctstate INVALID

Chain DOS_PROT_UDP (1 references)
target     prot opt source               destination         
RETURN     udp  --  0.0.0.0/0            0.0.0.0/0            limit: avg 1000/sec burst 1500
DOS_LOG_AND_DROP  udp  --  0.0.0.0/0            0.0.0.0/0           

Chain FORWARD_ACCESSPOLICY (0 references)
target     prot opt source               destination         

Chain FORWARD_DMZ (1 references)
target     prot opt source               destination         

Chain FORWARD_DROP_ACK (1 references)
target     prot opt source               destination         
ACK_LOG_AND_DROP  all  --  0.0.0.0/0            0.0.0.0/0            ctstate INVALID
ACK_LOG_AND_DROP  all  --  0.0.0.0/0            0.0.0.0/0            ctstate INVALID
ACK_LOG_AND_DROP  all  --  0.0.0.0/0            0.0.0.0/0            ctstate INVALID
ACK_LOG_AND_DROP  all  --  0.0.0.0/0            0.0.0.0/0            ctstate INVALID
ACK_LOG_AND_REJECT  tcp  --  0.0.0.0/0            0.0.0.0/0            tcp flags:0x17/0x10 ctstate NEW
ACK_LOG_AND_REJECT  tcp  --  0.0.0.0/0            0.0.0.0/0            tcp flags:0x17/0x10 ctstate NEW
ACK_LOG_AND_REJECT  tcp  --  0.0.0.0/0            0.0.0.0/0            tcp flags:0x17/0x10 ctstate NEW
ACK_LOG_AND_REJECT  tcp  --  0.0.0.0/0            0.0.0.0/0            tcp flags:0x17/0x10 ctstate NEW

Chain FORWARD_FW_BLACK (1 references)
target     prot opt source               destination         
IPFLTOUTFWD  all  --  0.0.0.0/0            0.0.0.0/0           
WANIPDROP  all  --  0.0.0.0/0            0.0.0.0/0           

Chain FORWARD_FW_PREFIX (1 references)
target     prot opt source               destination         
ACCEPT     all  --  0.0.0.0/0            0.0.0.0/0           
FORWARD_DROP_ACK  all  --  0.0.0.0/0            0.0.0.0/0           

Chain FORWARD_FW_WHITE (1 references)
target     prot opt source               destination         
FORWARD_PORTFWD  all  --  0.0.0.0/0            0.0.0.0/0           
FORWARD_DMZ  all  --  0.0.0.0/0            0.0.0.0/0           

Chain FORWARD_PORTFWD (1 references)
target     prot opt source               destination         
FORWARD_PORTFWD_EHEP  all  --  0.0.0.0/0            0.0.0.0/0           
FORWARD_PORTFWD_EHWP  all  --  0.0.0.0/0            0.0.0.0/0           
FORWARD_PORTFWD_WHEP  all  --  0.0.0.0/0            0.0.0.0/0           
FORWARD_PORTFWD_WHWP  all  --  0.0.0.0/0            0.0.0.0/0           

Chain FORWARD_PORTFWD_EHEP (1 references)
target     prot opt source               destination         

Chain FORWARD_PORTFWD_EHWP (1 references)
target     prot opt source               destination         

Chain FORWARD_PORTFWD_WHEP (1 references)
target     prot opt source               destination         

Chain FORWARD_PORTFWD_WHWP (1 references)
target     prot opt source               destination         

Chain INPUT_DOS_PROT (1 references)
target     prot opt source               destination         
LOG        tcp  --  0.0.0.0/0            0.0.0.0/0            tcp dpt:21 limit: avg 3/min burst 10 LOG flags 0 level 1 prefix "wan-ftp-access-log"
SUB_DOS_PROT  all  --  0.0.0.0/0            0.0.0.0/0           

Chain INPUT_DROP_ACK (1 references)
target     prot opt source               destination         
ACK_LOG_AND_DROP  all  --  0.0.0.0/0            0.0.0.0/0            ctstate INVALID
ACK_LOG_AND_DROP  all  --  0.0.0.0/0            0.0.0.0/0            ctstate INVALID
ACK_LOG_AND_DROP  all  --  0.0.0.0/0            0.0.0.0/0            ctstate INVALID
ACK_LOG_AND_REJECT  tcp  --  0.0.0.0/0            0.0.0.0/0            tcp flags:0x17/0x10 ctstate NEW
ACK_LOG_AND_REJECT  tcp  --  0.0.0.0/0            0.0.0.0/0            tcp flags:0x17/0x10 ctstate NEW
ACK_LOG_AND_REJECT  tcp  --  0.0.0.0/0            0.0.0.0/0            tcp flags:0x17/0x10 ctstate NEW

Chain INPUT_FW_BLACK (1 references)
target     prot opt source               destination         
INPUT_WAN_TR069_UPGRADE  all  --  0.0.0.0/0            0.0.0.0/0           
INPUT_LAN_ACCESS  all  --  0.0.0.0/0            0.0.0.0/0           
IPFLTOUTFWD  all  --  0.0.0.0/0            0.0.0.0/0           
INPUT_WAN_REMOTE_ACCESS  all  --  0.0.0.0/0            0.0.0.0/0           
INPUT_FW_LEVEL  all  --  0.0.0.0/0            0.0.0.0/0           
WANIPDROP  all  --  0.0.0.0/0            0.0.0.0/0           

Chain INPUT_FW_LEVEL (1 references)
target     prot opt source               destination         
ACCEPT     47   --  0.0.0.0/0            0.0.0.0/0           
ACCEPT     all  --  0.0.0.0/0            0.0.0.0/0           
ACCEPT     udp  --  0.0.0.0/0            0.0.0.0/0            udp spt:123
ACCEPT     udp  --  0.0.0.0/0            0.0.0.0/0           
ACCEPT     udp  --  0.0.0.0/0            0.0.0.0/0            udp dpt:49407
ACCEPT     tcp  --  0.0.0.0/0            0.0.0.0/0            tcp dpt:49407
REJECT     tcp  --  0.0.0.0/0            0.0.0.0/0            tcp dpt:5060 reject-with tcp-reset
ACCEPT     udp  --  0.0.0.0/0            0.0.0.0/0            udp dpts:22456:22584
ACCEPT     udp  --  0.0.0.0/0            0.0.0.0/0            udp dpt:5060
INPUT_FW_VOIP  all  --  0.0.0.0/0            0.0.0.0/0           
ACCEPT     tcp  --  0.0.0.0/0            0.0.0.0/0            tcp spt:7547
ACCEPT     tcp  --  0.0.0.0/0            0.0.0.0/0            tcp dpt:7547
ACCEPT     udp  --  0.0.0.0/0            0.0.0.0/0            udp spt:1813
ACCEPT     udp  --  0.0.0.0/0            0.0.0.0/0            udp spt:1812
ACCEPT     udp  --  0.0.0.0/0            0.0.0.0/0            udp dpt:2944
ACCEPT     tcp  --  0.0.0.0/0            0.0.0.0/0            tcp dpt:2944
ACCEPT     udp  --  0.0.0.0/0            0.0.0.0/0            udp dpt:69
ACCEPT     udp  --  0.0.0.0/0            0.0.0.0/0            udp dpt:68
ACCEPT     udp  --  0.0.0.0/0            0.0.0.0/0            udp spt:53
REJECT     udp  --  0.0.0.0/0            0.0.0.0/0            udp dpt:53 reject-with icmp-port-unreachable
REJECT     tcp  --  0.0.0.0/0            0.0.0.0/0            tcp dpt:5916 reject-with tcp-reset
REJECT     udp  --  0.0.0.0/0            0.0.0.0/0            udp dpt:80 reject-with icmp-port-unreachable
REJECT     udp  --  0.0.0.0/0            0.0.0.0/0            udp dpt:22 reject-with icmp-port-unreachable
REJECT     tcp  --  0.0.0.0/0            0.0.0.0/0            tcp dpt:21 reject-with tcp-reset
ACCEPT     tcp  --  0.0.0.0/0            0.0.0.0/0            ctstate RELATED,ESTABLISHED
ACCEPT     tcp  --  0.0.0.0/0            0.0.0.0/0            tcp spt:21
ACCEPT     2    --  0.0.0.0/0            224.0.0.0/4         
ACCEPT     icmp --  0.0.0.0/0            0.0.0.0/0            icmptype 8 limit: avg 10/sec burst 20
DROP       icmp --  0.0.0.0/0            0.0.0.0/0            icmptype 8
ACCEPT     icmp --  0.0.0.0/0            0.0.0.0/0            icmptype 0
ACCEPT     icmp --  0.0.0.0/0            0.0.0.0/0            icmptype 3
ACCEPT     icmp --  0.0.0.0/0            0.0.0.0/0            icmptype 11
ACCEPT     icmp --  0.0.0.0/0            0.0.0.0/0            icmptype 17
ACCEPT     icmp --  0.0.0.0/0            0.0.0.0/0            icmptype 18
ACCEPT     all  --  0.0.0.0/0            0.0.0.0/0           
DROP       all  --  0.0.0.0/0            0.0.0.0/0           

Chain INPUT_FW_PREFIX (1 references)
target     prot opt source               destination         
ACCEPT     all  --  0.0.0.0/0            0.0.0.0/0           
INPUT_DROP_ACK  all  --  0.0.0.0/0            0.0.0.0/0           

Chain INPUT_FW_VOIP (1 references)
target     prot opt source               destination         
ACCEPT     udp  --  0.0.0.0/0            0.0.0.0/0            udp dpt:5060
ACCEPT     udp  --  0.0.0.0/0            0.0.0.0/0            udp dpts:22456:22584

Chain INPUT_FW_WHITE (1 references)
target     prot opt source               destination         

Chain INPUT_LAN2WANITFIP_BLOCK (1 references)
target     prot opt source               destination         
DROP       all  --  0.0.0.0/0            10.249.254.131      

Chain INPUT_LAN_ACCESS (1 references)
target     prot opt source               destination         
ACCEPT     icmp --  0.0.0.0/0            0.0.0.0/0            icmptype 8 limit: avg 10/sec burst 20
DROP       icmp --  0.0.0.0/0            0.0.0.0/0            icmptype 8
ACCEPT     tcp  --  0.0.0.0/0            0.0.0.0/0            tcp dpt:80
ACCEPT     tcp  --  0.0.0.0/0            0.0.0.0/0            tcp dpt:23
REJECT     tcp  --  0.0.0.0/0            0.0.0.0/0            tcp dpt:22 reject-with tcp-reset
REJECT     tcp  --  0.0.0.0/0            0.0.0.0/0            tcp dpt:7547 reject-with tcp-reset
ACCEPT     tcp  --  0.0.0.0/0            0.0.0.0/0            tcp dpt:443

Chain INPUT_PORTSCAN_BLACK (1 references)
target     prot opt source               destination         

Chain INPUT_RTP_BLOCK (1 references)
target     prot opt source               destination         

Chain INPUT_WAN_ACCESS_TRUSTED (0 references)
target     prot opt source               destination         
DROP       all  --  0.0.0.0/0            0.0.0.0/0           

Chain INPUT_WAN_REMOTE_ACCESS (1 references)
target     prot opt source               destination         
ACCEPT     tcp  --  0.0.0.0/0            0.0.0.0/0            tcp spt:7547
ACCEPT     tcp  --  0.0.0.0/0            0.0.0.0/0            tcp dpt:7547
ACCEPT     tcp  --  0.0.0.0/0            0.0.0.0/0            tcp dpt:443
ACCEPT     icmp --  0.0.0.0/0            0.0.0.0/0            icmptype 8 limit: avg 10/sec burst 20
ACCEPT     tcp  --  0.0.0.0/0            0.0.0.0/0            tcp dpt:23
ACCEPT     tcp  --  0.0.0.0/0            0.0.0.0/0            tcp dpt:80
RETURN     all  --  0.0.0.0/0            0.0.0.0/0           
REJECT     tcp  --  0.0.0.0/0            0.0.0.0/0            tcp dpt:80 ctstate INVALID,NEW,RELATED,ESTABLISHED reject-with icmp-port-unreachable
REJECT     tcp  --  0.0.0.0/0            0.0.0.0/0            tcp dpt:23 ctstate INVALID,NEW,RELATED,ESTABLISHED reject-with icmp-port-unreachable
DROP       icmp --  0.0.0.0/0            0.0.0.0/0            icmptype 8
REJECT     tcp  --  0.0.0.0/0            0.0.0.0/0            tcp dpt:22 reject-with tcp-reset
REJECT     tcp  --  0.0.0.0/0            0.0.0.0/0            tcp dpt:7547 reject-with tcp-reset
REJECT     tcp  --  0.0.0.0/0            0.0.0.0/0            tcp spt:7547 reject-with tcp-reset
REJECT     tcp  --  0.0.0.0/0            0.0.0.0/0            tcp dpt:443 ctstate INVALID,NEW,RELATED,ESTABLISHED reject-with icmp-port-unreachable

Chain INPUT_WAN_TR069_UPGRADE (1 references)
target     prot opt source               destination         

Chain IPFLTOUTFWD (2 references)
target     prot opt source               destination         

Chain SUB_DOS_PROT (1 references)
target     prot opt source               destination         
RETURN     all  --  0.0.0.0/0            0.0.0.0/0           
RETURN     all  --  0.0.0.0/0            0.0.0.0/0           
DOS_LOG_AND_DROP  udp  --  0.0.0.0/0            0.0.0.0/0            udp dpt:21
DOS_LOG_AND_DROP  udp  --  0.0.0.0/0            0.0.0.0/0            udp dpt:22
DOS_LOG_AND_DROP  udp  --  0.0.0.0/0            0.0.0.0/0            udp dpt:80
DOS_LOG_AND_DROP  udp  --  0.0.0.0/0            0.0.0.0/0            udp dpt:443
DOS_LOG_AND_DROP  udp  --  0.0.0.0/0            0.0.0.0/0            udp dpt:8080
DOS_LOG_AND_DROP  udp  --  0.0.0.0/0            0.0.0.0/0            udp dpt:8090
DOS_LOG_AND_DROP  tcp  --  0.0.0.0/0            0.0.0.0/0            tcp dpt:137 flags:0x20/0x20
DOS_LOG_AND_DROP  tcp  --  0.0.0.0/0            0.0.0.0/0            tcp dpt:138 flags:0x20/0x20
DOS_LOG_AND_DROP  tcp  --  0.0.0.0/0            0.0.0.0/0            tcp dpt:139 flags:0x20/0x20
DOS_LOG_AND_DROP  icmp --  0.0.0.0/0            0.0.0.0/0            icmptype 5
RETURN     udp  --  0.0.0.0/0            0.0.0.0/0            udp dpt:53 limit: avg 100/sec burst 150
RETURN     udp  --  0.0.0.0/0            0.0.0.0/0            udp spt:53 limit: avg 200/sec burst 300
RETURN     tcp  --  0.0.0.0/0            0.0.0.0/0            tcp flags:0x17/0x02 limit: avg 20/sec burst 30
DOS_LOG_AND_DROP  tcp  --  0.0.0.0/0            0.0.0.0/0            tcp flags:0x17/0x02
RETURN     icmp --  0.0.0.0/0            0.0.0.0/0            icmptype 8 limit: avg 20/sec burst 100
DOS_LOG_AND_DROP  icmp --  0.0.0.0/0            0.0.0.0/0            icmptype 8
DOS_PROT_UDP  udp  --  0.0.0.0/0            0.0.0.0/0           
DOS_PROT_TCP  tcp  --  0.0.0.0/0            0.0.0.0/0           
DOS_PROT_ICMP  icmp --  0.0.0.0/0            0.0.0.0/0           

Chain WANIPALLOW (0 references)
target     prot opt source               destination         

Chain WANIPDROP (2 references)
target     prot opt source               destination         

Chain urlfilter (0 references)
target     prot opt source               destination         
```
