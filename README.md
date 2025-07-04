# 📚 Calculadora de Distributivo Docente

Esta es una aplicación web interactiva que permite visualizar, editar y exportar el **distributivo anual de horas de los docentes**, a partir de un archivo CSV. Está pensada para facilitar el análisis y control de la carga horaria docente, incluyendo docencia, investigación, gestión y vinculación, con validaciones automáticas y exportaciones en PDF o CSV.

---

## 🧠 ¿Por qué este stack tecnológico?

Se eligió un enfoque **ligero, directo y totalmente en el navegador**, basado en **HTML, JavaScript Vanilla y librerías vía CDN** por las siguientes razones:

- **📦 Sin necesidad de instalación**: La aplicación no requiere instalar dependencias ni usar entornos como Node.js, Python o frameworks complejos.
- **⚡ Carga instantánea**: Al no depender de servidores ni compiladores, puede ejecutarse directamente desde un archivo `.html`.
- **💅 Estilos modernos con Tailwind CSS**: Permite un diseño limpio y responsivo sin escribir CSS desde cero.
- **📄 Manejo de CSV eficiente con PapaParse**: Se usa para cargar y procesar archivos CSV fácilmente desde JavaScript.
- **🖨️ Exportación PDF con html2pdf.js**: Convierte dinámicamente secciones de la página en archivos PDF descargables.
- **🎨 Íconos atractivos con FontAwesome**: Mejora la experiencia visual sin esfuerzo adicional.

Este stack fue elegido para facilitar el uso inmediato de la aplicación por cualquier usuario, sin necesidad de configuración técnica.

### ⚠️ ¿Por qué no es recomendable para producción?

Aunque es perfecto para pruebas locales o entregas académicas, **no se recomienda este stack para entornos de producción profesional**, por las siguientes razones:

- ❌ **Escalabilidad reducida**: No es adecuado para manejar múltiples usuarios, base de datos en tiempo real o integración con servicios externos.
- ❌ **Dependencia de CDN externos**: Si alguna librería enlazada por CDN deja de estar disponible, la aplicación dejará de funcionar.

---

## ▶️ Instrucciones para ejecutar la aplicación

1. Descarga o clona el repositorio que contiene los archivos del proyecto.
2. **Abre el archivo `index.html` en tu navegador** (doble clic o arrastrándolo al navegador).
3. La aplicación se cargará automáticamente y obtendrá los datos desde un archivo CSV en línea o embebido.

> **No necesitas instalar nada adicional.** Toda la lógica y el estilo están incluidos o enlazados por CDN.

---

## ✅ Funcionalidades principales

- Cargar base de datos de docentes desde un CSV público o local.
- Visualizar y editar las horas asignadas en las 4 áreas principales:
  - Docencia
  - Investigación
  - Gestión
  - Vinculación
- Cálculo automático de:
  - Horas adicionales por planificación, tutorías y AOD.
  - Porcentaje de docencia.
  - Total de horas anuales.
- Validación visual:
  - ✅ Si el total anual es exactamente **1920 horas**.
  - ✅ Si el porcentaje de docencia es **mayor o igual al 60%**.
- Exportación:
  - 🖨️ PDF individual del resumen del docente seleccionado.
  - 📤 CSV general con el resumen de todos los docentes.

---

## 📌 Requisitos

- Conexión a internet para cargar las librerías desde CDN y el archivo CSV.

---

## 👤 Autor

Desarrollado por **Jorge Zambrano**
