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
- La validación comprueba que `README.md` exista y no esté vacío y aplica lint a los documentos Markdown.
- La configuración usa permisos de lectura únicamente (`contents: read`) y tiene un límite de cinco minutos.

No se publican capturas, enlaces de demostración ni estadísticas hasta que exista una implementación verificable.

## Arquitectura

La estructura actual se mantiene deliberadamente simple:

```text
My-Portfolio/
├── README.md
├── .gitignore
├── .markdownlint-cli2.jsonc
├── pilotos/
│   ├── README.md
│   ├── plantilla-ficha-piloto.md
│   └── matriz-madurez.md
└── .github/
    └── workflows/
        └── ci.yml
```

- [`README.md`](README.md) describe el proyecto y mantiene el índice principal.
- [`.gitignore`](.gitignore) evita incluir archivos locales, temporales y generados.
- [`.markdownlint-cli2.jsonc`](.markdownlint-cli2.jsonc) configura la validación local y automática de Markdown.
- [`.github/workflows/ci.yml`](.github/workflows/ci.yml) contiene la comprobación automática existente.

Cada proyecto futuro puede vivir en su propio repositorio y enlazarse desde esta base sin mezclar su código con el portfolio principal.

## Repositorios

- [My-Portfolio](https://github.com/NicoLucian/My-Portfolio): repositorio principal del portfolio.

La lista anterior se limita a repositorios públicos existentes que pueden verificarse en GitHub. No se enlazan repositorios privados ni proyectos sin evidencia pública.

## Presentación de pilotos

La carpeta [`pilotos/`](pilotos/) contiene una estructura reutilizable para presentar experimentos sin atribuirles resultados aún no verificables.

- [`Criterios de éxito`](pilotos/README.md): reglas para definir, medir y decidir la continuación de un piloto.
- [`Ficha de piloto`](pilotos/plantilla-ficha-piloto.md): plantilla neutral para alcance, riesgos, evidencia y decisión.
- [`Matriz de madurez`](pilotos/matriz-madurez.md): marco por dimensiones que debe completarse con información comprobada.
- [`Repositorio My-Portfolio`](https://github.com/NicoLucian/My-Portfolio): enlace al repositorio existente que aloja esta presentación.

Las plantillas usan campos como “pendiente” o “por validar” hasta que exista evidencia; no incluyen métricas predeterminadas, cifras de ejemplo ni afirmaciones de rendimiento.

## Próximos pasos

- Completar la ficha del primer piloto demostrable únicamente después de acordar alcance y evidencia.
- Enlazar repositorios adicionales solo cuando sean públicos, existentes y puedan verificarse.
- Incorporar una breve descripción, tecnologías usadas y instrucciones reproducibles para cada proyecto.
- Añadir capturas, demos o datos de resultados solo cuando estén disponibles.
- Mantener la validación de CI al incorporar nuevos archivos y ampliarla únicamente según las necesidades comprobadas.
