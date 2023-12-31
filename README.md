# movvvvedorDeObjetos
movedor de objetos en 3d y replicador - con salida spout
Hecho y exportado en VVVV Gamma 5.2

## Donación:
Me di cuenta de que hacer esto lleva tiempo y esfuerzo, y que de a poco se está transformando en una herramienta "en serio"
así que se agradece una donación para poder comprarme una bolsa (de cafe) para poder seguir haciéndolo.

[![Invitame un café en cafecito.app](https://cdn.cafecito.app/imgs/buttons/button_3.svg)](https://cafecito.app/lisandroperalta)


# Descargar 

**https://github.com/lisandroperalta/movvvvedorDeObjetos/releases/**

## Modelos 3d para probar en

**https://github.com/lisandroperalta/movvvvedorDeObjetos/tree/main/modelos3DParaProbar**


![Captura de pantalla 2023-12-18 220537](https://github.com/lisandroperalta/movvvvedorDeObjetos/assets/23583735/0d27d0bd-0800-4c9b-896d-d039c7dce7fd)




# Nueva version: 005

Bastante laburo que no se ve, pero lo que se ve es lo siguiente:


![Alt text](image.png)

-[NEW] Control independiente de velocidad de giro en X e Y (el 0 tiene una tolerancia para que sea mas facil detenerlo)

-[NEW] Control independiente de velocidad de desplazamiento en X e Y (el 0 tiene una tolerancia para que sea mas facil detenerlo)

-[NEW] Control de encendido y apagador de cada una de las luces (deberia ahorrar recursos, no sé)

-[NEW] Control de color de la luz ambiente

-[CHANGED] Se configuro la salida a 1920x1080


#  version: 004

-[NEW] se pueden cargar varias texturas, se distribuirán de acuerdo a los objetos que haya

-[NEW] el quad se adapta al aspect ratio de cada textura cargada

-[FIX] para evitar crasheos, no se puede usar objeto 3d si antes no se carga uno 

-[NEW] checkbox para usar la camara con el mouse o no

-[NEW] clonado en x e y 

-[NEW] velocidad de giro ahora permite no girar el objeto

-[FIX] ahora no hay saltos en el giro, todos los objetos dan un giro completo

-[NEW] spread de giro define cada cuántas repeticiones se desfasa un objeto

-[NEW] las luces se mueven lentamente (para lograr que iluminen desde todos los ángulos posibles)

-[NEW] medidor de fps 

-[HOTFIX] corregida la velocidad de desplazamiento, ahora 0 la detiene por completo

-[CHANGED] se modifico la manera de recortar el alpha de las texturas en modo quad, ahora debería estar mejor

*Nota:* se puede hacer pan/tilt/orbit/zoom con el mouse. Presionando R se reestablece la camara


![Captura de pantalla 2023-12-19 144255](https://github.com/lisandroperalta/movvvvedorDeObjetos/assets/23583735/e7c88ada-7118-4416-96ba-ebd7dbf4d67b)



#  version: 003
-Agregado más opciones de movimiento
-Agregado de opcion de usar textura o no

![version 002](https://github.com/lisandroperalta/movvvvedorDeObjetos/assets/23583735/c54d4ab8-b81f-4cc3-80b3-617c49d10508)


# Descargar 

**https://github.com/lisandroperalta/movvvvedorDeObjetos/releases/**

## Modelos 3d para probar en

**https://github.com/lisandroperalta/movvvvedorDeObjetos/tree/main/modelos3DParaProbar**





---------------------------------------------------

**Si no funciona, se puede probar instalando las siguientes dependencias (extraido de https://thegraybook.vvvv.org/reference/hde/exporting.html#dependencies )**


**Dependencies**
If your application is referencing VL.Stride, make sure the target PC also has the following dependencies installed:

Microsoft Visual C++ Redistributables 2013 
https://aka.ms/highdpimfc2013x64enu

Microsoft Visual C++ Redistributables 2015 https://aka.ms/vs/17/release/vc_redist.x64.exe

.NET6 SDK (For FileTexture and FileModel nodes to work) https://dotnet.microsoft.com/en-us/download/dotnet/6.0

---------------------------


### IMPORTANTE
Probando, con @jpupper encontramos que puede ser que ande instalando además, este otro sdk

https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/sdk-6.0.403-windows-x64-installer

*En todo caso, con instalando el vvvv gamma funciona, aunque no lo use*
https://teamcity.vvvv.org/guestAuth/app/rest/builds/id:37342/artifacts/content/vvvv_gamma_5.2_setup.exe
