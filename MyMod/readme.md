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
