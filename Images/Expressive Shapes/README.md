# Material 3 Expressive Shapes Catalog

A production-ready collection of **35 Material 3 Expressive Shapes** extracted with mathematical precision from Figma vector designs, available in both **SVG** and **Android Vector Drawable (XML)** formats.

All shapes have been normalized to `(0, 0)` origin with exact Bezier curve bounds, eliminating whitespace padding while preserving the designer's original geometry, curvature, and aspect ratios.

---

## 📁 Directory Structure

```
Expressive Shapes/
├── shapes.json              # 🤖 Machine-readable AI index & metadata catalog (MANDATORY AI LOOKUP)
├── README.md                # 📖 Visual gallery, documentation, and Jetpack Compose usage guide
├── SVG/                     # 🎨 35 Standard SVG vector files (Named with shape names)
│   ├── Circle.svg
│   ├── 4 Leaf Clover.svg
│   └── ... (35 files)
├── XML/                     # 📱 35 Android Vector Drawable XML files (Named with shape names)
│   ├── Circle.xml
│   ├── 4 Leaf Clover.xml
│   └── ... (35 files)
└── android_drawable/        # 🤖 AAPT-compliant drop-in drawables (snake_case, for res/drawable/)
    ├── shape_circle.xml
    ├── shape_4_leaf_clover.xml
    └── ... (35 files)
```

---

## 🤖 AI Quick-Lookup Instructions

When searching for a shape:
1. Query `shapes.json` by `name`, `category`, or `tags`.
2. Inspect `pathData` directly for programmatic canvas rendering or Compose `Path`.
3. Reference `files.svg` for web/vector use and `files.xml` for native Android.

---

## 🎨 Complete Shapes Index (35 Shapes)

