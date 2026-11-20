# BuruCron — Reloj Digital, Cronómetro y Temporizador para Aulas y Exámenes

**IES Sáenz de Buruaga** · Aplicación web diseñada específicamente para su proyección en paneles digitales interactivos (PDI) y pantallas de aula durante pruebas escritas, exposiciones orales o control de tiempo lectivo.

---

## 📋 Resumen del Proyecto

| Parámetro | Detalle |
| :--- | :--- |
| **Repositorio GitHub** | [https://github.com/xavileeee/BuruCron](https://github.com/xavileeee/BuruCron) |
| **Acceso desde Homarr** | Módulo directo en BuruPanel (`http://panel.saenzdeburuaga`) |
| **Manual de Usuario en BuruWikiTIC** | [Libro BuruPanel > Capítulo BuruCRON](http://buruwiki.saenzdeburuaga/books/burupanel/chapter/burucron) |
| **Script ID** | `1uYdz8oA7T4pz0JNs0ZZAyGJYBR97OFYHrsSdKSWtWRpGMp0xlav3A6aE` |
| **Acceso Corporativo** | Exclusivo para personal del centro mediante cuenta institucional `@iessaenzdeburuaga.es` a través de [BuruPanel](http://panel.saenzdeburuaga) |
| **Tipografía** | Fuente digital *Seven-Segment* retroiluminada de gran visibilidad |
| **Generación de Sonido** | Sintetizador de audio nativo mediante Web Audio API (`AudioContext`) |

---

## 🎨 Identidad Visual y Unicidad de Iconos

Siguiendo el principio de **Unicidad de Iconos** del IES Sáenz de Buruaga:

- **Icono Oficial:** Isotipo Cronicle / Cronómetro digital estilizado (Walkxcode).
- **Ruta Local:** [burucron_logo.png](file:///d:/PROYECTOS/IES%20SAENZ%20DE%20BURUAGA/PROYECTOS/BuruCron/burucron_logo.png) · [burucron_logo.svg](file:///d:/PROYECTOS/IES%20SAENZ%20DE%20BURUAGA/PROYECTOS/BuruCron/burucron_logo.svg)
- **Repositorio Central de Identidad:** [burucron_logo_oficial.png](file:///d:/PROYECTOS/IES%20SAENZ%20DE%20BURUAGA/Identidad_Corporativa/logos/burucron_logo_oficial.png)

---

## ⏱️ Modos de Funcionamiento

1. **Reloj Digital en Vivo (`Clock`):**
   - Muestra la hora oficial sincronizada en formato `HH:MM:SS`.
   - Ideal como salvapantallas o fondo permanente en el aula durante la jornada.

2. **Temporizador de Cuenta Atrás (`Timer`):**
   - Configuración manual de horas, minutos y segundos o presets rápidos (15m, 30m, 50m examen).
   - Aviso visual cuando restan los últimos minutos (cambio cromático de advertencia).
   - Señal acústica de fin de tiempo generada directamente por el navegador con pitidos progresivos vía Web Audio API.

3. **Cronómetro Progresivo (`Stopwatch`):**
   - Medición precisa de tiempos de intervención en debates, presentaciones orales o ejercicios prácticos.
   - Controles de pausa, reanudación y reinicio.

---

## 🎨 Características de Visualización

- **Modo Pantalla Completa:** Botón directo para maximizar la ventana y ocultar distracciones del navegador.
- **Selector de Temas:**
  - **Dark Theme (por defecto):** Fondo negro carbón (`#121212`) con dígitos en azul cian neón (`#00d4ff`) de mínimo consumo y máxima visibilidad desde el fondo de la clase.
  - **Light Theme:** Fondo blanco con dígitos azules para proyectores con baja luminosidad.
- **Control de Escala:** Botones `+` / `-` para adaptar el tamaño de los números a la resolución de cualquier panel o proyector.

---

## 📂 Archivos del Proyecto

```text
PROYECTOS/BuruCron/
├── .clasp.json                # Configuración de Clasp y Script ID oficial
├── appsscript.json            # Manifiesto de la WebApp
├── burucron_logo.png          # Icono oficial PNG
├── burucron_logo.svg          # Icono oficial vectorial SVG
├── capturas/                  # Capturas de la interfaz real del aula
│   ├── captura_burucron_inicio.png
│   └── captura_burucron_ui_real.png
├── Código.js                  # Servidor Apps Script con doGet()
├── index.html                 # Interfaz visual, estilos 7 segmentos y lógica de reloj/temporizador
└── README.md                  # Documentación técnica del proyecto
```

---

## 💻 Gestión y Despliegue con Clasp

```powershell
# Acceder a la carpeta
cd "D:\PROYECTOS\IES SAENZ DE BURUAGA\PROYECTOS\BuruCron"

# Sincronizar desde Google Apps Script
clasp pull

# Desplegar cambios locales a la nube
clasp push
```
