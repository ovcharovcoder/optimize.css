# Optimize.css

A minimal, modern CSS reset for stable and predictable UI development.

---

## 📌 Info

| | |
|---|---|
| **Author** | Andrii Ovcharov |
| **Email** | [ovcharovcoder@gmail.com](mailto:ovcharovcoder@gmail.com) |
| **Version** | 3.0 |
| **Build date** | 27.04.2026 |
| **License** | [MIT](LICENSE) |

---

## About

Optimize.css is a lightweight CSS reset that provides a clean, stable baseline for modern web development.

It removes inconsistent browser defaults without introducing opinionated design decisions — so you can build UI systems from a predictable foundation, without fighting hidden side effects that aggressive resets typically cause.

---

## Key Principles

| Principle | Description |
|---|---|
| **Minimalism** | Only essential resets, no unnecessary overrides |
| **Stability** | No rules that break layouts or native behavior |
| **Neutral baseline** | No interference with your design decisions |
| **Accessibility-first** | Proper focus styles and motion preferences |
| **Predictability** | Consistent behavior across modern browsers |

---

## What It Does

- Normalizes `box-sizing` and removes default spacing
- Improves text rendering for body and headings
- Makes media elements (`img`, `video`, `picture`, `svg`) responsive
- Ensures form elements inherit fonts correctly
- Provides accessible `:focus-visible` styles
- Respects `prefers-reduced-motion` for animations and scroll

---

## Why Not reset.css or normalize.css?

| Feature | reset.css | normalize.css | **Optimize.css** |
|---|---|---|---|
| Modern focus styles | ❌ | ❌ | ✅ |
| `prefers-reduced-motion` | ❌ | ❌ | ✅ |
| `button:disabled` cursor | ❌ | ❌ | ✅ |
| `::selection` styling | ❌ | ❌ | ✅ |
| `:target` scroll margin | ❌ | ❌ | ✅ |
| No legacy hacks | ❌ | ⚠️ | ✅ |
| Lightweight | ✅ | ❌ | ✅ |

---

## Who Is It For?

- **Front-end developers** who want control without fighting browser defaults
- **UI engineers** building scalable design systems
- **Teams** that need a consistent baseline across projects

---

## How to Use

**1. Download the file:**

- [optimize.css](https://raw.githubusercontent.com/datoshcode/optimize.css/main/optimize.css) — full version
- [optimize_min.css](https://raw.githubusercontent.com/datoshcode/optimize.css/main/optimize_min.css) — minified version

**2. Add to your HTML:**

```html
<link rel="stylesheet" href="optimize.css">
```

or if using the minified version:

```html
<link rel="stylesheet" href="optimize_min.css">
```

> ⚠️ Connect **before** your main stylesheet so resets apply first.

---

## Author

<img src="https://raw.githubusercontent.com/ovcharovcoder/neo-serene-theme/main/images/avatar.png" alt="Andrii Ovcharov" width="60">

**Andrii Ovcharov**
[ovcharovcoder@gmail.com](mailto:ovcharovcoder@gmail.com)

---

[MIT License](LICENSE)


