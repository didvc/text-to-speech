[English](README.md) · [日本語](README-ja.md) · [繁體中文](README-zh-TW.md) · [简体中文](README-zh.md) · [Deutsch](README-de.md) · [Français](README-fr.md) · Español · [Bahasa Indonesia](README-id.md)

# VoiceFlow - Aplicación avanzada de texto a voz

[![Live Demo](https://img.shields.io/badge/Live_Demo-blue?style=for-the-badge)](https://text-speech.pages.dev)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![GitHub issues](https://img.shields.io/github/issues/didvc/text-to-speech?style=for-the-badge)](https://github.com/didvc/text-to-speech/issues)
[![GitHub stars](https://img.shields.io/github/stars/didvc/text-to-speech?style=for-the-badge)](https://github.com/didvc/text-to-speech/stargazers)

Una aplicación web de texto a voz moderna y completa, hecha con React y TypeScript. VoiceFlow ofrece una interfaz intuitiva para convertir texto en una voz natural, con resaltado de palabras en tiempo real, ajustes de voz personalizables y gestión de contenidos.

## Capturas de pantalla

![Interfaz de la aplicación VoiceFlow](https://res.cloudinary.com/dxowqxqtj/image/upload/v1753415581/text-to-speech/voiceflow-main-screenshot.png)

*La interfaz intuitiva de VoiceFlow, con resaltado de palabras en tiempo real, controles de voz personalizables y gestión de contenidos.*

## Características

### Funciones principales
- Conversión de texto a voz: síntesis de alta calidad con la Web Speech API
- Resaltado de palabras en tiempo real: las palabras se resaltan con una animación durante la reproducción
- Controles de reproducción: reproducir, pausar y detener con controles ágiles
- Varias voces: elige entre las voces del sistema, con detección de idioma

### Personalización
- Velocidad ajustable: controla la reproducción de 0,5x a 2x
- Tono: ajusta con precisión el tono de la voz para escuchar mejor
- Volumen: ajusta el nivel de salida
- Selección de voz: elige entre las voces disponibles en el sistema

### Gestión de contenidos
- Biblioteca de textos: organiza varios documentos con títulos
- Añadir, editar y eliminar: gestión completa de los textos
- Cambio de contenido: pasa de un texto a otro sin interrupciones
- Almacenamiento persistente: el contenido se guarda localmente en el navegador

### Interfaz
- Tema oscuro moderno: una interfaz oscura elegante y agradable para la vista
- Diseño adaptable: funciona en ordenador, tableta y móvil
- Degradados: textos y elementos visuales con bonitos degradados
- Controles intuitivos: una interfaz sencilla con respuesta visual clara

## Primeros pasos

### Requisitos
- Node.js (versión 16 o superior)
- npm o yarn
- Un navegador moderno compatible con la Web Speech API

### Instalación

1. Clona el repositorio
   ```bash
   git clone https://github.com/didvc/text-to-speech.git
   cd text-to-speech
   ```

2. Instala las dependencias
   ```bash
   npm install
   # or
   yarn install
   ```

3. Inicia el servidor de desarrollo
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. Abre el navegador
   Ve a `http://localhost:5173` para ver la aplicación

### Compilación para producción

```bash
npm run build
# or
yarn build
```

Los archivos compilados quedan en el directorio `dist/`.

## Uso

### Uso básico
1. Elige o añade un texto: elige uno de los ejemplos incluidos o añade tu propio texto
2. Ajusta la configuración: voz, velocidad, tono y volumen a tu gusto
3. Reproduce: pulsa el botón de reproducción para empezar la conversión
4. Sigue la lectura: observa el resaltado de palabras en tiempo real mientras se lee el texto

### Funciones avanzadas
- Gestión de contenidos: organiza varios documentos en la biblioteca
- Cambio de voz: prueba distintas voces e idiomas
- Control de velocidad: ajusta el ritmo de lectura para comprender mejor o por accesibilidad
- Móvil: todas las funciones están disponibles en dispositivos móviles

## Tecnologías

- Framework de frontend: React 18
- Lenguaje: TypeScript
- Herramienta de build: Vite
- Estilos: Tailwind CSS
- Iconos: Lucide React
- API de voz: Web Speech API (SpeechSynthesis)

## Compatibilidad con navegadores

VoiceFlow funciona en navegadores modernos compatibles con la Web Speech API:

- Chrome/Chromium (recomendado)
- Edge
- Safari
- Firefox (selección de voces limitada)
- Navegadores móviles (iOS Safari, Chrome Mobile)

## Diseño adaptable

VoiceFlow está pensado para funcionar sin problemas en todo tipo de dispositivos:
- Ordenador: todas las funciones con un diseño optimizado
- Tableta: interfaz táctil con controles adaptables
- Móvil: diseño compacto con las funciones esenciales a mano

## Contribuir

¡Las contribuciones de la comunidad son bienvenidas! Consulta la [guía de contribución](CONTRIBUTING.md) para saber cómo empezar.

### Inicio rápido para colaboradores
1. Haz un fork del repositorio
2. Crea una rama (`git checkout -b feature/amazing-feature`)
3. Haz tus cambios
4. Haz commit de tus cambios (`git commit -m 'Add amazing feature'`)
5. Sube la rama (`git push origin feature/amazing-feature`)
6. Abre un pull request

## Licencia

Este proyecto tiene licencia MIT; consulta el archivo [LICENSE](LICENSE) para más detalles.

## Problemas y soporte

- Informes de errores: [crear un issue](https://github.com/didvc/text-to-speech/issues/new?template=bug_report.yml)
- Solicitudes de funciones: [solicitar una función](https://github.com/didvc/text-to-speech/issues/new?template=feature_request.yml)
- Debates: [únete a la conversación](https://github.com/didvc/text-to-speech/discussions)

## Agradecimientos

- A la Web Speech API, por la funcionalidad de texto a voz
- A las comunidades de React y TypeScript, por sus excelentes herramientas
- A Tailwind CSS, por su bonito sistema de estilos
- A Lucide React, por sus iconos limpios y modernos

## Aspectos del proyecto

- Tamaño del build: optimizado para cargar rápido
- Dependencias: mínimas y elegidas con cuidado
- Rendimiento: animaciones fluidas a 60 fps e interacciones ágiles
- Accesibilidad: cumple WCAG y admite navegación con teclado

---

<div align="center">

[Prueba VoiceFlow en vivo](https://text-speech.pages.dev) | [Documentación](https://github.com/didvc/text-to-speech/wiki) | [Debates](https://github.com/didvc/text-to-speech/discussions)

Hecho por [didvc](https://github.com/didvc)

</div>