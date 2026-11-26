# 🏗️ Kit del Arquitecto de Agentes

**🇧🇷 [Português](README.md) · 🇺🇸 [English](README.en.md) · 🇪🇸 [Español](README.es.md)**

Siete plantillas rellenables que se convierten en la **especificación de un agente de IA en una página**, más el prompt de ensayo simulado para probar la especificación en un chat de IA antes de construir nada. Kit de trabajo derivado del curso [Arquitecto de Trabajo con IA](https://linnoff88-dev.github.io/arckhe-/) (ARCKHÉ AI PRO).

## 📖 Guía de uso

Guía completa (landing + paso a paso): **https://linnoff88-dev.github.io/arckhe-/guia/es/**

## Usar

App: **https://linnoff88-dev.github.io/arckhe-/** (página única, sin instalación, todo se guarda en tu navegador).

Los siete bloques:

1. Proceso y resultado
2. Mapa de seis eslabones (entrada, decisión, acción, verificación, excepción, resultado)
3. Solicitud de largo horizonte (objetivo, contexto, restricciones, criterio, aprobación)
4. Cadena de orquestación (coordinador, especialistas, herramientas, sistemas, verificación)
5. Inventario de contexto (qué es, dónde está, formato, accesible, responsable)
6. Ficha de calidad (condiciones con rango, detenerse, llamar, batería de casos)
7. Matriz de permisos (leer, escribir, modificar, enviar, comprar, borrar, aprobar + datos fuera de alcance)

Presets por área (botón «cargar ejemplo por área»): **ventas** (reactivación de clientes), **salud** (confirmación de consultas y denegaciones de cobertura), **contable** (solicitud de documentos y obligaciones) y **abogacía** (control de plazos). Al cargar, el área queda marcada y el kit empieza a señalar sus brechas específicas: datos de pacientes fuera de alcance en salud, «quien registra no aprueba» en contabilidad, plazos que siempre requieren llamar a una persona en abogacía.

Cuadernos profesionales que usan estos presets: [salud](https://linnoff88-dev.github.io/arckhe-/) · [contable y financiero](https://linnoff88-dev.github.io/arckhe-/) · [abogacía](https://linnoff88-dev.github.io/arckhe-/).

Resultados: especificación en una página (copiar, imprimir/PDF, descargar `.md`), lista de brechas detectadas, prompt de ensayo simulado, exportar/importar `.json`.

## Estructura

- `index.html` — la app (HTML + CSS + JS, autocontenida)
- `guia/index.html` — landing + guía de uso
- `capa/capa.png` — portada oficial 1280×720
