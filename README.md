# H2infw
Esta desarrollado en bat , usando comandos DDos / cmd.
Muestra información de configuración detallada sobre una computadora y su sistema operativo, incluida la configuración del sistema operativo, la información de seguridad, la ID del producto y las propiedades del hardware (como RAM, espacio en disco y tarjetas de red).
https://lpericena.blogspot.com/2018/10/H2infw.html
![](https://4.bp.blogspot.com/-m1qSYKgmO5Y/W8p6xPNJTNI/AAAAAAAAMhs/SpiaweImZ2wC3aCwAyd8q-QQ2A9rkTlIQCLcBGAs/s1600/Screenshot_6.png)
### Código
```
@echo off
TITLE H2infw
MODE con: cols=45 lines=10
COLOR 0C
del H2infw.txt
echo.          _    _ ___  _        __          
echo.         ^| ^|  ^| ^|__ \(_)      / _^|         
echo.         ^| ^|__^| ^|  ) ^|_ _ __ ^| ^|___      __
echo.         ^|  __  ^| / /^| ^| '_ \^|  _\ \ /\ / /
echo.         ^| ^|  ^| ^|/ /_^| ^| ^| ^| ^| ^|  ^\ V  V / 
echo.         ^|_^|  ^|_^|____^|_^|_^| ^|_^|_^|   ^\_/\_/  
echo.        Autor: Luishino Pericena Choque
echo.       https://lpericena.blogspot.com/
net user>>H2infw.txt
hostname >>H2infw.txt
systeminfo >>H2infw.txt
systeminfo %hostname% | find "K">>H2infw.txt
exit
```


#### Descargar https://github.com/Pericena/H2infw/blob/master/Descargar/H2infw.zip

### Donación paypal
https://www.paypal.com/paypalme/lpericena


### Sigueme en las redes Sociales:
- 🌎Blogger          https://lpericena.blogspot.com/
- 💡 Github            https://github.com/Pericena
