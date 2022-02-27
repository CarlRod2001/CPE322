# Labs 1 and 2 - Command Line
I pledge my honor that I have abided by the Stevens Honor System.

### **hostname/env/ps/pwd**
![](https://github.com/CarlRod2001/CPE322/blob/main/Lab_1_2/Pics/Lab_1_2_pic1.JPG)
### **git clone/cd iot/ls/cd/df/mkdir demo/cd demo**
![](https://github.com/CarlRod2001/CPE322/blob/main/Lab_1_2/Pics/Lab_1_2_pic2.JPG)
![](https://github.com/CarlRod2001/CPE322/blob/main/Lab_1_2/Pics/nanofile.JPG)
### **nano file/catfile/cp file file1/mv file file2/rm file2**
![](https://github.com/CarlRod2001/CPE322/blob/main/Lab_1_2/Pics/Lab_1_2_pic3.JPG)
### **clear**
![](https://github.com/CarlRod2001/CPE322/blob/main/Lab_1_2/Pics/Lab_1_2_pic4.JPG)
### **man uname/uname -a/ifconfig**
![](https://github.com/CarlRod2001/CPE322/blob/main/Lab_1_2/Pics/Lab_1_2_pic5.JPG)
![](https://github.com/CarlRod2001/CPE322/blob/main/Lab_1_2/Pics/man_uname.JPG)
### **ping localhost/netstat**
![](https://github.com/CarlRod2001/CPE322/blob/main/Lab_1_2/Pics/Lab_1_2_pic6.JPG)
```
pi@CarlitosR:~/demo $ netstat
Active Internet connections (w/o servers)
Proto Recv-Q Send-Q Local Address           Foreign Address         State
tcp        0      0 localhost:59696         localhost:35419         ESTABLISHED
tcp        0    164 192.168.1.58:ssh        192.168.1.40:54461      ESTABLISHED
tcp        0      0 localhost:35419         localhost:59696         ESTABLISHED
Active UNIX domain sockets (w/o servers)
Proto RefCnt Flags       Type       State         I-Node   Path
unix  2      [ ]         DGRAM                    17911    /run/user/1000/systemd/notify
unix  2      [ ]         DGRAM                    20244    /tmp/dhcpcd-pi/libdhcpcd-wpa-929.1
unix  2      [ ]         DGRAM                    18433    /tmp/.vncserver-license/0.539
unix  3      [ ]         DGRAM                    8805     /run/systemd/notify
unix  2      [ ]         DGRAM                    8813     /run/systemd/journal/syslog
unix  7      [ ]         DGRAM                    8819     /run/systemd/journal/socket
unix  19     [ ]         DGRAM                    8839     /run/systemd/journal/dev-log
unix  4      [ ]         DGRAM                    17347    /var/run/wpa_supplicant/wlan0
unix  2      [ ]         DGRAM                    17369    /var/run/wpa_supplicant/p2p-dev-wlan0
unix  2      [ ]         DGRAM                    20243    /tmp/dhcpcd-pi/libdhcpcd-wpa-929.0
unix  3      [ ]         STREAM     CONNECTED     18749    /run/user/1000/bus
unix  3      [ ]         STREAM     CONNECTED     18748
unix  2      [ ]         DGRAM                    11447
unix  3      [ ]         DGRAM                    9819
unix  3      [ ]         STREAM     CONNECTED     18816
unix  3      [ ]         STREAM     CONNECTED     20649    /run/systemd/journal/stdout
unix  2      [ ]         DGRAM                    19796
unix  3      [ ]         STREAM     CONNECTED     16702    /var/run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     18814
unix  3      [ ]         STREAM     CONNECTED     18817    /run/user/1000/bus
unix  3      [ ]         STREAM     CONNECTED     14210    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     21579    /var/run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     18819
unix  3      [ ]         STREAM     CONNECTED     18907
unix  3      [ ]         STREAM     CONNECTED     19793
unix  3      [ ]         DGRAM                    9820
unix  3      [ ]         STREAM     CONNECTED     15899    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     18828
unix  3      [ ]         STREAM     CONNECTED     20696    /run/user/1000/bus
unix  2      [ ]         DGRAM                    15905
unix  3      [ ]         STREAM     CONNECTED     18084    /var/run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     18826
unix  3      [ ]         STREAM     CONNECTED     18754    /run/user/1000/bus
unix  3      [ ]         STREAM     CONNECTED     18865
unix  2      [ ]         DGRAM                    9816
unix  3      [ ]         STREAM     CONNECTED     20740    /run/user/1000/bus
unix  2      [ ]         DGRAM                    9683
unix  3      [ ]         STREAM     CONNECTED     15834
unix  3      [ ]         STREAM     CONNECTED     18868
unix  3      [ ]         STREAM     CONNECTED     9813
unix  3      [ ]         STREAM     CONNECTED     19838
unix  2      [ ]         DGRAM                    15509
unix  3      [ ]         STREAM     CONNECTED     18867
unix  3      [ ]         STREAM     CONNECTED     20742    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     11594    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     15898
unix  3      [ ]         STREAM     CONNECTED     20018    @/dbus-vfs-daemon/socket-eckbluiG
unix  2      [ ]         DGRAM                    18890
unix  3      [ ]         STREAM     CONNECTED     15518    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     20916    /var/run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     12263
unix  2      [ ]         STREAM     CONNECTED     21109
unix  3      [ ]         STREAM     CONNECTED     16794
unix  3      [ ]         STREAM     CONNECTED     16795    /run/systemd/journal/stdout
unix  3      [ ]         DGRAM                    8807
unix  3      [ ]         STREAM     CONNECTED     19178
unix  3      [ ]         STREAM     CONNECTED     19347    /var/run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     21100
unix  3      [ ]         STREAM     CONNECTED     19183
unix  3      [ ]         STREAM     CONNECTED     19184
unix  3      [ ]         STREAM     CONNECTED     20964    /var/run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     16698
unix  3      [ ]         STREAM     CONNECTED     16515
unix  3      [ ]         STREAM     CONNECTED     20237    /run/user/1000/bus
unix  2      [ ]         STREAM     CONNECTED     14220
unix  3      [ ]         STREAM     CONNECTED     16697
unix  3      [ ]         STREAM     CONNECTED     19179
unix  3      [ ]         STREAM     CONNECTED     21780    /run/user/1000/bus
unix  3      [ ]         STREAM     CONNECTED     16699    /var/run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     12065
unix  3      [ ]         DGRAM                    8806
unix  3      [ ]         STREAM     CONNECTED     21833    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     20015
unix  3      [ ]         STREAM     CONNECTED     16701    /var/run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     19107
unix  3      [ ]         STREAM     CONNECTED     13995
unix  3      [ ]         STREAM     CONNECTED     20915    /var/run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     15416    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     20132
unix  2      [ ]         DGRAM                    19117
unix  3      [ ]         STREAM     CONNECTED     19120
unix  3      [ ]         STREAM     CONNECTED     12194
unix  3      [ ]         STREAM     CONNECTED     19559    /var/run/dbus/system_bus_socket
unix  2      [ ]         DGRAM                    22290
unix  2      [ ]         DGRAM                    16383
unix  2      [ ]         STREAM     CONNECTED     14228
unix  3      [ ]         STREAM     CONNECTED     13981
unix  3      [ ]         STREAM     CONNECTED     16153
unix  3      [ ]         STREAM     CONNECTED     20163
unix  2      [ ]         DGRAM                    20529
unix  3      [ ]         STREAM     CONNECTED     20528
unix  2      [ ]         DGRAM                    13973
unix  3      [ ]         DGRAM                    17913
unix  3      [ ]         STREAM     CONNECTED     20919    /run/user/1000/pulse/native
unix  3      [ ]         STREAM     CONNECTED     22025
unix  3      [ ]         STREAM     CONNECTED     14181    /var/run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     16700    /var/run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     20638
unix  3      [ ]         STREAM     CONNECTED     19197    /var/run/dhcpcd.unpriv.sock
unix  3      [ ]         STREAM     CONNECTED     19177    /run/user/1000/menu-cached-:0
unix  3      [ ]         STREAM     CONNECTED     18768    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     18117    @/tmp/.X11-unix/X0
unix  3      [ ]         STREAM     CONNECTED     16282    /var/run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     16703    /var/run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     18505    /var/run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     15977
unix  3      [ ]         STREAM     CONNECTED     18822    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     14166    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     18175    @/tmp/.X11-unix/X0
unix  3      [ ]         STREAM     CONNECTED     13975
unix  3      [ ]         STREAM     CONNECTED     22608
unix  3      [ ]         STREAM     CONNECTED     18820    /run/user/1000/bus
unix  2      [ ]         DGRAM                    16002
unix  3      [ ]         STREAM     CONNECTED     13974
unix  3      [ ]         STREAM     CONNECTED     21099    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     19930
unix  2      [ ]         DGRAM                    20535
unix  2      [ ]         STREAM     CONNECTED     22276
unix  3      [ ]         STREAM     CONNECTED     16131
unix  3      [ ]         STREAM     CONNECTED     14117
unix  3      [ ]         STREAM     CONNECTED     22315
unix  3      [ ]         STREAM     CONNECTED     18827    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     20239
unix  3      [ ]         STREAM     CONNECTED     21566    /var/run/dbus/system_bus_socket
unix  2      [ ]         DGRAM                    14097
unix  2      [ ]         DGRAM                    15915
unix  2      [ ]         DGRAM                    13982
unix  3      [ ]         STREAM     CONNECTED     20481
unix  3      [ ]         STREAM     CONNECTED     20454
unix  3      [ ]         STREAM     CONNECTED     16243
unix  3      [ ]         STREAM     CONNECTED     21093    /var/run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     19996
unix  3      [ ]         STREAM     CONNECTED     20739
unix  2      [ ]         DGRAM                    22225
unix  3      [ ]         STREAM     CONNECTED     20628
unix  3      [ ]         STREAM     CONNECTED     19973
unix  3      [ ]         STREAM     CONNECTED     13892
unix  3      [ ]         STREAM     CONNECTED     20543    /var/run/dbus/system_bus_socket
unix  2      [ ]         DGRAM                    14078
unix  3      [ ]         STREAM     CONNECTED     15504    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     19196    /var/run/dhcpcd.unpriv.sock
unix  3      [ ]         STREAM     CONNECTED     17915
unix  3      [ ]         STREAM     CONNECTED     18113    @/tmp/.X11-unix/X0
unix  3      [ ]         STREAM     CONNECTED     20240
unix  3      [ ]         STREAM     CONNECTED     20650
unix  3      [ ]         STREAM     CONNECTED     20693
unix  3      [ ]         STREAM     CONNECTED     22314
unix  3      [ ]         STREAM     CONNECTED     16704    /var/run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     20627
unix  3      [ ]         STREAM     CONNECTED     14231
unix  3      [ ]         STREAM     CONNECTED     18737    /run/user/1000/bus
unix  3      [ ]         STREAM     CONNECTED     14862
unix  2      [ ]         DGRAM                    12052
unix  3      [ ]         STREAM     CONNECTED     19643    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     14039    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     21590
unix  3      [ ]         STREAM     CONNECTED     18649
unix  3      [ ]         STREAM     CONNECTED     21737
unix  3      [ ]         STREAM     CONNECTED     17478
unix  2      [ ]         DGRAM                    15022
unix  3      [ ]         STREAM     CONNECTED     16584
unix  3      [ ]         STREAM     CONNECTED     18689    /run/user/1000/bus
unix  3      [ ]         STREAM     CONNECTED     21599
unix  3      [ ]         STREAM     CONNECTED     19790
unix  3      [ ]         DGRAM                    12055
unix  3      [ ]         STREAM     CONNECTED     19619    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     18009
unix  3      [ ]         DGRAM                    17912
unix  3      [ ]         DGRAM                    18191
unix  3      [ ]         STREAM     CONNECTED     18081    @/tmp/.X11-unix/X0
unix  3      [ ]         STREAM     CONNECTED     18657
unix  3      [ ]         STREAM     CONNECTED     17688
unix  3      [ ]         STREAM     CONNECTED     18821    @/tmp/.X11-unix/X0
unix  3      [ ]         DGRAM                    12056
unix  2      [ ]         DGRAM                    18685
unix  3      [ ]         STREAM     CONNECTED     21717    /run/user/1000/bus
unix  3      [ ]         STREAM     CONNECTED     20743    /run/user/1000/bus
unix  3      [ ]         STREAM     CONNECTED     20000    @/tmp/.X11-unix/X0
unix  3      [ ]         STREAM     CONNECTED     14029    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     18708
unix  3      [ ]         STREAM     CONNECTED     19641
unix  3      [ ]         DGRAM                    12054
unix  3      [ ]         STREAM     CONNECTED     19549    @/tmp/.X11-unix/X0
unix  3      [ ]         STREAM     CONNECTED     15744    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     21761
unix  3      [ ]         STREAM     CONNECTED     18684    /run/user/1000/bus
unix  3      [ ]         STREAM     CONNECTED     18012
unix  3      [ ]         STREAM     CONNECTED     19547
unix  3      [ ]         STREAM     CONNECTED     14940
unix  3      [ ]         STREAM     CONNECTED     17894
unix  3      [ ]         STREAM     CONNECTED     17936
unix  2      [ ]         DGRAM                    14868
unix  3      [ ]         DGRAM                    18190
unix  3      [ ]         STREAM     CONNECTED     21735
unix  3      [ ]         STREAM     CONNECTED     18106    @/tmp/.X11-unix/X0
unix  3      [ ]         STREAM     CONNECTED     16022    /run/systemd/journal/stdout
unix  2      [ ]         DGRAM                    17903
unix  3      [ ]         STREAM     CONNECTED     17354
unix  3      [ ]         STREAM     CONNECTED     20745    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     14031    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     11212
unix  3      [ ]         STREAM     CONNECTED     18592    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     20011    @/tmp/.X11-unix/X0
unix  3      [ ]         STREAM     CONNECTED     19660
unix  3      [ ]         STREAM     CONNECTED     15483    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     16284    /var/run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     14717
unix  3      [ ]         STREAM     CONNECTED     18740
unix  3      [ ]         STREAM     CONNECTED     17961    @/tmp/.X11-unix/X0
unix  3      [ ]         STREAM     CONNECTED     19791
unix  3      [ ]         DGRAM                    12057
unix  3      [ ]         STREAM     CONNECTED     14235
unix  3      [ ]         STREAM     CONNECTED     19642
unix  3      [ ]         STREAM     CONNECTED     18658
unix  3      [ ]         STREAM     CONNECTED     17477
unix  3      [ ]         STREAM     CONNECTED     21582
unix  3      [ ]         STREAM     CONNECTED     18660    /run/user/1000/bus
unix  3      [ ]         STREAM     CONNECTED     17036
unix  2      [ ]         DGRAM                    17900
unix  3      [ ]         STREAM     CONNECTED     11213    /run/systemd/journal/stdout
unix  3      [ ]         STREAM     CONNECTED     18166
unix  2      [ ]         DGRAM                    15317
unix  3      [ ]         STREAM     CONNECTED     14191    /var/run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     18105
unix  3      [ ]         STREAM     CONNECTED     15268
unix  3      [ ]         STREAM     CONNECTED     18750    /run/systemd/journal/stdout
unix  2      [ ]         STREAM     CONNECTED     17443
unix  3      [ ]         STREAM     CONNECTED     16270    /var/run/dbus/system_bus_socket
unix  3      [ ]         STREAM     CONNECTED     18109    @/tmp/.X11-unix/X0
unix  3      [ ]         STREAM     CONNECTED     19552    @/tmp/.X11-unix/X0
unix  3      [ ]         STREAM     CONNECTED     21637
unix  3      [ ]         STREAM     CONNECTED     18023    @/tmp/.X11-unix/X0
unix  3      [ ]         STREAM     CONNECTED     20701    /run/user/1000/bus
unix  3      [ ]         STREAM     CONNECTED     21736
unix  3      [ ]         STREAM     CONNECTED     18705    /run/user/1000/bus
```