| # | Name | Category | Dimensions (W x H) | SVG Path | XML Path | Android Resource | Description |
|---|------|----------|-------------------|----------|----------|------------------|-------------|
| 1 | **Circle** | Geometric / Basic | 320 × 320 | [`SVG/Circle.svg`](SVG/Circle.svg) | [`XML/Circle.xml`](XML/Circle.xml) | `@drawable/shape_circle` | Perfect smooth circular disc with continuous curvature |
| 2 | **4 Leaf Clover** | Organic / Floral | 296 × 296 | [`SVG/4 Leaf Clover.svg`](SVG/4%20Leaf%20Clover.svg) | [`XML/4 Leaf Clover.xml`](XML/4%20Leaf%20Clover.xml) | `@drawable/shape_4_leaf_clover` | Four rounded clover lobes connected with smooth inward arcs |
| 3 | **4 SIded Cookie** | Organic / Scalloped | 292 × 292 | [`SVG/4 SIded Cookie.svg`](SVG/4%20SIded%20Cookie.svg) | [`XML/4 SIded Cookie.xml`](XML/4%20SIded%20Cookie.xml) | `@drawable/shape_4_sided_cookie` | Four-lobed squircle biscuit with pinched corners and undulating edges |
| 4 | **6 SIded Cookie** | Organic / Scalloped | 296 × 316 | [`SVG/6 SIded Cookie.svg`](SVG/6%20SIded%20Cookie.svg) | [`XML/6 SIded Cookie.xml`](XML/6%20SIded%20Cookie.xml) | `@drawable/shape_6_sided_cookie` | Hexagonal undulating biscuit with six rounded scalloped bumps |
| 5 | **7 sided Cookie** | Organic / Scalloped | 320 × 316 | [`SVG/7 sided Cookie.svg`](SVG/7%20sided%20Cookie.svg) | [`XML/7 sided Cookie.xml`](XML/7%20sided%20Cookie.xml) | `@drawable/shape_7_sided_cookie` | Heptagonal cookie badge with seven rounded lobes and soft corners |
| 6 | **8 leaf Clover** | Organic / Floral | 320 × 320 | [`SVG/8 leaf Clover.svg`](SVG/8%20leaf%20Clover.svg) | [`XML/8 leaf Clover.xml`](XML/8%20leaf%20Clover.xml) | `@drawable/shape_8_leaf_clover` | Symmetrical eight-petal flower or eight-leaf clover badge |
| 7 | **9 Side Cookie** | Organic / Scalloped | 324 × 319.95 | [`SVG/9 Side Cookie.svg`](SVG/9%20Side%20Cookie.svg) | [`XML/9 Side Cookie.xml`](XML/9%20Side%20Cookie.xml) | `@drawable/shape_9_side_cookie` | Nine-lobed scalloped disc with gentle rhythmic waves |
| 8 | **12 side cookie** | Organic / Scalloped | 319.99 × 320 | [`SVG/12 side cookie.svg`](SVG/12%20side%20cookie.svg) | [`XML/12 side cookie.xml`](XML/12%20side%20cookie.xml) | `@drawable/shape_12_side_cookie` | Twelve-lobed circular badge with fine scalloped teeth like a medal or ribbon seal |
| 9 | **Arch** | Architectural / Geometric | 310 × 310 | [`SVG/Arch.svg`](SVG/Arch.svg) | [`XML/Arch.xml`](XML/Arch.xml) | `@drawable/shape_arch` | Rounded dome top with vertical parallel pillars and a flat bottom base |
| 10 | **Arrow** | Indicator / Directional | 320 × 290 | [`SVG/Arrow.svg`](SVG/Arrow.svg) | [`XML/Arrow.xml`](XML/Arrow.xml) | `@drawable/shape_arrow` | Curved triangular arrowhead badge with smooth rounded vertex and flared base |
| 11 | **Boom** | Celestial / Burst | 328 × 328 | [`SVG/Boom.svg`](SVG/Boom.svg) | [`XML/Boom.xml`](XML/Boom.xml) | `@drawable/shape_boom` | Dynamic multi-point comic explosion burst with sharp radiating rays |
| 12 | **Bun** | Organic / Soft | 302.24 × 312 | [`SVG/Bun.svg`](SVG/Bun.svg) | [`XML/Bun.xml`](XML/Bun.xml) | `@drawable/shape_bun` | Horizontal pill shape with a central waist pinch, resembling a peanut or bun |
| 13 | **Burst** | Celestial / Burst | 332 × 331.99 | [`SVG/Burst.svg`](SVG/Burst.svg) | [`XML/Burst.xml`](XML/Burst.xml) | `@drawable/shape_burst` | High-density multi-pointed star burst with radiating slender needles |
| 14 | **Diamond** | Geometric / Sharp | 268 × 320.01 | [`SVG/Diamond.svg`](SVG/Diamond.svg) | [`XML/Diamond.xml`](XML/Diamond.xml) | `@drawable/shape_diamond` | Rhombus diamond oriented vertically with softened rounded corners |
| 15 | **Fan** | Organic / Curved | 300 × 300 | [`SVG/Fan.svg`](SVG/Fan.svg) | [`XML/Fan.xml`](XML/Fan.xml) | `@drawable/shape_fan` | Quarter-circle quadrant / fan wedge with rounded corners |
| 16 | **Flower** | Organic / Floral | 320 × 320 | [`SVG/Flower.svg`](SVG/Flower.svg) | [`XML/Flower.xml`](XML/Flower.xml) | `@drawable/shape_flower` | Expressive sixteen-petal flower blossom with rounded petals radiating outward |
| 17 | **Gem** | Geometric / Faceted | 292 × 301.67 | [`SVG/Gem.svg`](SVG/Gem.svg) | [`XML/Gem.xml`](XML/Gem.xml) | `@drawable/shape_gem` | Faceted shield shape with a pointed base and curved crown |
| 18 | **Ghost-ish** | Playful / Character | 300 × 300 | [`SVG/Ghost-ish.svg`](SVG/Ghost-ish.svg) | [`XML/Ghost-ish.xml`](XML/Ghost-ish.xml) | `@drawable/shape_ghost_ish` | Rounded domed head with an inverted scalloped arch bottom, resembling a friendly ghost or bell |
| 19 | **Heart** | Iconic / Romantic | 320 × 286 | [`SVG/Heart.svg`](SVG/Heart.svg) | [`XML/Heart.xml`](XML/Heart.xml) | `@drawable/shape_heart` | Symmetrical heart with wide rounded lobes and sharp bottom point |
| 20 | **Hexagon** | Geometric / Polygon | 371.99 × 254 | [`SVG/Hexagon.svg`](SVG/Hexagon.svg) | [`XML/Hexagon.xml`](XML/Hexagon.xml) | `@drawable/shape_hexagon` | Wide horizontal hexagon with chamfered or rounded vertices |
| 21 | **Oval** | Geometric / Basic | 300 × 300 | [`SVG/Oval.svg`](SVG/Oval.svg) | [`XML/Oval.xml`](XML/Oval.xml) | `@drawable/shape_oval` | Rotated smooth diagonal ellipse / egg shape with soft curvature |
| 22 | **Pentagon** | Geometric / Polygon | 314.66 × 305.13 | [`SVG/Pentagon.svg`](SVG/Pentagon.svg) | [`XML/Pentagon.xml`](XML/Pentagon.xml) | `@drawable/shape_pentagon` | Five-sided pentagon with soft rounded vertices and a horizontal base |
| 23 | **Pill** | Geometric / Soft | 316 × 316 | [`SVG/Pill.svg`](SVG/Pill.svg) | [`XML/Pill.xml`](XML/Pill.xml) | `@drawable/shape_pill` | Rotated smooth diagonal stadium / capsule pill shape |
| 24 | **Pixel-Circle** | Retro / Pixel | 312 × 312 | [`SVG/Pixel-Circle.svg`](SVG/Pixel-Circle.svg) | [`XML/Pixel-Circle.xml`](XML/Pixel-Circle.xml) | `@drawable/shape_pixel_circle` | Pixel-art stepped circle constructed from discrete digital block steps |
| 25 | **Pixel - Triangle** | Retro / Pixel | 248 × 320 | [`SVG/Pixel - Triangle.svg`](SVG/Pixel%20-%20Triangle.svg) | [`XML/Pixel - Triangle.xml`](XML/Pixel%20-%20Triangle.xml) | `@drawable/shape_pixel_triangle` | Pixel-art right-angled stair step pyramid / stepped corner block |
| 26 | **Puffy** | Organic / Soft | 363 × 287 | [`SVG/Puffy.svg`](SVG/Puffy.svg) | [`XML/Puffy.xml`](XML/Puffy.xml) | `@drawable/shape_puffy` | Plump cloud-like horizontal pillow squircle with bulbous lobes |
| 27 | **Puffy Diamond** | Organic / Soft | 320.01 × 320 | [`SVG/Puffy Diamond.svg`](SVG/Puffy%20Diamond.svg) | [`XML/Puffy Diamond.xml`](XML/Puffy%20Diamond.xml) | `@drawable/shape_puffy_diamond` | Four-pointed star with deeply curved inward concave edges and bulbous tips |
| 28 | **Semicircle** | Geometric / Half | 320 × 200 | [`SVG/Semicircle.svg`](SVG/Semicircle.svg) | [`XML/Semicircle.xml`](XML/Semicircle.xml) | `@drawable/shape_semicircle` | Horizontal half-circle dome with flat base and rounded ends |
| 29 | **Slanted** | Geometric / Dynamic | 320 × 300 | [`SVG/Slanted.svg`](SVG/Slanted.svg) | [`XML/Slanted.xml`](XML/Slanted.xml) | `@drawable/shape_slanted` | Parallelogram squircle sheared diagonally with rounded corners |
| 30 | **Soft Boom** | Organic / Burst | 312.01 × 312 | [`SVG/Soft Boom.svg`](SVG/Soft%20Boom.svg) | [`XML/Soft Boom.xml`](XML/Soft%20Boom.xml) | `@drawable/shape_soft_boom` | Eight-lobed starburst with rounded bulbous petal tips and soft valleys |
| 31 | **Soft Burst** | Organic / Burst | 320 × 330 | [`SVG/Soft Burst.svg`](SVG/Soft%20Burst.svg) | [`XML/Soft Burst.xml`](XML/Soft%20Burst.xml) | `@drawable/shape_soft_burst` | Twelve-pointed star with rounded smooth undulating lobes like a festive sun |
| 32 | **Square** | Geometric / Basic | 320 × 320 | [`SVG/Square.svg`](SVG/Square.svg) | [`XML/Square.xml`](XML/Square.xml) | `@drawable/shape_square` | Material 3 Expressive squircle square with continuous curvature rounded corners |
| 33 | **Sunny** | Celestial / Nature | 320 × 320 | [`SVG/Sunny.svg`](SVG/Sunny.svg) | [`XML/Sunny.xml`](XML/Sunny.xml) | `@drawable/shape_sunny` | Eight-pointed radiating sun star with alternating rounded sunray spikes |
| 34 | **Triangle** | Geometric / Polygon | 315.99 × 286 | [`SVG/Triangle.svg`](SVG/Triangle.svg) | [`XML/Triangle.xml`](XML/Triangle.xml) | `@drawable/shape_triangle` | Equilateral triangle with smoothly rounded corners and stable horizontal base |
| 35 | **Very Sunny** | Celestial / Nature | 320.01 × 320 | [`SVG/Very Sunny.svg`](SVG/Very%20Sunny.svg) | [`XML/Very Sunny.xml`](XML/Very%20Sunny.xml) | `@drawable/shape_very_sunny` | Sixteen-pointed radiating sun badge with compact rounded sunray peaks |

