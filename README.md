# Portfolio

[![CI](https://github.com/NicoLucian/My-Portfolio/actions/workflows/ci.yml/badge.svg)](https://github.com/NicoLucian/My-Portfolio/actions/workflows/ci.yml)

Repositorio central para presentar el progreso y los proyectos del portfolio.

## Estado del proyecto

- **Fase:** inicial
- **Contenido publicado:** documentación principal y configuración de integración continua
- **Estado:** activo y en preparación para incorporar nuevos proyectos

Este repositorio no contiene actualmente una aplicación web ni módulos de código ejecutables. No se presentan métricas ni resultados de desempeño que todavía no hayan sido verificados.

## Stack

- **Markdown:** documentación del portfolio
- **GitHub Actions:** validación automática del repositorio
- **GitHub:** alojamiento, control de versiones y visualización de proyectos

## Demostración local

No se requieren credenciales ni dependencias para consultar el contenido actual.

```bash
git clone https://github.com/NicoLucian/My-Portfolio.git
cd My-Portfolio
```

Abre `README.md` con cualquier editor de Markdown. Desde Windows también puedes ejecutar `start README.md` para abrirlo en la aplicación asociada.

## Resultados verificables

- El flujo de CI se ejecuta en cada `push` y `pull_request`.
- La validación comprueba que `README.md` exista y no esté vacío.
- La configuración usa permisos de lectura únicamente (`contents: read`) y tiene un límite de cinco minutos.

No se publican capturas, enlaces de demostración ni estadísticas hasta que exista una implementación verificable.

## Arquitectura

La estructura actual se mantiene deliberadamente simple:

```text
My-Portfolio/
├── README.md
├── .gitignore
└── .github/
    └── workflows/
        └── ci.yml
```

- [`README.md`](README.md) describe el proyecto y mantiene el índice principal.
- [`.gitignore`](.gitignore) evita incluir archivos locales, temporales y generados.
- [`.github/workflows/ci.yml`](.github/workflows/ci.yml) contiene la comprobación automática existente.

Cada proyecto futuro puede vivir en su propio repositorio y enlazarse desde esta base sin mezclar su código con el portfolio principal.

## Repositorios

- [My-Portfolio](https://github.com/NicoLucian/My-Portfolio): repositorio principal del portfolio.

A medida que existan proyectos publicados y verificables, se añadirán aquí mediante enlaces internos o enlaces a sus repositorios.

## Próximos pasos

- Documentar el primer proyecto demostrable y enlazar a su repositorio.
- Incorporar una breve descripción, tecnologías usadas y instrucciones reproducibles para cada proyecto.
- Añadir capturas, demos o datos de resultados solo cuando estén disponibles.
- Mantener la validación de CI al incorporar nuevos archivos y ampliarla únicamente según las necesidades comprobadas.
