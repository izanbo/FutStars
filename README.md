# ⚽ FutStars

**Plataforma de estadísticas, análisis y predicciones de fútbol.**

FutStars es un proyecto de fin de ciclo de **2.º de Desarrollo de Aplicaciones Multiplataforma (DAM)**. Su objetivo es desarrollar una plataforma que permita consultar estadísticas de fútbol, analizar el rendimiento de equipos y jugadores, y ofrecer predicciones de partidos mediante técnicas de inteligencia artificial.

El proyecto contempla una aplicación web y una aplicación móvil Android, conectadas a un backend común y una base de datos compartida.

## 🎯 Objetivos

- Consultar estadísticas de equipos, jugadores y partidos.
- Analizar el rendimiento de equipos y futbolistas.
- Ofrecer predicciones de partidos mediante inteligencia artificial.
- Desarrollar una interfaz web y una aplicación Android.
- Centralizar los datos mediante una API REST.
- Diseñar una arquitectura modular y mantenible.

## 🛠️ Tecnologías

| Componente | Tecnologías previstas |
|---|---|
| Web | Astro, React, TypeScript, HTML y CSS |
| Aplicación Android | Android Studio, Java y XML |
| Backend | Java y Spring Boot |
| API | REST |
| Base de datos | PostgreSQL, Spring Data JPA e Hibernate |
| Servicio de inteligencia artificial | Python, scikit-learn y FastAPI |
| Control de versiones | Git y GitHub |

*Las tecnologías y funcionalidades podrán ajustarse durante el desarrollo.*

## 📁 Estructura del proyecto

```text
FutStars/
├── backend/       # API REST y lógica del servidor
├── web/           # Aplicación web
├── android/       # Aplicación móvil Android
├── ai-service/    # Servicio de predicciones con IA
├── database/      # Recursos y scripts de base de datos
├── docs/          # Documentación del proyecto
└── README.md      # Información general del proyecto
```

## 🚧 Estado del desarrollo

**Fase inicial: configuración del proyecto.**

Actualmente se ha preparado la estructura inicial del repositorio y se ha configurado el backend con Spring Boot y la conexión a PostgreSQL.

Funcionalidades implementadas hasta el momento:

- [x] Creación del repositorio y estructura inicial.
- [x] Configuración inicial del backend con Spring Boot.
- [x] Conexión con la base de datos PostgreSQL.
- [x] Creación del primer endpoint REST: `GET /api/hello`.
- [ ] Diseño del modelo de datos.
- [ ] Desarrollo de las primeras entidades y operaciones CRUD.
- [ ] Desarrollo de la aplicación web.
- [ ] Desarrollo de la aplicación Android.
- [ ] Integración del servicio de inteligencia artificial.

## ▶️ Ejecución del backend

### Requisitos previos

- Java compatible con la versión configurada en el proyecto.
- Maven o Maven Wrapper, si está incluido.
- PostgreSQL instalado y en ejecución.

### Configuración

1. Crear una base de datos llamada `futstars_db` en PostgreSQL.
2. Configurar las credenciales de acceso mediante variables de entorno.
3. Revisar el archivo `backend/src/main/resources/application.properties`.

La contraseña de la base de datos debe mantenerse fuera del repositorio.

### Variable de entorno en Windows PowerShell

```powershell
$env:DB_PASSWORD = "TU_CONTRASEÑA"
```

Sustituye el valor por tu contraseña local de PostgreSQL. Ejecuta este comando en el terminal desde el que vayas a iniciar el backend.

### Endpoint de prueba

Con el backend en ejecución en el puerto `8080`, accede a:

```text
http://localhost:8080/api/hello
```

Respuesta esperada:

```text
¡Bienvenido a FutStars!
```

## 👥 Equipo

Proyecto desarrollado en equipo por tres estudiantes de 2.º de DAM.

## 📌 Notas

- FutStars se encuentra en fase de desarrollo.
- Las funcionalidades y la arquitectura podrán evolucionar durante el proyecto.
- Las estadísticas y los datos de fútbol dependerán de las fuentes de datos que se integren.
- Las predicciones generadas por inteligencia artificial serán estimaciones y no garantías de resultados.

## 📄 Licencia

Pendiente de definir.