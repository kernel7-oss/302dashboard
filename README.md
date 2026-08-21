# Dashboard Estadístico Escuela Nº 302 (Ciclo 2026 - 1° Semestre)

Dashboard interactivo y analítica de datos escolares y carga horaria docente para la **Escuela Nº 302** (Modalidad Domiciliaria y Hospitalaria), correspondiente al **1° Semestre 2026 (23 de Febrero al 30 de Junio de 2026)**.

Procesado conforme al **Calendario Oficial Nacional de Feriados de la República Argentina** ([argentina.gob.ar/feriados](https://www.argentina.gob.ar/feriados)).

---

## 📊 Métricas Principales del Periodo

- **Días hábiles trabajados:** 85 días laborables.
- **Feriados / Puentes oficiales descontados:** 7 días.
- **Semanas lectivas procesadas:** 19 semanas (23/02 al 30/06).
- **Estudiantes únicos atendidos:** 13 alumnos.
- **Pico de matrícula semanal:** 10 alumnos en simultáneo.
- **Horas efectivas dictadas (netas):** 1.015,7 horas (96,8% cumplimiento sobre 1.049,0 hs programadas).
- **Total de clases / módulos registrados:** 901 clases.
- **Docentes activos:** 13 profesores.

---

## 🌐 Estructura del Repositorio

- `index.html` / `Dashboard_Secundaria_2026.html`: Aplicación web interactiva completa (HTML5, TailwindCSS, Chart.js, Lucide Icons).
- `dashboard_data/`:
  - `resumen_semanal.csv`: Estadísticas semanales de horas, alumnos y días laborables.
  - `clases_detalladas.csv`: 901 registros detallados con cálculo de horas programadas vs efectivas.
  - `estudiantes_semanales.csv`: Padrón y datos de estudiantes.
  - `feriados_oficiales_2026.csv`: Tabla de feriados oficiales nacionales.
  - `dashboard_data.json`: Dataset consolidado en JSON.

---

## 🚀 Visualización en Línea

Si se activa GitHub Pages desde la rama `main`, el dashboard estará disponible directamente en:
`https://kernel7-oss.github.io/302dashboard/`
