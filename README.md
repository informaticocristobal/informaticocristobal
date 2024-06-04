# La Máquina del Tiempo - Proyecto de Presupuestos

La máquina del tiempo
la empresa fue creada con el objetivo de crear relojes de diferentes épocas y estilos para su
posterior venta a distintos proveedores.
Es una empresa que refleja la evolución entre el diseño, la tecnología y la visualización tiempo.
Para cumplir con la misión de la empresa se realizaron diferentes investigaciones y selecciones de la calidad de los relojes, permitiendo crear con éxito la empresa y abriendo las puertas al público, la máquina del tiempo se a convertido en una empresa muy popular para los amantes de los
relojes de calidad.

## Objetivo del Proyecto

El objetivo de este proyecto es desarrollar un sistema de facturación que permita gestionar los productos y generar presupuestos para los clientes, solicitando los datos necesarios de la empresa.

## Requisitos

### Requisitos Funcionales

1. **Gestión de Productos:**
     Registro y actualización de productos.
     Control de inventario y stock.
     Búsqueda y visualización de productos.

2. **Gestión de Facturas:**
     Creación y edición de facturas.
     Asociación de facturas a clientes.
     Cálculo automático de impuestos y totales.
     Envío de facturas por correo electrónico.

3. **Pago y Cobranza:**
     Registro de pagos.
     Asociación de pagos a facturas.
     Generación de recibos de pago.

4. **Notificaciones y Comunicaciones:**
     Envío de facturas y presupuestos por correo electrónico.
     Recordatorios de pago a clientes.

5. **Acceso y Seguridad:**
     Control de acceso basado en roles.
     Autenticación segura de usuarios.
     Registro de actividad de los usuarios.

### Requisitos No Funcionales

1. **Rendimiento:**
     Manejo eficiente de múltiples usuarios simultáneos.
     Tiempos de respuesta rápidos (menos de 2 segundos).

2. **Escalabilidad:**
     Capacidad de escalar horizontal y verticalmente.
     Diseño modular para facilitar la adición de nuevas funcionalidades.

3. **Seguridad:**
     Cifrado de datos sensibles.
     Protección contra ataques comunes.

4. **Disponibilidad:**
     Alta disponibilidad (99.9% de tiempo de actividad).
     Respaldo y recuperación ante desastres.

5. **Usabilidad:**
     Interfaz intuitiva y fácil de usar.
     Soporte multilenguaje.

6. **Compatibilidad:**
     Compatible con principales navegadores (Chrome, Firefox, Safari, Edge).
     Aplicación móvil compatible con Android e iOS.

7. **Mantenimiento:**
     Documentación clara y detallada.
     Procedimientos definidos para actualizaciones y mantenimiento.

8. **Sistema de fácil uso:**
     Simplificación en la navegación y uso del sistema.

## Tecnologías Utilizadas

- **Lenguaje de Programación:** Python
- **Framework:** Django

## Instalación

### Instalación de Python

1. Descarga e instala Python desde la página oficial: [Python Downloads](https://www.python.org/downloads/)

### Creación de un Entorno Virtual

1. Abre el cmd y navega a la carpeta donde deseas crear el proyecto.
2. Ejecuta los siguientes comandos:

```bash
python -m venv myenv
```bash
myenv\Scripts\activate
```bash
pip install django
```bash
django-admin startproject myproject
```bash
cd myproject
```bash
python manage.py runserver
```bash
python manage.py migrate
```bash
python manage.py createsuperuser
