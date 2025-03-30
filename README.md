# CURSO PLC LOGO CON EJEMPLOS

- [CURSO PLC LOGO CON EJEMPLOS](#curso-plc-logo-con-ejemplos)
  - [INTRODUCCIÓN](#introducción)
  - [Marcha-Paro por Impulso](#marcha-paro-por-impulso)
    - [Arranque de un motor trifásico por impulso con luz de piloto](#arranque-de-un-motor-trifásico-por-impulso-con-luz-de-piloto)
    - [Conexión en 3D PLC LOGO en CADeSimu](#conexión-en-3d-plc-logo-en-cadesimu)
  - [Marcha-Paro con Tres Luces Piloto](#marcha-paro-con-tres-luces-piloto)
    - [Arranque de un Motor Trifásico](#arranque-de-un-motor-trifásico)
  - [Marcha-Paro con dos Putos de Encenddo y tres Luces](#marcha-paro-con-dos-putos-de-encenddo-y-tres-luces)

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

![alt text](image-4.png "Esquema cableado marcha-paro motor trifásico"){width=75%}
![alt text](image-5.png "Esquema marcha-paro en KOP")
![alt text](image-6.png "Esquem marcha-paro en FUP")
![alt text](image-7.png "Esquema conexión LOGO al circuito")
![alt text](image-8.png "Programa KOP para LOGO")

- - -

## Marcha-Paro con dos Putos de Encenddo y tres Luces