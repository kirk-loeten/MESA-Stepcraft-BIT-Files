# my Modings

PIN  PWM

## init
Check default
```
$ sudo mesaflash --device 5i25 --readhmid
```
Write bit-file in fallback memory
```
$ sudo mesaflash --device 5i25 --fallback --write SC_34.bit
```
Load fallback memory
```
$ sudo mesaflash --device 5i25 --fallback --reload
```
Check used config
```
$ sudo mesaflash --device 5i25 --readhmid
```


<a href="http://www.youtube.com/watch?feature=player_embedded&v=vfJyw-WCSp4
" target="_blank"><img src="http://img.youtube.com/vi/vfJyw-WCSp4/0.jpg" 
alt="#2 LinuxCNC + 5i25 - custom bitfile - Xilinx + Mesaflash" width="240" height="180" border="10" /></a>