---

## 🚀 Native Jetpack Compose Usage

### Method 1: Using Android Vector Drawable
```kotlin
import androidx.compose.foundation.Image
import androidx.compose.foundation.layout.size
import androidx.compose.material3.MaterialTheme
import androidx.compose.runtime.Composable
import androidx.compose.ui.Modifier
import androidx.compose.ui.graphics.ColorFilter
import androidx.compose.ui.res.painterResource
import androidx.compose.ui.unit.dp

@Composable
fun ExpressiveShapeIcon(
    modifier: Modifier = Modifier
) {
    Image(
        painter = painterResource(id = R.drawable.shape_sunny),
        contentDescription = "Expressive Sunny Shape",
        modifier = modifier.size(48.dp),
        colorFilter = ColorFilter.tint(MaterialTheme.colorScheme.primary)
    )
}
```

### Method 2: Dynamic Path Rendering with Canvas
```kotlin
import androidx.compose.foundation.Canvas
import androidx.compose.foundation.layout.size
import androidx.compose.material3.MaterialTheme
import androidx.compose.runtime.Composable
import androidx.compose.ui.Modifier
import androidx.compose.ui.graphics.asComposePath
import androidx.compose.ui.graphics.vector.PathParser
import androidx.compose.ui.unit.dp

@Composable
fun ExpressiveCanvasShape(
    pathData: String,
    modifier: Modifier = Modifier.size(64.dp)
) {
    val primaryColor = MaterialTheme.colorScheme.primary
    val path = remember(pathData) {
        PathParser().parsePathString(pathData).toPath()
    }

    Canvas(modifier = modifier) {
        drawPath(
            path = path,
            color = primaryColor
        )
    }
}
```

---

## 📐 Shape Categories & Tags

- **Basic Geometric:** `Circle`, `Square`, `Triangle`, `Hexagon`, `Pentagon`, `Diamond`, `Oval`, `Semicircle`
- **Organic & Floral:** `4 Leaf Clover`, `8 leaf Clover`, `Flower`, `Bun`, `Puffy`
- **Scalloped & Cookies:** `4 SIded Cookie`, `6 SIded Cookie`, `7 sided Cookie`, `9 Side Cookie`, `12 side cookie`
- **Celestial & Starbursts:** `Boom`, `Burst`, `Puffy Diamond`, `Soft Boom`, `Soft Burst`, `Sunny`, `Very Sunny`
- **Playful & Character:** `Ghost-ish`, `Heart`, `Gem`, `Fan`, `Arch`, `Arrow`, `Pill`, `Slanted`
- **Retro & Digital:** `Pixel-Circle`, `Pixel - Triangle`

---
*Generated automatically with 100% mathematical Bezier precision from Figma vector data.*
