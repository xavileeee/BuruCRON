# BuruCRON 🕒

**BuruCRON** es una herramienta web de cronometraje diseñada específicamente para el entorno educativo del **IES Sáenz de Buruaga**. Proporciona una interfaz visual clara y funcional para gestionar el tiempo en el aula, con modos de reloj, cuenta atrás y cronómetro.

## ✨ Características Principales

-   **Modo Reloj**: Visualización de la hora actual en formato digital (24h).
-   **Cuenta Atrás (Temporizador)**:
    -   Ajustes rápidos de tiempo (1m, 2m, 5m, 10m, 15m, 30m).
    -   Configuración manual de minutos (hasta 600 minutos).
    -   Alerta sonora automática al finalizar el tiempo.
-   **Cronómetro**: Seguimiento preciso del tiempo transcurrido.
-   **Interfaz Moderna y Adaptable**:
    -   Diseño inspirado en pantallas LCD de siete segmentos.
    -   **Temas**: Soporte para Modo Oscuro (por defecto) y Modo Claro.
    -   **Pantalla Completa**: Ideal para proyecciones en el aula.
    -   **Tamaño Ajustable**: Control dinámico del tamaño de los dígitos para mejorar la legibilidad.
-   **Accesibilidad**: Atajos de teclado (Barra espaciadora para iniciar/pausar).

## 🚀 Tecnologías

Este proyecto está desarrollado como una **Google Apps Script Web App** utilizando:
-   **HTML5 / CSS3**: Estructura y diseño premium con variables CSS para temas.
-   **JavaScript (Vanilla)**: Lógica del cronómetro y gestión de AudioContext para los pitidos.
-   **Fuentes Especializadas**: Uso de la fuente *Seven Segment* para una estética retro-digital.

## 🛠️ Desarrollo Local con CLASP

Si deseas modificar o desplegar este proyecto, te recomendamos usar [clasp](https://github.com/google/clasp).

### 1. Requisitos previos
-   Node.js instalado.
-   Instalar clasp de forma global: `npm install -g @google/clasp`
-   Tener habilitada la API de Google Apps Script en tu cuenta de Google.

### 2. Clonar el proyecto
Si ya tienes el ID del script, puedes descargarlo usando:
```bash
clasp clone "TU_SCRIPT_ID"
```

### 3. Sincronización
-   **Bajar cambios**: `clasp pull`
-   **Subir cambios**: `clasp push`

## 📖 Instrucciones de Uso

1.  **Cambiar de Modo**: Utiliza los botones de la barra lateral (**RELOJ**, **CUENTA ATRÁS**, **CRONÓMETRO**).
2.  **Iniciar/Pausar**: Haz clic en el botón principal de la barra lateral o presiona la **barra espaciadora**.
3.  **Configurar Cuenta Atrás**: Introduce el tiempo en "Minutos Manuales" o usa los botones rápidos. Asegúrate de tener la "Alerta Sonora" activada si deseas escuchar el aviso final.
4.  **Ajustar Pantalla**: Usa los botones **+** y **-** para cambiar el tamaño del reloj. Haz clic en el icono de pantalla completa (⛶) para una visualización sin distracciones.

---
*Desarrollado para el IES Sáenz de Buruaga.*
