# Guía de instalación Automatización - Móvil
## Requerimiento
1. [IntelliJ](https://www.jetbrains.com/es-es/idea/).
2. [Java SE (JDK 8 U 11)](https://www.oracle.com/java/technologies/downloads/).
3. [NodeJS](https://nodejs.org/es/).
4. [Android studio](https://developer.android.com/studio).
5. [Appium (1.17.1)](https://discuss.appium.io/t/appium-desktop-1-17-1-rc1-is-released/30754).

## Configuracion

![alt text](https://github.com/Maycolx/Automation-M-vil/blob/master/Movile%20automation/EV.png)

![alt text](https://github.com/Maycolx/Automation-M-vil/blob/master/Movile%20automation/C.png)

## Configurar Dispositivo

* Activar Modo desarrollador.
* Activar el modo depuración.

## Detectar Dispositivo en la PC
Abrir la consola de comandos (CMD) y pegar los siguientes comandos:
```
cd %android_home%\platform-tools\
```
```
adb devices -l
```

Listará todos los dispositivos encontrados
![alt text](https://github.com/Maycolx/Automation-M-vil/blob/master/Movile%20automation/dev.png)

***Si su dispostivo no se encuentra. asegurese que su dispositivo este conectado en la PC y que esté habilitado el modo desarrollador y depuración***

## Appium

Iniciamos el servidor

![alt text](https://github.com/Maycolx/Automation-M-vil/blob/master/Movile%20automation/Appium1.png)

![alt text](https://github.com/Maycolx/Automation-M-vil/blob/master/Movile%20automation/Appium2.png)

## Configurar inspector de Sesión

| capabilities        | Descripción        |
| -------------       |:------------------:|
| automationName      | Define el motor de automatizacióna utilizar.Los valores posibles son:Para **Android**: Appium, UiAutomator2, Espresso, UiAutomator1.Para **iOS**:XCUITest o InstrumentsYou.i Engine: YouiEngine |
| plataformName       | Que sistema operativo del dispositivo usaremos. Valores posibles: Android, iOS, FirefoxOS  |
| plataformVersion    | Versióndel sistema operativo del dispositivo móvil.     |
| deviceName          |El nombre del dispositivo móvil o emulador a usar. *Copiar el nombre del dispositivo mostrado por el resultado mostrado en la consola de comandos*|

![alt text](https://github.com/Maycolx/Automation-M-vil/blob/master/Movile%20automation/Inspector%20sesion.png)
