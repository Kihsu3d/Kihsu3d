# Kihsu3D — Cómo añadir productos

## Método: Subir a GitHub

### 1. Sube las imágenes

1. Ve a **github.com/Kihsu3d/Kihsu3d**
2. Navega a la carpeta `images/`
3. Sube tus fotos (JPG, PNG, WEBP — máximo 5MB)

### 2. Crea el producto

En la carpeta `content/[categoria]/`, crea un archivo `.md`:

**Ejemplo:** `content/anime/naruto.md`

```markdown
---
name: "Naruto Sage Mode"
price: "25"
image: "https://raw.githubusercontent.com/Kihsu3d/Kihsu3d/main/images/anime/naruto.jpg"
---
```

### 3. Categorías disponibles

| Categoría | Ruta |
|---|---|
| Anime | `content/anime/` |
| Kpop | `content/kpop/` |
| Películas | `content/peliculas/` |
| Música | `content/musica/` |
| Series | `content/series/` |
| Videojuegos | `content/videojuegos/` |
| Llaveros | `content/llaveros/` |
| Figuras | `content/figuras/` |
| Láminas Personalizadas | `content/laminaspersonal/` |

---

## Subir imagen → obtener URL

1. Sube la foto a GitHub en la carpeta `images/[categoria]/`
2. Una vez subida, copia la URL raw:
   - La imagen estará en: `https://raw.githubusercontent.com/Kihsu3d/Kihsu3d/main/images/anime/mi-foto.jpg`

---

## Estructura del repositorio

```
Kihsu3d/
├── index.html
├── content/
│   ├── anime/
│   │   ├── producto1.md
│   │   └── producto2.md
│   ├── kpop/
│   ├── peliculas/
│   ├── musica/
│   ├── series/
│   ├── videojuegos/
│   ├── llaveros/
│   ├── figuras/
│   └── laminaspersonal/
└── images/
    ├── anime/
    ├── kpop/
    └── ...
```

---

## Ejemplo completo

**Imagen:** `images/anime/tanjiro.jpg`

**Archivo:** `content/anime/tanjiro.md`

```markdown
---
name: "Tanjiro Kamado"
price: "25"
image: "https://raw.githubusercontent.com/Kihsu3d/Kihsu3d/main/images/anime/tanjiro.jpg"
---
```

La imagen aparece en la web automáticamente en 1-2 minutos tras hacer Commit.
