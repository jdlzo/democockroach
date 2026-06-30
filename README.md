#  Laboratorio CockroachDB

Práctica de implementación y pruebas de un clúster distribuido utilizando **CockroachDB** con **Docker Compose**.

## Estructura del proyecto

```
labcrock/
│
├── Imagenes/
│   └── (Capturas utilizadas durante la práctica)
│
├── Comandos de la practica.md
│   └── Guía paso a paso con todos los comandos utilizados.
│
└── docker-compose.yml
    └── Configuración del clúster de CockroachDB.
```

---

# Contenido

El repositorio contiene los siguientes archivos:

| Archivo | Descripción |
|----------|-------------|
| **Comandos de la practica.md** | Documento con todos los comandos necesarios para realizar la práctica desde cero. |
| **docker-compose.yml** | Archivo de Docker Compose utilizado para crear el clúster de CockroachDB de tres nodos. |
| **Imagenes/** | Carpeta con capturas de pantalla del desarrollo y resultados obtenidos durante la práctica. |

---

#  Requisitos

Antes de comenzar asegúrate de tener instalado:

- Docker Desktop
- Docker Compose

Puedes verificar la instalación ejecutando:

```bash
docker --version
docker compose version
```

---

#  Cómo utilizar este repositorio

1. Clonar el repositorio.

```bash
git clone https://github.com/jdlzo/democockroach.git
```

2. Entrar a la carpeta del proyecto.

```bash
cd labcrock
```

3. Seguir paso a paso las instrucciones del archivo:

```
Comandos de la practica.md
```

Allí se encuentran todos los comandos necesarios para:

- Descargar CockroachDB.
- Crear el clúster.
- Inicializar la base de datos.
- Crear tablas.
- Insertar datos.
- Ejecutar transacciones.
- Simular la caída de un nodo.
- Verificar la tolerancia a fallos.
- Finalizar la práctica.

---

#  Interfaz Web

Una vez iniciado el clúster podrás acceder al panel de administración desde:

```
http://localhost:8080
```

Desde allí podrás visualizar:

- Estado de los nodos.
- Rangos.
- Replicación.
- Salud del clúster.

---

#  Objetivo

Esta práctica tiene como finalidad comprender el funcionamiento de una base de datos distribuida utilizando CockroachDB, analizando aspectos como:

- Replicación de datos.
- Alta disponibilidad.
- Tolerancia a fallos.
- Transacciones distribuidas.
- Consistencia de la información.

---

# Autor

Repositorio desarrollado por **Avila Andy - Bailon Mikaela - Indio Heidi - Laz Jordan** como parte de una práctica académica sobre bases de datos distribuidas utilizando CockroachDB y Docker.
