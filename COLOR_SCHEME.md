# PolaRiS Color Scheme

Color palette for use in accompanying paper figures and visualizations.

## Primary Accent Colors

### Honey Bronze (Primary Accent)
- **Hex:** `#d4940a`
- **RGB:** `rgb(212, 148, 10)`
- **Usage:** Primary brand color, highlights, key metrics
- **Paper use:** Main data series, primary emphasis, correlation lines

### Hyper Magenta
- **Hex:** `#9333ea`
- **RGB:** `rgb(147, 51, 234)`
- **Usage:** Secondary accent, gradients
- **Paper use:** Secondary data series, alternative emphasis

### Neon Violet
- **Hex:** `#a855f7`
- **RGB:** `rgb(168, 85, 247)`
- **Usage:** Gradient transitions, tertiary accent
- **Paper use:** Tertiary data series, gradient fills

### Cool Horizon
- **Hex:** `#3b82f6`
- **RGB:** `rgb(59, 130, 246)`
- **Usage:** Cool accent, gradients
- **Paper use:** Cool-toned data series, background accents

### Blue Energy
- **Hex:** `#2563eb`
- **RGB:** `rgb(37, 99, 235)`
- **Usage:** Deep blue accent, gradients
- **Paper use:** Deep blue data series, strong emphasis

## Background Colors

### Background Deep
- **Hex:** `#fafafa`
- **RGB:** `rgb(250, 250, 250)`
- **Usage:** Page background
- **Paper use:** Figure backgrounds, light backgrounds

### Background Surface
- **Hex:** `#ffffff`
- **RGB:** `rgb(255, 255, 255)`
- **Usage:** Card backgrounds, elevated surfaces
- **Paper use:** White backgrounds, plot backgrounds

### Background Elevated
- **Hex:** `#f5f5f5`
- **RGB:** `rgb(245, 245, 245)`
- **Usage:** Subtle elevation, card backgrounds
- **Paper use:** Subtle background differentiation

## Text Colors

### Text Primary
- **Hex:** `#1a1a1a`
- **RGB:** `rgb(26, 26, 26)`
- **Usage:** Main text, headings
- **Paper use:** Axis labels, titles, main text

### Text Secondary
- **Hex:** `#4a4a4a`
- **RGB:** `rgb(74, 74, 74)`
- **Usage:** Secondary text, descriptions
- **Paper use:** Secondary labels, captions

### Text Muted
- **Hex:** `#7a7a7a`
- **RGB:** `rgb(122, 122, 122)`
- **Usage:** Tertiary text, hints
- **Paper use:** Grid lines, minor labels

## Border Colors

### Border Subtle
- **Hex:** `rgba(0, 0, 0, 0.06)`
- **RGB:** `rgba(0, 0, 0, 0.06)`
- **Usage:** Subtle borders, dividers
- **Paper use:** Subtle grid lines, light borders

### Border Light
- **Hex:** `rgba(0, 0, 0, 0.1)`
- **RGB:** `rgba(0, 0, 0, 0.1)`
- **Usage:** Light borders, dividers
- **Paper use:** Grid lines, plot borders

## Recommended Color Combinations for Paper Figures

### For Line Plots / Time Series
- **Primary series:** Honey Bronze `#d4940a`
- **Secondary series:** Hyper Magenta `#9333ea`
- **Tertiary series:** Cool Horizon `#3b82f6`
- **Baseline/Reference:** Text Muted `#7a7a7a`

### For Bar Charts
- **PolaRiS results:** Honey Bronze `#d4940a`
- **Baseline/Comparison:** Hyper Magenta `#9333ea`
- **Alternative method:** Cool Horizon `#3b82f6`

### For Scatter Plots
- **PolaRiS points:** Honey Bronze `#d4940a` (with transparency)
- **Baseline points:** Hyper Magenta `#9333ea` (with transparency)
- **Correlation line:** Honey Bronze `#d4940a` (dashed)

### For Heatmaps / Correlation Matrices
- **High values:** Honey Bronze `#d4940a`
- **Medium values:** Neon Violet `#a855f7`
- **Low values:** Cool Horizon `#3b82f6`
- **Neutral:** Background Elevated `#f5f5f5`

## LaTeX/Matplotlib Color Definitions

### For LaTeX (xcolor package)
```latex
\definecolor{honeybronze}{RGB}{212,148,10}
\definecolor{hypermagenta}{RGB}{147,51,234}
\definecolor{neonviolet}{RGB}{168,85,247}
\definecolor{coolhorizon}{RGB}{59,130,246}
\definecolor{blueenergy}{RGB}{37,99,235}
```

### For Python/Matplotlib
```python
COLORS = {
    'honey_bronze': '#d4940a',
    'hyper_magenta': '#9333ea',
    'neon_violet': '#a855f7',
    'cool_horizon': '#3b82f6',
    'blue_energy': '#2563eb',
    'text_primary': '#1a1a1a',
    'text_secondary': '#4a4a4a',
    'text_muted': '#7a7a7a',
}
```

### For R/ggplot2
```r
polaris_colors <- list(
  honey_bronze = "#d4940a",
  hyper_magenta = "#9333ea",
  neon_violet = "#a855f7",
  cool_horizon = "#3b82f6",
  blue_energy = "#2563eb"
)
```

## Accessibility Notes

- **Honey Bronze** and **Hyper Magenta** have sufficient contrast for text on white backgrounds
- For colorblind-friendly palettes, consider using **Honey Bronze** with **Cool Horizon** or **Blue Energy** instead of magenta/violet combinations
- All colors meet WCAG AA standards for contrast when used appropriately

