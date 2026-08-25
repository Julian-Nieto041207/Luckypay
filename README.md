# Sistema Automatizado de Costos de Producción

Sistema de información web diseñado para pequeños emprendimientos de manufactura artesanal, con el objetivo de facilitar la gestión de insumos, productos, producción, ventas y costos de fabricación.

## 📌 Descripción del proyecto

El proyecto busca solucionar la falta de control sobre los costos de producción que presentan pequeños emprendimientos y negocios de manufactura.

Actualmente, muchos negocios registran sus compras, ventas, insumos y gastos de manera manual, lo que dificulta conocer el costo real de fabricación de sus productos y tomar decisiones adecuadas sobre los precios de venta.

El sistema permitirá centralizar y automatizar esta información para mejorar la visibilidad financiera y facilitar la toma de decisiones.

**Caso de estudio:** Michi Jabones — emprendimiento de jabones artesanales.

---

## 🎯 Objetivo general

Desarrollar e implementar un sistema de información automatizado que permita gestionar insumos y productos, calcular el costo de fabricación de cada producto, registrar la producción y las ventas realizadas, con el fin de mejorar la visibilidad financiera y la toma de decisiones.

## 🎯 Objetivos específicos

* Registrar y controlar los insumos y materiales utilizados en la producción.
* Registrar productos junto con sus recetas, insumos y cantidades requeridas.
* Calcular automáticamente el costo de fabricación por unidad.
* Registrar y comparar el precio de venta con el costo de producción.
* Registrar la producción y descontar automáticamente los insumos utilizados.
* Registrar las ventas y calcular la ganancia obtenida.
* Generar reportes de costos por producto.
* Gestionar usuarios mediante los roles **Administrador** y **Empleado**.

---

## ⚙️ Funcionalidades

### 🔐 Seguridad y usuarios

* Inicio y cierre de sesión.
* Gestión de usuarios.
* Roles de Administrador y Empleado.

### 📦 Gestión de insumos

* Registro de materias primas.
* Edición y desactivación de insumos.
* Registro de precios.
* Registro de proveedores.
* Fecha de vencimiento.
* Control de inventario.

### 🧼 Gestión de productos

* Catálogo de productos.
* Clasificación por categorías.
* Registro de recetas.
* Definición de insumos y cantidades necesarias.

### 💰 Cálculo de costos

* Cálculo automático del costo de materia prima.
* Cálculo de mano de obra directa.
* Cálculo del costo de producción por unidad.

### 🏭 Producción

* Registro de unidades fabricadas.
* Descuento automático de insumos utilizados del inventario.

### 🛒 Ventas

* Registro de ventas.
* Cálculo automático de ganancias por venta.
* Comparación entre precio de venta y costo de producción.

### 📊 Reportes

* Reportes de costos por producto.
* Visualización de información directamente en el sistema.

### 🚨 Alertas

* Notificaciones cuando el stock de un insumo sea bajo.

### 💾 Base de datos

* Almacenamiento persistente mediante una base de datos relacional.
* Copias de seguridad manuales.

---

## 🖥️ Interfaz

El sistema contará con una interfaz web responsiva, permitiendo su utilización desde:

* 💻 Computadores
* 📱 Dispositivos móviles

La interfaz será desarrollada utilizando **HTML/CSS** y podrá utilizar frameworks como **Bootstrap** o **Tailwind CSS**.

---

## 👥 Roles de usuario

| Rol           | Permisos                                           |
| ------------- | -------------------------------------------------- |
| Administrador | Acceso completo al sistema                         |
| Empleado      | Acceso a las funciones relacionadas con producción |

Los permisos están definidos de manera fija y no son configurables por el usuario.

---

## 🚫 Funcionalidades fuera del alcance

Esta versión del proyecto **no incluye**:

* Cálculo del punto de equilibrio.
* Análisis financiero avanzado.
* Distribución de costos indirectos de fabricación.
* Análisis de mercado.
* Comparación de precios con la competencia.
* Exportación de reportes a PDF o Excel.
* Integración con redes sociales o marketplaces.
* Facturación o contabilidad formal.
* Gestión de nómina.
* Múltiples sucursales o empresas.
* Aplicación móvil nativa.
* Auditoría detallada de cambios.

---

## 🏗️ Alcance del cálculo de costos

El sistema calcula el costo de producción teniendo en cuenta:

**Costo de producción = Materia prima + Mano de obra directa**

Los gastos fijos del negocio y otros costos indirectos no hacen parte del cálculo de esta versión.

---

## 📁 Estructura sugerida del proyecto

```text
Sistema-Costos-Produccion/
│
├── README.md
│
├── frontend/
│   ├── index.html
│   ├── css/
│   ├── js/
│   └── img/
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── config/
│
├── database/
│   ├── database.sql
│   └── backups/
│
├── docs/
│   └── Formulacion_del_Proyecto.pdf
│
└── .gitignore
```

---

## 🚀 Instalación

### 1. Clonar el repositorio

```bash
git clone URL_DEL_REPOSITORIO
```

### 2. Entrar al proyecto

```bash
cd Sistema-Costos-Produccion
```

### 3. Configurar la base de datos

Importar el archivo SQL ubicado en:

```text
database/database.sql
```

### 4. Configurar el proyecto

Configurar las variables necesarias para la conexión con la base de datos y los servicios utilizados por el sistema.

### 5. Ejecutar el proyecto

Iniciar el servidor según la tecnología utilizada en el backend y acceder desde el navegador.

---

## 🛠️ Tecnologías

* HTML5
* CSS3
* JavaScript
* Bootstrap o Tailwind CSS
* Base de datos relacional
* Git
* GitHub

---

## 📋 Estado del proyecto

**Versión:** 2.0
**Estado:** En desarrollo
**Área:** Gestión de costos / Manufactura artesanal
**Caso de estudio:** Michi Jabones
**Fecha:** Agosto de 2026

---

## 🎯 Misión

Brindar una solución automatizada que facilite la gestión de insumos y el cálculo del costo de producción, permitiendo a los emprendedores conocer con claridad cuánto cuesta fabricar cada producto y tomar decisiones de precio más informadas.

## 🔭 Visión

Ser una herramienta reconocida por ofrecer soluciones simples y eficientes que apoyen a pequeños emprendimientos de manufactura artesanal en el control de sus costos de producción, contribuyendo a su sostenibilidad en el mercado.

---

## 👨‍💻 Proyecto

**Sistema Automatizado de Costos de Producción para Emprendimientos**

**Caso de estudio:** Michi Jabones

**Área:** Ingeniería de Sistemas
