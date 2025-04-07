> The Official Repository for Group 5 for the COM 617 Industrial consulting course.
>



## EVENTS CONFIGURATION DB 8008

<uei>uei.opennms.org/traps/DB8008-MIB/notifTest</uei>	
```sh
 snmptrap -v 2c -c public 192.168.105.245:1162 "" .1.3.6.1.4.1.35833.6.254.1    .1.3.6.1.4.1.52330.6.2.1.0 i 0  .1.3.6.1.4.1.52330.6.2.5.0 i 1

```

trap for the notif source change 
```sh
snmptrap -v 2c -c public 192.168.105.245:1162 "" .1.3.6.1.4.1.35833.6.254.2    .1.3.6.1.4.1.52330.6.2.1.0 i 1  .1.3.6.1.4.1.52330.6.2.5.0 i 1
```

trap for syncloss insel2mainaudio
```sh
snmptrap -v 2c -c public 192.168.105.245:1162 "" .1.3.6.1.4.1.35833.6.254.3    .1.3.6.1.4.1.52330.6.2.1.0 i 1  .1.3.6.1.4.1.52330.6.2.5.0 i 1
```

trap for sync recover insel2mainaudio
```sh
snmptrap -v 2c -c public 192.168.105.245:1162 "" .1.3.6.1.4.1.35833.6.254.4    .1.3.6.1.4.1.52330.6.2.1.0 i 1  .1.3.6.1.4.1.52330.6.2.5.0 i 1
```

trap for syncloss insel2AuxAudio
```sh
snmptrap -v 2c -c public 192.168.105.245:1162 "" .1.3.6.1.4.1.35833.6.254.5    .1.3.6.1.4.1.52330.6.2.1.0 i 1  .1.3.6.1.4.1.52330.6.2.5.0 i 1
```

trap for sync recover insel2AuxAudio
```sh
snmptrap -v 2c -c public 192.168.105.245:1162 "" .1.3.6.1.4.1.35833.6.254.6    .1.3.6.1.4.1.52330.6.2.1.0 i 1  .1.3.6.1.4.1.52330.6.2.5.0 i 1
```

trap for  insel2ipaudioclient1
```
snmptrap -v 2c -c public 192.168.105.245:1162 "" .1.3.6.1.4.1.35833.6.254.7    .1.3.6.1.4.1.52330.6.2.1.0 i 1  .1.3.6.1.4.1.52330.6.2.5.0 i 1
```

clear:
```
snmptrap -v 2c -c public 192.168.105.245:1162 "" .1.3.6.1.4.1.35833.6.254.8    .1.3.6.1.4.1.52330.6.2.1.0 i 1  .1.3.6.1.4.1.52330.6.2.5.0 i 1

```





