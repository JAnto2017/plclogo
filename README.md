# CURSO PLC LOGO CON EJEMPLOS

- [CURSO PLC LOGO CON EJEMPLOS](#curso-plc-logo-con-ejemplos)
  - [INTRODUCCIÓN](#introducción)
  - [Marcha-Paro por Impulso](#marcha-paro-por-impulso)
    - [Arranque de un motor trifásico por impulso con luz de piloto](#arranque-de-un-motor-trifásico-por-impulso-con-luz-de-piloto)
    - [Conexión en 3D PLC LOGO en CADeSimu](#conexión-en-3d-plc-logo-en-cadesimu)
  - [Marcha-Paro con Tres Luces Piloto](#marcha-paro-con-tres-luces-piloto)
    - [Arranque de un Motor Trifásico](#arranque-de-un-motor-trifásico)
  - [Marcha-Paro con dos Putos de Encenddo y tres Luces](#marcha-paro-con-dos-putos-de-encenddo-y-tres-luces)
    - [Arranque de un Motor con dos Puntos de Encendido](#arranque-de-un-motor-con-dos-puntos-de-encendido)
  - [Inversión de Sentido de Giro Motor Monofásico](#inversión-de-sentido-de-giro-motor-monofásico)
    - [Arranque Motor Monofásico con Inversión de Giro](#arranque-motor-monofásico-con-inversión-de-giro)
  - [Inversión de Sentido de Giro Motor Trifásico](#inversión-de-sentido-de-giro-motor-trifásico)
    - [Esquema de contactos cableado Giro Motor Trifásico](#esquema-de-contactos-cableado-giro-motor-trifásico)
    - [Esquema KOP y conexiones en CADe-SIMU Giro Motor Trifásico](#esquema-kop-y-conexiones-en-cade-simu-giro-motor-trifásico)
  - [Arranque de un Motor Trifásico con Apagado Programado](#arranque-de-un-motor-trifásico-con-apagado-programado)
    - [Esquema de contactos cableado con Apagado Programado](#esquema-de-contactos-cableado-con-apagado-programado)
    - [Esquema KOP y conexiones en CADe-SIMU Apagado Motor Trifásico](#esquema-kop-y-conexiones-en-cade-simu-apagado-motor-trifásico)
  - [Arranque de un Motor Trifásico con Retraso en Encendido](#arranque-de-un-motor-trifásico-con-retraso-en-encendido)
    - [Esquema de contactos cableado con Retraso en Encendido](#esquema-de-contactos-cableado-con-retraso-en-encendido)
    - [Esquema KOP y conexiones en LOGO-SOFT/CADe-SIMU Retraso en Encendido](#esquema-kop-y-conexiones-en-logo-softcade-simu-retraso-en-encendido)
  - [Marcha con Retardo y Apagado Automático Motor Trifásico](#marcha-con-retardo-y-apagado-automático-motor-trifásico)
    - [Esquema de contactos cableado con Retardo y Apagado Automático Motor Trifásico](#esquema-de-contactos-cableado-con-retardo-y-apagado-automático-motor-trifásico)
    - [Esquema KOP y conexiones en CADe-SIMU Retardo y Apagado Automático Motor Trifásico](#esquema-kop-y-conexiones-en-cade-simu-retardo-y-apagado-automático-motor-trifásico)
  - [Arranque Estrello-Triángulo Motor Trifásico con Temporizador](#arranque-estrello-triángulo-motor-trifásico-con-temporizador)
    - [Esquema de contactos cableado con Arranque Estrello-Triángulo con Temporizador](#esquema-de-contactos-cableado-con-arranque-estrello-triángulo-con-temporizador)
    - [Esquema KOP y conexiones en CADe-SIMU Arranque Estrello-Triángulo con Temporizador](#esquema-kop-y-conexiones-en-cade-simu-arranque-estrello-triángulo-con-temporizador)
  - [Arranque de un Motor Trifásico Estrella-Triángulo con Temporizador e Inversión de Giro](#arranque-de-un-motor-trifásico-estrella-triángulo-con-temporizador-e-inversión-de-giro)
    - [Esquema de contactos cableado con Arranque Estrello-Triángulo con Temporizador e Inversión de Giro](#esquema-de-contactos-cableado-con-arranque-estrello-triángulo-con-temporizador-e-inversión-de-giro)
    - [Esquema KOP y conexiones en CADe-SIMU Arranque Estrello-Triángulo con Temporizador e Inversión de Giro](#esquema-kop-y-conexiones-en-cade-simu-arranque-estrello-triángulo-con-temporizador-e-inversión-de-giro)
  - [Inversión de Giro Motor Monofásico](#inversión-de-giro-motor-monofásico)
    - [Esquema de contactos cableado Inversión de Giro Motor Monofásico](#esquema-de-contactos-cableado-inversión-de-giro-motor-monofásico)
    - [Esquema KOP y conexiones en CADe-SIMU Inversión de Giro Motor Monofásico](#esquema-kop-y-conexiones-en-cade-simu-inversión-de-giro-motor-monofásico)
  - [Inversión de Giro Motor Trifásico con sentido de giro de forma cíclica](#inversión-de-giro-motor-trifásico-con-sentido-de-giro-de-forma-cíclica)
    - [Esquema de contactos cableado Inversión de Giro Motor Trifásico con sentido de giro de forma cíclica](#esquema-de-contactos-cableado-inversión-de-giro-motor-trifásico-con-sentido-de-giro-de-forma-cíclica)
    - [Esquema KOP y conexiones en CADe-SIMU Inversión de Giro Motor Trifásico con sentido de giro de forma cíclica](#esquema-kop-y-conexiones-en-cade-simu-inversión-de-giro-motor-trifásico-con-sentido-de-giro-de-forma-cíclica)
  - [Inversión de Giro Motor Monofásico sin secuencia cíclica](#inversión-de-giro-motor-monofásico-sin-secuencia-cíclica)
    - [Esquema de contactos cableado Inversión de Giro Motor Monofásico sin secuencia cíclica](#esquema-de-contactos-cableado-inversión-de-giro-motor-monofásico-sin-secuencia-cíclica)
    - [Esquema KOP Inversión de Giro Motor Monofásico sin secuencia cíclica](#esquema-kop-inversión-de-giro-motor-monofásico-sin-secuencia-cíclica)
  - [Arranque Secuencial de dos Motores Trifásicos](#arranque-secuencial-de-dos-motores-trifásicos)
    - [Esquema de contactos cableado Arranque Secuencial de dos Motores Trifásicos](#esquema-de-contactos-cableado-arranque-secuencial-de-dos-motores-trifásicos)
    - [Esquema KOP Arranque Secuencial de dos Motores Trifásicos](#esquema-kop-arranque-secuencial-de-dos-motores-trifásicos)
  - [Arranque Secuencial de dos Motores Trifásicos con Retraso en el Encendido](#arranque-secuencial-de-dos-motores-trifásicos-con-retraso-en-el-encendido)
    - [Esquema de contactos cableado Arranque Secuencial de dos Motores Trifásicos con Retraso en el Encendido](#esquema-de-contactos-cableado-arranque-secuencial-de-dos-motores-trifásicos-con-retraso-en-el-encendido)
    - [Esquema KOP Arranque Secuencial de dos Motores Trifásicos con Retraso en el Encendido](#esquema-kop-arranque-secuencial-de-dos-motores-trifásicos-con-retraso-en-el-encendido)
  - [Arranque Secuencial de dos Motores Trifásicos con Retraso en el Encendido y Apagado Automático](#arranque-secuencial-de-dos-motores-trifásicos-con-retraso-en-el-encendido-y-apagado-automático)
    - [Esquema de contactos cableado Arranque Secuencial de dos Motores Trifásicos con Retraso en el Encendido y Apagado Automático](#esquema-de-contactos-cableado-arranque-secuencial-de-dos-motores-trifásicos-con-retraso-en-el-encendido-y-apagado-automático)
    - [Esquema KOP Arranque Secuencial de dos Motores Trifásicos con Retraso en el Encendido y Apagado Automático](#esquema-kop-arranque-secuencial-de-dos-motores-trifásicos-con-retraso-en-el-encendido-y-apagado-automático)
  - [Arranque de dos Motores Trifásicos con Retraso en el Encendido y Apagado Automático](#arranque-de-dos-motores-trifásicos-con-retraso-en-el-encendido-y-apagado-automático)
    - [Esquema KOP Arranque de dos Motores Trifásicos con Retraso en el Encendido y Apagado Automático](#esquema-kop-arranque-de-dos-motores-trifásicos-con-retraso-en-el-encendido-y-apagado-automático)
  - [Arranque Secuencial de tres Motores Trifásicos](#arranque-secuencial-de-tres-motores-trifásicos)
    - [Esquema de contactos cableado Arranque Secuencial de tres Motores Trifásicos](#esquema-de-contactos-cableado-arranque-secuencial-de-tres-motores-trifásicos)
    - [Esquema KOP Arranque Secuencial de tres Motores Trifásicos](#esquema-kop-arranque-secuencial-de-tres-motores-trifásicos)
  - [Arranque Secuencial de tres Motores Trifásicos con Retraso en el Encendido](#arranque-secuencial-de-tres-motores-trifásicos-con-retraso-en-el-encendido)
    - [Esquema de contactos cableado Arranque Secuencial de tres Motores Trifásicos con Retraso en el Encendido](#esquema-de-contactos-cableado-arranque-secuencial-de-tres-motores-trifásicos-con-retraso-en-el-encendido)
    - [Esquema KOP Arranque Secuencial de tres Motores Trifásicos con Retraso en el Encendido](#esquema-kop-arranque-secuencial-de-tres-motores-trifásicos-con-retraso-en-el-encendido)
  - [Arranque Secuencial de tres Motores Trifásicos con Retraso en el Encendido y Apagado Automático](#arranque-secuencial-de-tres-motores-trifásicos-con-retraso-en-el-encendido-y-apagado-automático)
    - [Esquema de contactos cableado Arranque Secuencial de tres Motores Trifásicos con Retraso en el Encendido y Apagado Automático](#esquema-de-contactos-cableado-arranque-secuencial-de-tres-motores-trifásicos-con-retraso-en-el-encendido-y-apagado-automático)
    - [Esquema KOP Arranque Secuencial de tres Motores Trifásicos con Retraso en el Encendido y Apagado Automático](#esquema-kop-arranque-secuencial-de-tres-motores-trifásicos-con-retraso-en-el-encendido-y-apagado-automático)
  - [Arranque de tres Motores Trifásicos con Retraso en el Encendido y Apagado Automático y Retención](#arranque-de-tres-motores-trifásicos-con-retraso-en-el-encendido-y-apagado-automático-y-retención)
    - [Esquema de contactos cableado Arranque de tres Motores Trifásicos con Retraso en el Encendido y Apagado Automático y Retención](#esquema-de-contactos-cableado-arranque-de-tres-motores-trifásicos-con-retraso-en-el-encendido-y-apagado-automático-y-retención)
    - [Esquema KOP Arranque de tres Motores Trifásicos con Retraso en el Encendido y Apagado Automático y Retención](#esquema-kop-arranque-de-tres-motores-trifásicos-con-retraso-en-el-encendido-y-apagado-automático-y-retención)
  - [Semáforo Básico con dos Luces](#semáforo-básico-con-dos-luces)

- - -

## INTRODUCCIÓN

- CADe-Simu v4
- LOGO-SOFT v3 (disponible v4)

Para programas con problemas de compatibilidad en W10,sobre el icono de la aplicación, clic en botón derecho y seleccionar _Propiedades > Compatibilidad_. Marcar la opción: _Ejecutar este programa como admnistrador_. Hacer clic en _Cambiar configuración elevada de PPP_. Marcar: _Invalidar el comportaminto de ajuste de PPP alto_. Desplegar y seleccionar: _Sistema_. Aceptar y aplicar cambios.

- - -

## Marcha-Paro por Impulso

### Arranque de un motor trifásico por impulso con luz de piloto

Esquema cableado del _Marcha-Paro_:

![alt text](image.png "Marcha paro por impulso")

Esquema de contactos en KOP del _Marcha-Paro_. Se utilizan dos pulsadores normalmente abiertos para las entradas I1 e I2 correspondientes al _Marcha S1_ y al _Paro S2_. El térmico es un interruptor:

![alt text](image-1.png "Esquema de contactos KOP")

### Conexión en 3D PLC LOGO en CADeSimu

![alt text](image-2.png "Conexión en 3D PLC LOGO en CADeSimu")
![alt text](image-3.png "Esquema KOP para el LOGO")

- - -

## Marcha-Paro con Tres Luces Piloto

### Arranque de un Motor Trifásico

> [!tip]
> **Contacto Directo**. Se comporta de manera directa a la realidad.</br>
> **Contacto Negado**. Se comporta de manera inversa a la realidad.

![alt text](image-4.png "Esquema cableado marcha-paro motor trifásico")
![alt text](image-5.png "Esquema marcha-paro en KOP")
![alt text](image-6.png "Esquem marcha-paro en FUP")
![alt text](image-7.png "Esquema conexión LOGO al circuito")
![alt text](image-8.png "Programa KOP para LOGO")

- - -

## Marcha-Paro con dos Putos de Encenddo y tres Luces

### Arranque de un Motor con dos Puntos de Encendido

![alt text](image-9.png "Esquema cableado marcha-paro dos pusadores")
![alt text](image-10.png "Programa en KOP marcha-paro dos pusadores")
![alt text](image-11.png "Programa en FUP marcha-paro dos pulsadores")
![alt text](image-12.png "Detalle del relé térmico")
![alt text](image-13.png "Esquema programa KOP en CADe-SIMU")
![alt text](image-14.png "Esquem completo en CADe-SIMU")

- - -

## Inversión de Sentido de Giro Motor Monofásico

### Arranque Motor Monofásico con Inversión de Giro

![alt text](image-15.png "Esquema contactos giro motor")
![alt text](image-16.png "Programa en KOP")

- - -

## Inversión de Sentido de Giro Motor Trifásico

### Esquema de contactos cableado Giro Motor Trifásico

![alt text](image-17.png "Esquema cableado motor trifásico inversión de giro")

### Esquema KOP y conexiones en CADe-SIMU Giro Motor Trifásico

![alt text](image-18.png "Esquema KOP y conexiones en CADe-SIMU")
![alt text](image-19.png "Programa en KOP en el LOGO SOFT")

- - -

## Arranque de un Motor Trifásico con Apagado Programado

### Esquema de contactos cableado con Apagado Programado

![alt text](image-20.png "Esquema cableado con apagado programado en CADE-SIMU")
![alt text](image-23.png "Esquema cableado con apagado programado en LOGO-SOFT")

### Esquema KOP y conexiones en CADe-SIMU Apagado Motor Trifásico

![alt text](image-21.png "Esquema KOP y conexiones en CADe-SIMU")
![alt text](image-22.png "Esquema cableado LOGO con elementos en CADe-SIMU")

- - -

## Arranque de un Motor Trifásico con Retraso en Encendido

### Esquema de contactos cableado con Retraso en Encendido

Tras pulsar el botón de _Marcha_, el motor se enciende con un retraso de 3 segundos.

![alt text](image-25.png "Esquema cableado con retraso en encendido")

### Esquema KOP y conexiones en LOGO-SOFT/CADe-SIMU Retraso en Encendido

![alt text](image-24.png "Programa en KOP en LOGO-SOFT")
![alt text](image-26.png "Programa en KOP en CADe-SIMU")
![alt text](image-27.png "Esquema cableado con retraso en encendido en CADe-SIMU")

- - -

## Marcha con Retardo y Apagado Automático Motor Trifásico

### Esquema de contactos cableado con Retardo y Apagado Automático Motor Trifásico

Existe un tiempo de retardo de 3 segundos para el encendido del motor. Después de 5 segundos, el motor se apaga.

![alt text](image-28.png "Esquema cableado con retardo y apagado automático")

### Esquema KOP y conexiones en CADe-SIMU Retardo y Apagado Automático Motor Trifásico

![alt text](image-29.png "Programa en KOP en LOGO-SOFT")

- - -

## Arranque Estrello-Triángulo Motor Trifásico con Temporizador

### Esquema de contactos cableado con Arranque Estrello-Triángulo con Temporizador

![alt text](image-30.png "Esquema cableado con arranque estrello-triángulo con temporizador")

### Esquema KOP y conexiones en CADe-SIMU Arranque Estrello-Triángulo con Temporizador

![alt text](image-31.png "Programa en KOP en LOGO-SOFT activado KM1 y Estrella")
![alt text](image-32.png "Programa en KOP en LOGO-SOFT activado KM1 y Triángulo")

- - -

## Arranque de un Motor Trifásico Estrella-Triángulo con Temporizador e Inversión de Giro

### Esquema de contactos cableado con Arranque Estrello-Triángulo con Temporizador e Inversión de Giro

![alt text](image-33.png "Esquema cableado con arranque estrello-triángulo con temporizador e inversión de giro")

### Esquema KOP y conexiones en CADe-SIMU Arranque Estrello-Triángulo con Temporizador e Inversión de Giro

![alt text](image-34.png "Programa KOP en LOGO-SOFT Estrella-Triángulo con Inversión de Giro")

- - -

## Inversión de Giro Motor Monofásico

### Esquema de contactos cableado Inversión de Giro Motor Monofásico

El motor gira 10 segundos a la dercha, luego estaá 5 segundos parados para posteriromente estar girando 10 segudnos a la izquierda, vuelte a estar parado otros 5 segundos. El proceso se repite indefinidamente.

![alt text](image-35.png "Esquema cableado con inversión de giro motor monofásico con temporizadores")

### Esquema KOP y conexiones en CADe-SIMU Inversión de Giro Motor Monofásico

![alt text](image-36.png "Programa KOP en LOGO-SOFT Inversión de Giro Motor Monofásico I")
![alt text](image-37.png "Programa KOP en LOGO-SOFT Inversión de Giro Motor Monofásico II")

- - -

## Inversión de Giro Motor Trifásico con sentido de giro de forma cíclica

Tras pulsar el botón de _Marcha_, el motor se enciende durante 5 segundos. Estará 5 segundos parado y volverá a encenderse durante 5 segundos. El proceso se repite indefinidamente, cambiando el sentido de giro en cada ciclo.

### Esquema de contactos cableado Inversión de Giro Motor Trifásico con sentido de giro de forma cíclica

![alt text](image-38.png "Esquema cableado con inversión de giro motor trifásico con sentido de giro de forma cíclica")

### Esquema KOP y conexiones en CADe-SIMU Inversión de Giro Motor Trifásico con sentido de giro de forma cíclica

![alt text](image-39.png "Programa KOP parte I")
![alt text](image-40.png "Programa KOP parte II")

- - -

## Inversión de Giro Motor Monofásico sin secuencia cíclica

El motor comenzará a girar a la derecha y en un tiempo determinado cambiará el sentido de giro.

### Esquema de contactos cableado Inversión de Giro Motor Monofásico sin secuencia cíclica

![alt text](image-41.png "Esquema cableado con inversión de giro motor monofásico sin secuencia cíclica")

### Esquema KOP Inversión de Giro Motor Monofásico sin secuencia cíclica

![alt text](image-42.png "Programa KOP versión I")
![alt text](image-43.png "Programa KOP versión II")

- - -

## Arranque Secuencial de dos Motores Trifásicos

Dos motores trifásicos, se enciende uno y el segundo motor se enciende después de 5 segundos.

### Esquema de contactos cableado Arranque Secuencial de dos Motores Trifásicos

![alt text](image-44.png "Esquema cableado con arranque secuencial de dos motores trifásicos")

### Esquema KOP Arranque Secuencial de dos Motores Trifásicos

![alt text](image-45.png "Programa KOP")

- - -

## Arranque Secuencial de dos Motores Trifásicos con Retraso en el Encendido

Arraque Secuencial de dos Motores Trifásicos con Retraso en el Encendido de 3 segundos. El seegundo motor se enciende después de 5 segundos. Luz de avería activada por el relé térmico, parpadea con un perior de  0.5 segundos.

### Esquema de contactos cableado Arranque Secuencial de dos Motores Trifásicos con Retraso en el Encendido

![alt text](image-46.png "Esquema cableado con arranque secuencial de dos motores trifásicos con retraso en el encendido")

### Esquema KOP Arranque Secuencial de dos Motores Trifásicos con Retraso en el Encendido

![alt text](image-47.png "Programa KOP")

- - -

## Arranque Secuencial de dos Motores Trifásicos con Retraso en el Encendido y Apagado Automático

Se arranca e motor 1, luego se arranca el motor 2 después de 5 segundos. Cuando se apaga el motor 1, se apaga el motor 2.

### Esquema de contactos cableado Arranque Secuencial de dos Motores Trifásicos con Retraso en el Encendido y Apagado Automático

![alt text](image-48.png "Esquema cableado con arranque secuencial de dos motores trifásicos con retraso en el encendido y apagado automático")

### Esquema KOP Arranque Secuencial de dos Motores Trifásicos con Retraso en el Encendido y Apagado Automático

![alt text](image-49.png "Programa KOP")

- - -

## Arranque de dos Motores Trifásicos con Retraso en el Encendido y Apagado Automático

Se arranca e motor 1 tras un tiempo de retardo tras la pulsación del pulsador de encendido, luego de 5 segundos se arranca el motor 2. Cuando se arranca el motor 2 un temporizador se encargará de apagar.

### Esquema KOP Arranque de dos Motores Trifásicos con Retraso en el Encendido y Apagado Automático

![alt text](image-50.png "Programa KOP")

- - -

## Arranque Secuencial de tres Motores Trifásicos

Tres motores trifásicos, se encienden secuencialmente cada motor después de 5 segundos.

### Esquema de contactos cableado Arranque Secuencial de tres Motores Trifásicos

![alt text](image-51.png "Esquema cableado con arranque secuencial de tres motores trifásicos")

### Esquema KOP Arranque Secuencial de tres Motores Trifásicos

![alt text](image-52.png "Programa KOP")

- - -

## Arranque Secuencial de tres Motores Trifásicos con Retraso en el Encendido

Tres motores trifásicos, se encienden secuencialmente cada motor con un retardo de 5 segundos.

### Esquema de contactos cableado Arranque Secuencial de tres Motores Trifásicos con Retraso en el Encendido

![alt text](image-53.png "Esquema cableado con arranque secuencial de tres motores trifásicos con retraso en el encendido")

### Esquema KOP Arranque Secuencial de tres Motores Trifásicos con Retraso en el Encendido

![alt text](image-54.png "Programa KOP")

- - -

## Arranque Secuencial de tres Motores Trifásicos con Retraso en el Encendido y Apagado Automático

Tres motores trifásicos, se encienden secuencialmente cada motor con un retardo de 5 segundos. El primer motor se arranca según la pulsación del pulsador de encendido.

### Esquema de contactos cableado Arranque Secuencial de tres Motores Trifásicos con Retraso en el Encendido y Apagado Automático

![alt text](image-55.png "Esquema cableado con arranque secuencial de tres motores trifásicos con retraso en el encendido y apagado automático")

### Esquema KOP Arranque Secuencial de tres Motores Trifásicos con Retraso en el Encendido y Apagado Automático

![alt text](image-56.png "Programa KOP")

- - -

## Arranque de tres Motores Trifásicos con Retraso en el Encendido y Apagado Automático y Retención

Tres motores trifásicos, se encienden secuencialmente cada motor con un retardo de 5 segundos. El primer motor se arrancaccording con retraso en el encendido.

### Esquema de contactos cableado Arranque de tres Motores Trifásicos con Retraso en el Encendido y Apagado Automático y Retención

![alt text](image-57.png "Esquema cableado con arranque de tres motores trifásicos con retraso en el encendido y apagado automático y retención")

### Esquema KOP Arranque de tres Motores Trifásicos con Retraso en el Encendido y Apagado Automático y Retención

![alt text](image-58.png "Programa KOP")

- - -

## Semáforo Básico con dos Luces