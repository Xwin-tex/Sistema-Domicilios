=========================================
  SISTEMA DE GESTIÓN Y SIMULACIÓN DE PEDIDOS A DOMICILIO MULTIZONA
=========================================

DESCRIPCIÓN GENERAL
-------------------
Este proyecto simula una plataforma de pedidos a domicilio en un entorno multizona,
similar a aplicaciones como Rappi o Uber Eats. Permite registrar y gestionar
clientes, restaurantes, domiciliarios y zonas interconectadas mediante un grafo.

El objetivo del sistema es aplicar estructuras de datos implementadas manualmente
(Listas Ligadas, Pilas, Colas, Árboles Binarios y Grafos) para simular el flujo
de pedidos sin utilizar colecciones nativas del lenguaje Python.

Cada pedido sigue un proceso que incluye su creación, asignación automática de
restaurante y domiciliario más cercano, y finalización con entrega o cancelación.


REQUISITOS TÉCNICOS
-------------------
- Lenguaje: Python 3.8 o superior
- Librerías externas: Ninguna
- Modo de ejecución: Consola / Terminal


EJECUCIÓN DEL PROGRAMA
----------------------
1. Abrir una terminal o consola en la carpeta del proyecto.
2. Ejecutar el siguiente comando:

   python "Sistemas de domicilios.py"

3. Se mostrará un menú principal con las siguientes opciones:
   - Gestión de zonas
   - Gestión de clientes
   - Gestión de restaurantes
   - Gestión de domiciliarios
   - Gestión de pedidos
   - Consultas e historiales

4. Seguir las instrucciones del menú para registrar entidades, crear pedidos
   o consultar reportes.


## ESTRUCTURA DEL PROYECTO

```
Sistemas de domicilios.py
├── Estructuras de datos personalizadas
│   ├── ListaLigada
│   ├── Pila
│   ├── Cola
│   ├── Arbol Binario
│   └── Grafo
├── Entidades principales
│   ├── Cliente
│   ├── Restaurante
│   ├── Domiciliario
│   ├── Pedido
│   └── Zona
├── Sistema de gestión
│   └── SistemaGestionPedidos
└── Interfaz
    └── MenuConsola (interfaz de texto)
```

AUTORES
-------
- Edwin Ternera
- Daniel Gamez

Estudiantes del programa de Ingeniería de Software.


PROPÓSITO ACADÉMICO
-------------------
Este proyecto fue desarrollado como trabajo final de la asignatura
"Estructuras de Datos". Su propósito es demostrar el uso práctico
de estructuras de datos personalizadas en un sistema de simulación
realista basado en la gestión de pedidos y zonas conectadas.

-----------------------------------------
Fin del archivo README.txt
-----------------------------------------
