---
title: 'ああああ'
tocTitle: 'あああ'
description: 'あああ adiós a los errores visuales'
---

Los desarrolladores dedican el [21%](https://ieeexplore.ieee.org/document/895984) de su tiempo a corregir errores. Depurar la apariencia de la interfaz de usuario puede resultar especialmente frustrante. Las reproducciones requieren que inicie diferentes navegadores, coloque su aplicación en el estado correcto y avance penosamente por el DOM. Lo que está en juego también es mayor; los errores no detectados cuestan [5-10x](https://www.cs.umd.edu/projects/SoftEng/ESEG/papers/82.78.pdf) más tiempo para corregirlos en producción que en QA.

Es de sentido común que miles de equipos de frontend realicen pruebas visuales con Storybook. Storybook te ayuda a **construir** componentes y escribir **pruebas visuales**. La ejecución de pruebas a nivel de componente te permite identificar la causa raíz de un error. Tomar instantáneas te ayuda a detectar **regresiones** automáticamente. Eso significa que la gente puede enviar interfaces de usuario sin preocuparse por los errores polizones.

Esta guía te presentó los conceptos básicos de las pruebas visuales. Tom y yo esperamos que puedan aprovechar estos aprendizajes en sus propios proyectos. Únase a la lista de correo de Storybook para recibir notificaciones sobre más artículos y guías útiles como este.

<iframe style="height:400px;width:100%;max-width:800px;margin:0px auto;" src="https://upscri.be/d42fc0?as_embed"></iframe>

## Código de muestra para este tutorial

Si lo ha estado siguiendo, su repositorio y Storybook implementado deberían verse así:

- 📕 [**Repositorio de GitHub**](https://github.com/chromaui/learnstorybook-visual-testing-code)
- 🌎 [**Storybook desplegado**](https://6070d9288779ab00214a9831-oymqxvbejc.chromatic.com/?path=/story/commentlist--paginated)

## Más recursos

¿Quieres sumergirte más profundo? A continuación, se incluyen algunos recursos útiles adicionales:

- [**Documentación oficial de Storybook**](https://storybook.js.org/docs/react/get-started/introduction) tiene documentación de API, ejemplos y la galería de complementos.

- [**Cómo probar realmente las IU**](https://storybook.js.org/blog/how-to-actually-test-uis/) es un resumen de las estrategias prácticas de prueba de interfaz de usuario de Shopify, Adobe, Twilio y más.

- [**Discord de Storybook**](https://discord.gg/UUt2PJb) te pone en contacto con la comunidad y los mantenedores de Storybook.

- [**Blog de Storybook**](https://medium.com/storybookjs) muestra las últimas versiones y funciones para optimizar el flujo de trabajo de desarrollo de la interfaz de usuario.
