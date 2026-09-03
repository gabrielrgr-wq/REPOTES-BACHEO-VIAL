# Informes de Bacheo UE1 – Canelones (2026)

Este repositorio contiene la estructura modular para la publicación periódica y mensual de los informes de bacheo y obras viales de la **Unidad Operativa 1 (UE1)** en Canelones, Uruguay.

## 📂 Estructura del Repositorio

```text
.
├── index.html                           # Portal principal de informes
├── README.md                            # Documentación y guía de aportes
└── informes/
    └── 2026_Enero-Agosto/
        ├── index.html                   # Reporte interactivo del periodo
        └── img/                         # Recursos gráficos del periodo
            ├── tendencia_mensual.png
            ├── distribucion_localidad.png
            └── top10_calles.png
```

## 📊 Histórico de Informes

| Periodo | M² Reparados | Cobertura | Estado | Enlace al Reporte |
| :--- | :---: | :--- | :---: | :---: |
| **Enero - Agosto 2026** | **10.219 m²** | Las Piedras (91%), La Paz (9%) | `Completado` | [Ver Informe](informes/2026_Enero-Agosto/index.html) |

## 🚀 Cómo agregar un nuevo mes al repositorio

1. Crear una carpeta dentro de `informes/` con el patrón `YYYY_Mes` (ej. `informes/2026_Septiembre/`).
2. Colocar el archivo HTML renombrado a `index.html` y sus imágenes dentro de la subcarpeta `img/`.
3. Agregar el enlace al nuevo mes en el menú de `index.html` (raíz) y actualizar la tabla de este `README.md`.
4. Ejecutar `git add .`, `git commit -m "docs: agregar informe Septiembre 2026"` y `git push`.
