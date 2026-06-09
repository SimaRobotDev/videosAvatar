# videosAvatar

Repositorio centralizado de videos de avatars utilizados en los distintos proyectos de SimaRobot.

## Estructura

```
videosAvatar/
├── MentorIA/
│   ├── lenguaje-basico/       # Avatar MentorIA - Lenguaje básica
│   ├── lenguaje-secundaria/   # Avatar MentorIA - Lenguaje secundaria
│   ├── matematica-basica/     # Avatar MentorIA - Matemática básica
│   └── matematica-secundaria/ # Avatar MentorIA - Matemática secundaria
├── Hub-Providencia/           # Avatar Hub Providencia
├── Colina/                    # Avatar Colina
├── Onstar/                    # Avatar Onstar
├── SimaCare-Hombre/           # Avatar SimaCare masculino
├── SimaCare-Mujer/            # Avatar SimaCare femenino
└── Demo/                      # Videos de demostración
```

## Uso

1. Coloca los videos en la carpeta correspondiente al proyecto/avatar.
2. Usa nombres descriptivos para los archivos (ej. `saludo-inicial.mp4`, `idle-loop.mp4`).
3. Los archivos de video se gestionan con **Git LFS** por su tamaño.

### Formatos soportados

- `.mp4`, `.mov`, `.webm`, `.avi`, `.mkv`

## Git LFS

Este repositorio usa Git LFS para archivos de video. Antes de subir videos, instala Git LFS:

```bash
git lfs install
git lfs pull
```

## Convenciones

- Una carpeta por proyecto/avatar.
- No mezclar videos de distintos proyectos en la misma carpeta.
- Mantener solo la versión activa de cada video; versiones anteriores pueden archivarse en una subcarpeta `_archivo/` si es necesario.
