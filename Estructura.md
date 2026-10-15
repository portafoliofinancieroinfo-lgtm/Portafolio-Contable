# Estructura del repositorio

```
📁 portafolio/
 ┣ 📄 README.md                         → hoja de vida
 ┣ 📄 HV_Brian_David_Calero_Torres.pdf  → hoja de vida en PDF
 ┣ 📄 Estructura.md                     → este archivo
 ┗ 📁 detalles/                         → detalle de cada proyecto + herramienta propia
     ┣ 📄 README.md                     → índice de proyectos
     ┣ 📄 requirements.txt              → dependencias compartidas (pandas, matplotlib, numpy)
     ┣ 📁 electrovichada-2023/          → Electrovichada.md + auditor_reteica.py + evidencia/
     ┣ 📁 transervi-2022/               → Transervi.md + conciliador.py + evidencia/
     ┣ 📁 fervicom-2024/                → FERVICOM.md + auditor_checklist.py + evidencia/
     ┗ 📁 inlogistic-2025/              → INLOGISTIC.md + organizador.py + evidencia/
```

Cada carpeta dentro de `detalles/` contiene el estudio de caso real (sin datos confidenciales), el script que
automatiza —sobre datos sintéticos— el tipo de control que hice manualmente en esa empresa, y una carpeta
`evidencia/` con el gráfico de resultados.
