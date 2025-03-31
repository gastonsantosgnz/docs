# Guía de Admisiones

Este proyecto contiene la documentación de procesos de admisión, carreras, requisitos y guías de estudio para diferentes instituciones educativas en Baja California:

- UABC (Universidad Autónoma de Baja California)
- PFLC (Preparatoria Federal Lázaro Cárdenas)
- CETYS Universidad

## Estructura del Proyecto

El proyecto está organizado por instituciones, cada una con su propia sección:

```
/
├── uabc/                      # Información de UABC
│   ├── convocatorias.mdx      # Convocatorias y fechas
│   ├── carreras.mdx           # Catálogo de carreras
│   ├── proceso-admision.mdx   # Pasos del proceso de admisión
│   └── guia-estudio.mdx       # Guía para el examen de admisión
├── pflc/                      # Información de PFLC
│   ├── convocatorias.mdx      # Convocatorias y fechas
│   ├── capacitaciones.mdx     # Programas de capacitación
│   ├── proceso-admision.mdx   # Pasos del proceso de admisión
│   └── guia-estudio.mdx       # Guía para el examen de admisión
└── cetys/                     # Información de CETYS Universidad
    ├── convocatorias.mdx      # Convocatorias y fechas
    ├── carreras.mdx           # Catálogo de carreras
    ├── proceso-admision.mdx   # Pasos del proceso de admisión
    └── guia-estudio.mdx       # Guía para el examen de admisión
```

### Desarrollo

Este proyecto utiliza [Mintlify](https://www.npmjs.com/package/mintlify) para la documentación. Para visualizar los cambios localmente, sigue estos pasos:

1. Instala el CLI de Mintlify:
```
npm i -g mintlify
```

2. Ejecuta el servidor de desarrollo en la raíz del proyecto:
```
mintlify dev
```

### Publicación de Cambios

Los cambios se despliegan automáticamente al hacer push a la rama principal. Para más información sobre cómo contribuir al proyecto, consulta la documentación de Mintlify.
