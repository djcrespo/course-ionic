# Interacción con el dispositivo

## Capacitor

Es un framework desarrollado por el equipo de Ionic que nos permite comunicarnos a las API nativas de los dispositivos, dando la posibilidad acceder y usar las características y funcionalidades del dispositivo, como la cámara, GPS, almacenamiento y muchas otras.

## Requisitos para compilar una app

Es necesario tener los IDE de desarrollo de Android y iOS para poder compilar, para eso necesitamos seguir con las siguientes instrucciones:

### Advertencia

Se recomienda usar linux o MacOS para evitar conflictos con PowerShell y variables de entorno (Windows)

### Android

Para compilar en dispositivos android es necesario tener instalado y configurado en IDE "Android Studio", lo puedes descargar a través de la herramienta de [JetBrains Tolbox](https://www.jetbrains.com/toolbox-app/) o desde la página oficial de [Android Studio](https://developer.android.com/studio).

### IOS

Para compilar en dispositivos apple es necesario que tengamos un entorno con MacOS para poder firmar las apps desarrolladas por nosotros.

Puedes descargar el XCode puedes descargar el IDE en la App Store.

## Plugins

En la página oficial encontraremos una variedad de herramientas que podemos integrar en nuestro proyecto de manera facil siguiendo las instrucciones del cada uno de estos, para eso puedes hacer click [acá](https://ionicframework.com/docs/native) para ver a detalle los "plugins" que tienes a tu disposición.

## Pasos a seguir para compilar nuestro proyecto en una plataforma

Es importante mencionar que para eso necesitamos previamente compilar nuestro proyecto, para ello necesitamos hacer lo siguiente:

```bash
 ionic build
```

Podemos pasarle otros parametros para ver 
