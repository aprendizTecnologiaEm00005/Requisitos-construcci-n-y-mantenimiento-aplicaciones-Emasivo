# 🚀 Proyecto Web – Documentación Técnica


## 🧱 Stack de Desarrollo


| Componente     | Tecnología |
|---------------|-----------|
| Backend       | Mínimo: Flask WSGI Framework <br> Esperado: FastAPI Web Framework |
| Frontend      | Mínimo: Flask HTML Templates / FastAPI Templates <br> Opcional: Vue |
| Base de Datos | SQL Server 2019 (Mandatorio) |
| Web Server    | NGINX (Mandatorio) |


---


## 🏗️ Arquitectura


Se debe construir como mínimo una aplicación **monolítica**, con posibilidad de escalar a arquitecturas más complejas.


### 🔧 Directrices


| Componente                     | Directriz |
|------------------------------|----------|
| Patrón de diseño             | MVC (documentado en el código) |
| Gestión de datos             | Diagrama de base de datos (Mandatorio) |
| Generación de base de datos  | Script SQL (Mandatorio) |
| Migraciones                  | Esperado |


---


## 🔐 Seguridad de la Información – Gobierno de Datos


### 🔑 Autenticación


- Implementar inicio de sesión mediante usuario y contraseña  
- Longitud mínima: 10 caracteres  
- Composición: alfanumérica  
- Implementar mecanismo de recuperación de credenciales  
- Implementar mecanismo de cambio de contraseña  


---


### 🛡️ Control de Acceso


- Implementar roles y permisos  
- Entregar matriz de segregación de funciones  


---


## 🏢 Administración y Soporte


- La administración de usuarios debe entregarse como un proceso documentado al área de tecnología  
- La gestión de usuarios será realizada por mesa de ayuda y control de identidades  
- El soporte en ambiente productivo debe realizarse por mesa de ayuda  
- Se debe transferir conocimiento al equipo TIC  
- Los nuevos desarrollos deben gestionarse mediante proceso de cambio  


---


## 🎨 UI / UX


- Interfaz amigable e intuitiva  
- Diseño responsivo (desktop, laptop, tablet, etc.)  
- Flujo de usuario claro  
- Paginación del lado del servidor para mejorar rendimiento  


---


## 🔄 Control de Versiones y Repositorio


- Uso de Git para control de versiones  
- Repositorio en GitHub  


---


## ⚙️ Ejecución del Proyecto




python app.py
