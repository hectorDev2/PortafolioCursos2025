

# Portafolio de Cursos – Proyecto Semestral 2025-1

Sistema de gestión de portafolios de cursos para la Escuela Profesional de Ingeniería Informática y de Sistemas.

---

## Descripción

Este proyecto consiste en el desarrollo de una plataforma web para la gestión de portafolios de cursos, orientada a docentes, administradores y evaluadores. Cada portafolio incluye sílabos, materiales de enseñanza (diapositivas, guías, prácticas, lecturas, etc.), ejemplos de asignaciones y exámenes, así como muestras de trabajos estudiantiles categorizados de “excelente” a “pobre”. El sistema permite la subida y organización de archivos (límite de 5 MB por documento), cuenta con un visor integrado para previsualización sin descarga y gestiona permisos diferenciados por roles[^1].

---

## Tecnologías

- **Frontend:** Next.js
- **Backend:** NestJS
- **ORM:** Prisma
- **Base de datos:** MySQL / PostgreSQL
- **Gestión de proyecto:** Azure DevOps
- **Almacenamiento:** Nube (por definir)

---

## Roles de Usuario

- **Administrador:** Crea y administra portafolios por semestre, fusiona archivos del mismo rubro para descarga.
- **Docente:** Sube y organiza el material del portafolio de cursos.
- **Evaluador:** Revisa y proporciona retroalimentación a los docentes[^1].

---

## Características

- Subida y gestión de archivos (máx. 5 MB).
- Organización de documentos por rubro y semestre.
- Visor de documentos integrado.
- Permisos y acceso diferenciados por rol.
- Fusión y descarga de archivos por rubro.
- Retroalimentación y evaluación de materiales docentes.
- Seguridad, escalabilidad y facilidad de uso.
- Integración con almacenamiento en la nube[^1].

---

## Instalación

1. **Clonar el repositorio**

```bash
git clone https://github.com/tu-usuario/portafolio-cursos.git
cd portafolio-cursos
```

2. **Instalar dependencias**

```bash
npm install
```

3. **Configurar variables de entorno**
    - Copia `.env.example` a `.env` y completa los valores requeridos.
4. **Configurar la base de datos**
    - Actualiza la cadena de conexión en `.env`.
    - Ejecuta migraciones:

```bash
npx prisma migrate dev
```

5. **Ejecutar el backend**

```bash
cd apps/backend
npm run start:dev
```

6. **Ejecutar el frontend**

```bash
cd apps/frontend
npm run dev
```


---

## Metodología de Trabajo

- **SCRUM**: Organización en sprints y entregas incrementales.
- **Product Owner:** Define y prioriza funcionalidades. --> DOCENTE A CARGO
- **Scrum Master:** Facilita el proceso y elimina impedimentos. --> HECTOR PAOLO BARAZORDA CUELLAR
- **Development Team:** Diseña, desarrolla y prueba el sistema[^1].

---

## Entregables

- Product Backlog con historias de usuario.
- Prototipo de interfaces (wireframes/mockups).
- Modelo de base de datos inicial.
- Documento de arquitectura.
- Documentación de sprints y retrospectivas.
- Reportes de progreso en Azure DevOps[^1].

---

## Licencia

Proyecto académico para la asignatura de Metodologías de Desarrollo de Software, 2025-1.

---

> Desarrollado por estudiantes de la Escuela Profesional de Ingeniería Informática y de Sistemas. Docentes responsables: Waldo Elio Ibarra Zambrano.

---

[^1] proyecto-de-desarrollo.pdf

<div style="text-align: center">⁂</div>

[^1]: proyecto-de-desarrollo.pdf

