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


<img width="1844" height="700" alt="image" src="https://github.com/user-attachments/assets/393bad06-ef49-4d6e-a3b9-10012775c852" />
<img width="1857" height="799" alt="image" src="https://github.com/user-attachments/assets/46b02c9d-aa91-4722-b291-98871fe1766b" />
<img width="1851" height="708" alt="image" src="https://github.com/user-attachments/assets/d9e33a95-4033-452d-bf3e-f34111af8595" />



## 🚀 Tecnologías

Este proyecto está desarrollado como una **Google Apps Script Web App** utilizando:
-   **HTML5 / CSS3**: Estructura y diseño premium con variables CSS para temas.
-   **JavaScript (Vanilla)**: Lógica del cronómetro y gestión de AudioContext para los pitidos.
-   **Fuentes Especializadas**: Uso de la fuente *Seven Segment* para una estética retro-digital.

## 🚀 Cómo probar la herramienta

Tienes dos formas de ejecutar este proyecto:

### 1. Ejecución rápida (Web / Codespaces)
Si solo quieres probar la interfaz o usar la herramienta sin instalar nada:
-   **Localmente**: Simplemente abre el archivo `index.html` en cualquier navegador moderno.
-   **GitHub Codespaces**: Haz clic en el botón verde **"Code"** > **"Codespaces"** > **"Create codespace"**. Una vez abierto, ejecuta en la terminal:
    ```bash
    npm start
    ```
    > [!IMPORTANT]
    > Al ejecutar `npm start` en Codespaces, asegúrate de ir a la pestaña **"Ports"** y cambiar el **"Port Visibility"** a **"Public"** para que la previsualización cargue correctamente todos los recursos.

### 2. Desarrollo con Google Apps Script (CLASP)
Utilizamos [clasp](https://github.com/google/clasp) **exclusivamente para subir el proyecto a Google Apps Script**. Esto es necesario si quieres desplegarlo como una Web App oficial vinculada a una hoja de cálculo o a los servicios de Google.

**Requisitos previos:**
-   Node.js instalado.
-   Instalar dependencias: `npm install`
-   Tener habilitada la API de Google Apps Script en tu cuenta de Google.

**Sincronización:**
-   **Login**: `npm run login`
-   **Subir cambios**: `npm run push`
-   **Bajar cambios**: `npm run pull`

## 📖 Instrucciones de Uso

1.  **Cambiar de Modo**: Utiliza los botones de la barra lateral (**RELOJ**, **CUENTA ATRÁS**, **CRONÓMETRO**).
2.  **Iniciar/Pausar**: Haz clic en el botón principal de la barra lateral o presiona la **barra espaciadora**.
3.  **Configurar Cuenta Atrás**: Introduce el tiempo en "Minutos Manuales" o usa los botones rápidos. Asegúrate de tener la "Alerta Sonora" activada si deseas escuchar el aviso final.
4.  **Ajustar Pantalla**: Usa los botones **+** y **-** para cambiar el tamaño del reloj. Haz clic en el icono de pantalla completa (⛶) para una visualización sin distracciones.

---
*Desarrollado para el IES Sáenz de Buruaga.*
