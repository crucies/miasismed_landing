# 🧠 Manual de Reconstrucción (Prompt Kai) - miasismed_landing

## 📋 Resumen del Proyecto
**miasismed_landing** es una Landing Page estratégica diseñada para el análisis de neuromarketing del producto "VitaMemo". No es solo una página informativa, sino un dashboard interactivo para equipos de producto y marketing.

## 🛠️ Stack Tecnológico
- **Core:** HTML5 Semántico.
- **Estilos:** Tailwind CSS (via CDN).
- **Lógica/Interactividad:** Vanilla JavaScript.
- **Gráficos:** Chart.js (Radar y Doughnut charts).
- **Tipografía:** Inter (Google Fonts).

## 🏗️ Estructura de Secciones
1. **Hero:** Propuesta de valor basada en la reparación de la autonomía.
2. **Perfiles Psicológicos:** Gráfico de radar interactivo para comparar cargas emocionales.
3. **Miedos vs Deseos:** Análisis de motivadores profundos de compra.
4. **Voz del Cliente:** Grid filtrable de testimonios cualitativos.
5. **Barreras y Triggers:** Mapeo de objeciones vs disparadores de conversión.

## 🌍 Soporte Multi-idioma (i18n)
- **Sistema:** Motor ligero en JavaScript puro usando un objeto `i18n` centralizado.
- **Implementación:** 
    - Atributos `data-i18n` para elementos de texto estáticos.
    - Función `updateContent(lang)` para refrescar el DOM y reinicializar gráficos con datos traducidos.
    - Persistencia en `localStorage` con la clave `preferredLang`.
- **Selector:** Botón toggle en el Navbar (ES/EN).

## 🎨 Guía de Estilo
- **Paleta:** Calm Harmony (Slate/Neutrals con acentos Indigo/Blue).
- **Enfoque:** Profesional, médico, confiable pero moderno.
