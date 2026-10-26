# Normas de trabajo con Git y GitHub

## 1. Ramas

- `main`: tendrá solo las versiones estables del proyecto.
- `dev`: se utilizará para integrar y probar los cambios del equipo.
- `feature/nombre-tarea`: para desarrollar nuevas funcionalidades.
- `fix/nombre-error`: para corregir errores.
- `docs/nombre-tarea`: para realizar cambios en la documentación.

No se trabajará directamente sobre `main`.

## 2. Commits

- Los mensajes deben ser breves y describir claramente el cambio.
- Cada commit debe representar un cambio concreto.
- Se utilizarán prefijos para identificar el tipo de cambio.

Ejemplos:
- `feat: añadir gestión de grupos`
- `fix: corregir validación de usuarios`
- `docs: actualizar requisitos`
- `refactor: reorganizar servicios`

## 3. Pull requests

- Los cambios de las ramas de trabajo se incorporarán a `dev` mediante pull requests.
- Antes de fusionar una pull request, se comprobará que el código funciona y que no introduce errores evidentes.
- Siempre que sea posible, otro integrante revisará los cambios.
- La incorporación de cambios de `dev` a `main` se realizará cuando la versión esté comprobada.

## 4. Buenas prácticas

- Actualizar la rama de trabajo con los últimos cambios antes de integrar código.
- Resolver los conflictos antes de fusionar las ramas.
- No subir contraseñas, tokens, claves privadas ni datos personales reales.
- Mantener actualizada la documentación cuando cambien aspectos relevantes del proyecto.
