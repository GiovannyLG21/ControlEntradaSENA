# 🚧 Control Entrada SENA

**Control Entrada SENA** es un **sistema de control de acceso y registro de ingreso** para la institución SENA, diseñado para gestionar de manera organizada y segura la entrada y salida de personas, vehículos y dispositivos dentro del centro de formación. La plataforma permite registrar usuarios, administrar roles, asociar dispositivos de acceso y llevar un historial de ingresos y salidas en tiempo real.

---

## ✨ Características

- Diseño responsive y adaptable.

- Registro y administración de usuarios

- Control de ingreso y salida de personal y visitantes

- Gestión de vehículos asociados a los accesos

- Administración de dispositivos y tipos de equipos

- Módulos de acceso diferenciados por zona o proceso

- Registro histórico de entradas y salidas

- Reportes para seguimiento y control interno

- API para integración con otros sistemas o dispositivos

---

## 🛠️ Tecnologías

| Tecnología | Uso |
|---|---|
| [Python](https://www.python.org/) | Lenguaje principal del proyecto |
| [Django](https://www.djangoproject.com/) | Framework backend para la lógica de negocio, autenticación y administración de la aplicación |
| [Django REST Framework](https://www.django-rest-framework.org/) | Desarrollo de APIs para integración con otros sistemas o dispositivos |
| [MySQL](https://www.mysql.com/) | Sistema de gestión de bases de datos utilizado para persistencia de información |
| [SQLite](https://sqlite.org/) | Base de datos ligera para desarrollo local y pruebas |
| [Bootstrap 5](https://getbootstrap.com/) | Framework frontend para interfaces responsivas y modernas |
| [OpenPyXL](https://openpyxl.readthedocs.io/) | Exportación e importación de reportes en formato Excel |
| [Pillow](https://pillow.readthedocs.io/) | Manejo de imágenes y archivos multimedia |
| [PyMySQL](https://pymysql.readthedocs.io/) | Conector de Python para la conexión con MySQL |

---

## 📸 Vista previa

![Control Entrada SENA Preview](./public/preview.png)

---

## 🚀 Instalación

### 1. Clonar el repositorio

```bash
git clone https://github.com/GiovannyLG21/ControlEntradaSENA.git
cd ControlEntradaSENA
```

### 2. Instalar dependencias

```bash
python -m pip install -r requirements.txt
```

### 3. Iniciar el servidor de desarrollo

```bash
python manage.py runserver
```

El proyecto estará disponible en:

```bash
http://127.0.0.1:8000
```

## Migraciones de la base de datos

```bash
python manage.py makemigrations administrator
python manage.py migrate
```

## 📁 Estructura del proyecto

```bash
ControlEntradaSENA/
├── administrator/   # App admin
├── api/   # Endpoints de la API
├── ControlEntradaSENA/   # Configuración del proyecto
├── images/   # Imágenes subidas por el usuario
├── mainapp/   #F unciones principales
├── modules/   # App principal
├── static/   # Archivos estaticos
├── manage.py  # Archivo de gestión del proyecto
└── requirements.txt  # Dependencias del proyecto
```

## 👨‍💻 Autor

Giovanny Ladino

- GitHub: https://github.com/GiovannyLG21

## 📄 Licencia

Este proyecto está publicado bajo la licencia MIT.