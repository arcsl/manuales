# Manual Logo 8 de Siemens mediante pantalla integrada

## Introducción

El PLC Logo 8 de Siemens es un controlador lógico programable compacto y versátil que se utiliza en diversas aplicaciones de automatización. Este manual describe cómo utilizar la pantalla integrada del PLC para configurar y monitorear el dispositivo.

## Contenidos

1. [Encendido y Acceso Inicial](#1-encendido-y-acceso-inicial)
2. [Navegación Básica en la Pantalla](#2-navegación-básica-en-la-pantalla)
3. [Configuración del Sistema](#3-configuración-del-sistema)
4. [Monitoreo de Entradas y Salidas](#4-monitoreo-de-entradas-y-salidas)
5. [Modificación de Parámetros](#5-modificación-de-parámetros)
6. [Mensajes de Alerta y Diagnóstico](#6-mensajes-de-alerta-y-diagnóstico)
7. [Mantenimiento y Solución de Problemas](#7-mantenimiento-y-solución-de-problemas)

## 1. Encendido y Acceso Inicial

### 1.1 Encendido del PLC

1. Conecte y encienda la fuente de alimentación al PLC.
2. La pantalla integrada se encenderá y mostrará el estado inicial o la pantalla principal si hay alguna configurada.

### 1.2 Pantalla principal

1. Si su aplicacion está correctamente configurada e iniciada por ARC, la pantalla principal mostará los valores de las entradas mas relevantes con un texto descriptivo.

<!-- <div style="page-break-after: always;"></div> -->

### 1.3 Estado Inicial

1. En caso de que tener la aplicacion configurada e iniciada pero sin ninguna pantalla principal, el PLC mostrara la fecha y la hora actuales:
<div style="text-align: center;">
<img src="imagenes/horafecha.png" alt="Hora y Fecha" style="width:50%;"/>
</div>

2. Tambien puede mostrar una de las 9 pantallas similares a esta donde se muestran los valores actuales de entradas y salidas

<img src="imagenes/digInputs.png" alt="Entradas digitales" style="width:50%;"/>

3. puede moverse entre esas 9 pantallas y la de fecha y hora usando las teclas direccionales derecha e izquierda.

4. Por ultimo, en caso de no tener aplicacion configurada o no estar iniciada la pantalla mostrará el menu principal:

<img src="imagenes/menu.png" alt="Menú principal" style="width:50%;"/>

## 2. Navegación Básica en la Pantalla

### 2.1 Botones de Navegación

- **Flechas**: Utilice las flechas arriba, abajo, izquierda y derecha para navegar por las opciones del menú.
- **Enter (OK)**: Selecciona la opción resaltada.
- **Escape (ESC)**: Regresa al menú anterior o cancela la operación actual.

### 2.2 Menú Principal

El menú principal incluye las siguientes opciones:
- Estado del Sistema
- Entradas/Salidas
- Configuración
- Diagnóstico
- Parámetros del Usuario

## 3. Configuración del Sistema

### 3.1 Ajustes de Fecha y Hora

1. En el menú principal, seleccione "Configuración" y presione **Enter**.
2. Seleccione "Fecha y Hora" y presione **Enter**.
3. Use las flechas para ajustar la fecha y la hora, y presione **Enter** para confirmar.

### 3.2 Ajustes de Red

1. En "Configuración", seleccione "Red" y presione **Enter**.
2. Configure los parámetros de red como la dirección IP, máscara de subred y puerta de enlace.
3. Presione **Enter** para guardar los cambios.

## 4. Monitoreo de Entradas y Salidas

### 4.1 Ver Estado de Entradas

1. En el menú principal, seleccione "Entradas/Salidas" y presione **Enter**.
2. Seleccione "Entradas" y presione **Enter**.
3. La pantalla mostrará el estado actual de las entradas digitales y analógicas.

### 4.2 Ver Estado de Salidas

1. En "Entradas/Salidas", seleccione "Salidas" y presione **Enter**.
2. La pantalla mostrará el estado actual de las salidas digitales y analógicas.

## 5. Modificación de Parámetros

### 5.1 Ajuste de Parámetros del Usuario

1. En el menú principal, seleccione "Parámetros del Usuario" y presione **Enter**.
2. Seleccione el parámetro que desea modificar.
3. Use las flechas para cambiar el valor y presione **Enter** para confirmar.

## 6. Mensajes de Alerta y Diagnóstico

### 6.1 Ver Mensajes de Alerta

1. En el menú principal, seleccione "Diagnóstico" y presione **Enter**.
2. Seleccione "Mensajes de Alerta" para ver una lista de alertas actuales y anteriores.

### 6.2 Diagnóstico del Sistema

1. En "Diagnóstico", seleccione "Diagnóstico del Sistema" y presione **Enter**.
2. Revise la información de diagnóstico para identificar problemas potenciales.

## 7. Mantenimiento y Solución de Problemas

### 7.1 Reinicio del PLC

1. Si es necesario, puede reiniciar el PLC apagándolo y volviéndolo a encender.
2. Asegúrese de guardar cualquier configuración antes de reiniciar.

### 7.2 Restauración de Configuración de Fábrica

1. En el menú principal, seleccione "Configuración" y presione **Enter**.
2. Seleccione "Restaurar Configuración de Fábrica" y confirme con **Enter**.
