[← Volver al flujo general](../README.md)

# Flujo de Registro

```mermaid
flowchart TD
    A([Inicio]) --> B[/Completar formulario/]
    B --> C{¿Datos válidos?}
    C -- No --> D[Mostrar errores]
    D --> B
    C -- Sí --> E{¿Email ya existe?}
    E -- Sí --> F[Avisar al usuario]
    F --> B
    E -- No --> G[Crear cuenta]
    G --> H([Ir al Login])
```
