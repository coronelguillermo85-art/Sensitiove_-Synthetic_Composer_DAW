# Sensitive Synthetic Composer DAW

Un DAW liviano de código abierto para componer rápido, directo del navegador — sin instalar nada, sin depender de internet una vez descargado.

Hecho por necesidad: una herramienta para bocetar ideas musicales completas (melodía, bajo, ritmo y voz) en cualquier compu o tablet, y después bajar el track para masterizarlo en tu DAW de siempre.

## Qué tiene

- 🎹 **Piano roll** con dos pistas MIDI independientes (melodía + bajo)
- 🎸 **Sintetizador de bajo propio** — sub-oscilador + filtro con envolvente, no un oscilador genérico
- 🎛️ **Seis instrumentos MIDI**: piano acústico, Rhodes, órgano, pad, lead synth y bajo
- 🥁 **Secuenciador de percusión** por pads, con patrones de género precargados
- 🎤 **Grabación de voz** por micrófono, en su propia pista
- 📂 **Importación de archivos de audio** (loops, samples) en pista separada
- 🔌 **Web MIDI real**: conectá tu controlador y tocá — reconecta en caliente si lo enchufás después de abrir la página
- 🖱️ **Botones de "modo de trabajo"**: elegí de un click si vas a tocar teclado, bajo, grabar voz o cargar audio
- 💾 **Exportación** a WAV (mezcla completa) o stems individuales en ZIP
- 🌐 **100% offline**: es un solo archivo HTML. Se abre con doble click, sin servidor, sin conexión

- <img width="1024" height="1536" alt="flyer sscd" src="https://github.com/user-attachments/assets/776ef235-22ef-44ab-ab04-2a1561b9d183" />


## Cómo usarlo

1. Descargá `sensitive_synthetic_composer_daw.html`
2. Abrilo con cualquier navegador moderno (Chrome recomendado, por soporte completo de Web MIDI)
3. Conectá un controlador MIDI (opcional) o usá el teclado en pantalla
4. Componé: melodía, bajo, ritmo, voz, loops de audio
5. Exportá tu mezcla o los stems y masterizala donde quieras

No requiere instalación, build, ni servidor. No manda datos a ningún lado — todo corre local en tu navegador.

## Stack técnico

- Vanilla JavaScript, un solo archivo HTML
- Web Audio API (síntesis, grabación, renderizado offline para exportar)
- Web MIDI API (entrada de controladores externos)
- JSZip (exportación de stems)

## Filosofía

Este DAW no busca reemplazar a Reaper, FL Studio ni ningún DAW profesional — es una herramienta de **maquetación rápida**: capturar una idea completa apenas se te ocurre, en la compu que tengas a mano, sin fricción de instalación ni licencias. De ahí bajás el track y lo terminás donde ya trabajás.


<img width="1913" height="943" alt="image" src="https://github.com/user-attachments/assets/c5cf59aa-5f40-48d8-8b47-56639771eb5f" />


Parte del ecosistema [Sensitive Lab](https://github.com/coronelguillermo85-art) — instrumentos y herramientas musicales DIY.

## Licencia

MIT — usalo, modificalo, compartilo.
