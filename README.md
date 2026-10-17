# CreativeSystem

CreativeSystem is a local-first creative software ecosystem for digital art, photography, vector design, resources, notes and workflow automation.

The applications are designed to work independently while sharing resources and capabilities through Existence.

## Applications

| Application | Role | Status |
|---|---|---|
| [Existence](https://github.com/Sonaed/Existence) | Ecosystem hub, modules, scripting and shared resources | 26.1.0 |
| [Nebula](https://github.com/Sonaed/Nebula) | Raster painting, compositing and large layered documents | 26.4.0 |
| [Nova](https://github.com/Sonaed/Nova) | RAW development and non-destructive photo adjustments | 26.1.0 |
| [Atlas](https://github.com/Sonaed/Atlas) | Vector illustration, typography and SVG/PDF export | 26.1.0 |
| [StarDust](https://github.com/Sonaed/StarDust) | Resource and script creation studio | 26.1.0 development |
| [Cosmos](https://github.com/Sonaed/Cosmos) | Connected notes, projects and knowledge graphs | 26.0 |
| Ephemeris | Layout and publishing workspace | In development |
| Pulsar | Motion Design, Video Editing and 2DVFX | In development |

## Workflow

```text
                 Existence
              /      |       \
       StarDust   Resources   Scripts
          |          |           |
       Nebula     Nova        Atlas
          \          |          /
                 CreativeSystem
```

Typical workflows include:

- developing a photograph in Nova, then painting or compositing it in Nebula;
- creating vector assets in Atlas and sharing them through Existence;
- building brushes, presets and scripts in StarDust;
- managing project notes and references in Cosmos.

## Design principles

- Local-first operation.
- Non-destructive editing where practical.
- Shared resources are versioned and validated through Existence.
- Plugins and user extensions belong to Existence, not individual creative applications.
- Large documents use tiled storage, caching and controlled memory budgets.
- Each application remains useful on its own.

## Project status

CreativeSystem is under active development. Releases and qualification reports are published in the individual repositories. The ecosystem is currently focused on production workflows, interoperability, memory stability and long-session reliability.
They will be no Official port for windows or MacOS, I focus on bringing tools for Linux user only (Windows and MacOs can already use Adobe)
Looking for someone to help me test/Install through github (since I have everything locally I don't know if there's bug concerning git installation)
Someone to teach me Pyhton is also welcome ! 

## License

See the license and contribution information in each application repository.
