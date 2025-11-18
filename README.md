# 🧠 Neuro EEG Lab

> Repositorio oficial del equipo de investigación en señales EEG. Aquí documentamos experimentos, análisis, modelos y resultados para construir el pipeline completo del laboratorio.

- 💡 **Foco:** investigación EEG computacional, de la señal cruda a la interpretación de modelos avanzados.
- 🤝 **Colaboración:** múltiples laboratorios temáticos y miembros rotando según intereses.
- 🌍 **Open source:** todo el progreso se comparte públicamente bajo licencia MIT.

---

## 🗂️ Distribución del repositorio

| Dominio | Propósito | Carpeta |
| --- | --- | --- |
| ⚙️ Preproc | Limpieza, filtrado y control de calidad | `preproc/`
| 🧬 Neuro | Análisis neurofisiológico, features y biomarcadores | `neuro/`
| 🧠 Models | Modelado ML/DL, benchmarking y experimentos | `models/`
| 🔍 Interp | Interpretabilidad, visualización y comunicación científica | `interp/`
| 📖 Docs | Documentación, protocolos y referencias | `docs/`

Cada dominio contiene:

- `<nombre de laboratorio>/`: Laboratorio enfocado en un área específica.
- `docs/`: acuerdos internos, protocolos y referencias.
- `notebooks/`: exploración rápida y reportes replicables.
- `scripts/`: módulos reutilizables (procesamiento, training, utils...).
- `tests/`: validaciones automáticas por laboratorio.
- `README.md`: objetivos, KPIs y enlaces relevantes.

> 📍 Tip: en VS Code, usa la búsqueda global (`Ctrl+Shift+F`) con el nombre del laboratorio para saltar entre laboratorios afines.

---

## 🎯 Objetivo general

Construir un pipeline EEG de punta a punta — desde adquisición y preprocesamiento hasta interpretabilidad avanzada con IA — fomentando el aprendizaje colectivo y la experimentación responsable.

- 🧱 **Pilares:** orden, trazabilidad y compartición.
- 🧪 **Mantra:** "Mejor una iteración imperfecta hoy que una perfecta nunca".

---

## 🔬 Líneas de investigación activas

1. **Preprocesamiento y Calidad de Datos** (`preproc/`)
2. **Análisis Neurofisiológico y Señal** (`neuro/`)
3. **Modelado con IA / ML / DL** (`models/`)
4. **Interpretabilidad y Comunicación Científica** (`interp/`)

Cada línea se subdivide en laboratorios independientes para facilitar la escalabilidad del equipo y la autonomía de los miembros.

---

## 🧭 Flujo de trabajo básico (Git)

1. **Actualizar tu fork/branch**
  ```bash
  git pull
  ```
2. **Trabajar dentro de tu laboratorio**
  - Mantén los cambios contenidos en la carpeta asignada.
  - Documenta supuestos y resultados en el `README.md` correspondiente.
3. **Guardar avances frecuentes**
  ```bash
  git add .
  git commit -m "descripcion del avance"
  git push
  ```
4. **Cambios mayores**
  - Crea una nueva branch descriptiva (`feature/preproc-denoise`).
  - Abre un Pull Request.
  - Espera feedback del coordinador del laboratorio o Giovanny.

> 💡 Consejo: referencia issues o experimentos usando `#ID` en tus commits para mantener trazabilidad.

---

## 📚 Guías y documentación

Toda la documentación transversal vive en `documentacion_general/`:

- `roadmap.md`: hitos trimestrales y prioridades.
- `reuniones.md`: minutas, acuerdos y próximos pasos.
- `guidelines.md`: convenciones de código, nombrado de archivos y estilo de notebooks.

---

## 🧭 Principios del laboratorio

- 🔍 Curiosidad antes que perfección.
- 🪜 Avanzar paso a paso (pero avanzar siempre).
- 🧠 Aprender haciendo; documentar el aprendizaje.
- 📣 Compartir hallazgos, incluso los negativos.
- 🧼 Mantener el orden para que cualquiera pueda retomar tu trabajo.
- 🤖 Usar IA como herramienta de apoyo, nunca como sustituto del entendimiento.

---

## 🧭 Filosofía del laboratorio

Consulta nuestra visión y principios en:
[docs/filosofia.md](docs/filosofia.md)

---

## 📄 Licencia

Este proyecto se distribuye bajo la licencia **MIT**. Revisa el archivo [`LICENSE`](LICENSE) para más detalles.

> ¿Tienes dudas, ideas o quieres proponer una nueva línea de investigación? Abre un issue o contáctanos en el canal interno del equipo.