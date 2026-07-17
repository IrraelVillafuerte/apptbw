# 🌍 Plataforma de Gestión y Monitoreo Ambiental OpenAQ

Este proyecto es una interfaz web (Dashboard) profesional desarrollada como un prototipo visual para el monitoreo ambiental y la gestión de datos de dispositivos IoT simulados.

## 📋 Descripción de la Actividad
El objetivo de la actividad es diseñar y maquetar la estructura de un panel de control moderno, limpio y responsivo enfocado en la visualización de la calidad del aire. La interfaz organiza la información de manera intuitiva para permitir una experiencia de usuario similar a la de un sistema en entornos de producción real.

## ⚖️ Cumplimiento Estricto de la Rúbrica
Para garantizar el cumplimiento absoluto de los lineamientos solicitados en la evaluación, el desarrollo de esta plataforma se rige bajo los siguientes pilares:
*   **0% Librerías JavaScript:** No se utiliza ningún motor, script externo ni manipulación dinámica por código.
*   **0% Frameworks:** El proyecto prescinde por completo de herramientas como Vue.js, React, Bootstrap o Tailwind CSS.
*   **Solo HTML y CSS Nativos:** Toda la distribución del contenido, la paleta de colores, la iconografía y los componentes visuales han sido codificados mediante estándares puros de desarrollo web.

## 🚀 Características de la Interfaz
*   **Distribución del Layout:** Estructura limpia que incluye una barra superior de navegación (`navbar`), un menú lateral izquierdo (`sidebar`) para las secciones del sistema, y un panel principal de visualización.
*   **Tarjetas de Métricas (KPIs):** Componentes con bordes redondeados y sombras que presentan de forma clara el total de dispositivos, promedios globales e indicadores de alerta.
*   **Mapa Real Incorporado:** Integración de cartografía real de Quito, Ecuador, mediante el uso nativo de una etiqueta `<iframe>` de OpenStreetMap, permitiendo desplazamiento y zoom interactivo sin requerir scripts JavaScript.
*   **Tabla de Monitoreo IoT:** Formateo estructurado de datos para simular el seguimiento a placas ESP32 de Wokwi equipadas con sensores climáticos (DHT22).
*   **Panel de Detalles y Gráficas CSS:** Sección derecha que desglosa especificaciones del punto seleccionado y muestra barras estadísticas estilizadas mediante CSS puro (propiedades de altura y color adaptadas).

## 🛠️ Tecnologías Utilizadas
*   **HTML5:** Uso de etiquetas semánticas para estructurar el esqueleto del Dashboard (`<header>`, `<aside>`, `<main>`, `<section>`, `<footer>`).
*   **CSS3:** Estilos avanzados implementando variables globales (`:root`), Flexbox para la distribución y alineación del diseño, y diseño de componentes desde cero.
*   **FontAwesome v6.4:** Kit de iconos en formato de fuente web para enriquecer los menús y botones del panel.