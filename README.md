# ¿Qué es Git y Git Flow?

## Git
Git es un sistema de control de versiones distribuido. Esto significa que ayuda a los desarrolladores a gestionar y realizar un seguimiento de los cambios en el código fuente de un proyecto, permitiendo trabajar en equipo de forma eficiente.

### Características principales:
- **Control de versiones**: Guarda un historial completo de los cambios en el código.
- **Trabajo en equipo**: Permite que varias personas trabajen en el mismo proyecto al mismo tiempo.
- **Ramas (branches)**: Facilita la creación de versiones paralelas del proyecto para trabajar en nuevas características sin afectar el código principal.

## Git Flow
Git Flow es una estrategia o metodología para trabajar con Git que organiza el uso de las ramas de forma estructurada. Se utiliza especialmente en proyectos que tienen ciclos de desarrollo bien definidos (como versiones o lanzamientos).

### Las ramas principales:
1. **Main (o master)**: Contiene el código listo para producción.
2. **Develop**: Es la rama de desarrollo donde se integran las nuevas características antes de pasarlas a producción.

### Ramas adicionales:
- **Feature**: Para desarrollar nuevas funcionalidades.
- **Release**: Para preparar una nueva versión del proyecto.
- **Hotfix**: Para corregir errores críticos en producción.

### Flujo de trabajo básico:
1. Crear una rama **feature** desde `develop`.
2. Trabajar en la nueva característica y, al terminar, fusionarla con `develop`.
3. Cuando el código esté listo para producción, crear una rama **release** desde `develop` y luego fusionarla con `main`.
4. Si hay un error crítico, crear una rama **hotfix** desde `main`, solucionarlo y fusionarla con `main` y `develop`.

### Beneficios:
- Organización clara del proyecto.
- Facilita la colaboración entre desarrolladores.
- Reduce conflictos al integrar cambios.

---

Git y Git Flow juntos hacen que el trabajo en equipo sea más eficiente y organizado, ayudando a gestionar proyectos de software de cualquier tamaño.
