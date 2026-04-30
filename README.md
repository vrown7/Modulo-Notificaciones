# Proyecto Semestral: 777

**Integrantes:** Nicolas Ortega, Jairo Cid, Anita Olivares

**Estado del Sistema (Hito 1)**

| Microservicio | Puerto | DB Name | Funcionalidad |
| :--- | :--- | :--- | :--- |
| Módulo de Registro | 8082 | universidad_backend | CRUD de usuarios |
| Módulo de Catálogo | 8081 | universidad_backend | CRUD de Productos (Prendas) |
| Módulo de Carrito | 8084 | universidad_backend | CRUD de ItemCarrito |
| Módulo de Favoritos | 8080 | universidad_backend | CRUD de Favoritos |
| Módulo de Notificaciones | 8085 | universidad_backend | CRUD de Notificaciones |
| Módulo de Descuentos | 8086 | universidad_backend | CRUD de Descuentos |
| Módulo de Ventas | 8087 | universidad_backend | CRUD de Ventas |

**Despliegue Técnico**

* **Instancia:** AWS EC2 t3.large (Ubuntu 24.04)
* **Comando de inicio:** `docker compose up -d`
