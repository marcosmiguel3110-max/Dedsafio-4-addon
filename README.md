# Dedsafio 4 Addon

Repositorio que contiene los addons y recursos de Minecraft Bedrock Edition para el **Dedsafio 4**.

## Contenido

| Archivo | Tamaño | Descripción |
|---|---|---|
| `Dedsafio_4_addon.mcaddon` | ~46.6 MB | Paquete principal del addon (comportamiento + recursos). |
| `asset.mcaddon` | ~99.7 MB | Recursos adicionales del addon. |
| `sounds.zip` | ~36.4 MB | Resource pack con sonidos (`.ogg`) y texturas GUI (`.png` + `.mcmeta`). |

## Instalación

### Addons (`.mcaddon`)

1. Descarga los archivos `.mcaddon` desde este repositorio.
2. Haz doble clic sobre cada archivo (o ábrelo con Minecraft) para que se importe automáticamente.
3. Entra a un mundo existente o crea uno nuevo y activa el addon desde la sección de **Comportamiento / Recursos**.

### Resource pack (`sounds.zip`)

1. Descarga `sounds.zip`.
2. Renómbralo a `sounds.mcpack` (cambiar la extensión de `.zip` a `.mcpack`).
3. Haz doble clic sobre el archivo para que Minecraft lo importe como resource pack.
4. Activa el resource pack en tu mundo desde **Configuración → Recursos globales** o desde el menú de resource packs del mundo.

> Alternativamente, extrae el `.zip` y copia la carpeta a `com.mojang/development_resource_packs/` (Windows) o la ruta equivalente en Android/iOS.

## Notas

- Compatible con Minecraft Bedrock Edition.
- Se recomienda instalar en este orden: `Dedsafio_4_addon.mcaddon` → `asset.mcaddon` → `sounds.zip` (como `.mcpack`).
- `asset.mcaddon` supera el tamaño recomendado por GitHub (50 MB) pero está dentro del límite permitido (100 MB).
