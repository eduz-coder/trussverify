# TrussVerify — prototipo seguro del portal

## Qué es esto

Un sitio estático de demostración para el portal de clientes de TrussVerify (revisión de paquetes de trusses antes de cotizar o producir). Contiene **solo datos ficticios de ejemplo**: la página principal, la pantalla de subida, el panel del cliente, un reporte de muestra y la página de cómo se tratan los archivos. Nada se sube, se envía ni se guarda de verdad; es navegable para enseñar el concepto.

Archivos:

- `index.html` — página principal del servicio.
- `upload.html` — pantalla de subida (solo frente, no funcional).
- `dashboard.html` — panel del cliente con trabajos ficticios.
- `sample-report.html` — reporte de muestra ficticio (Maple Street Residence).
- `privacy.html` — cómo se tratan los archivos del cliente.
- `styles.css` — estilos compartidos (sin recursos externos; funciona sin conexión una vez descargado).

## Pasos para publicarlo (en este orden)

1. **Pon en privado el repositorio actual de inmediato.** La página anterior queda fuera de línea mientras tanto.
2. **Después, borra ese repositorio por completo y crea uno NUEVO y público llamado `trussverify`.** Aunque reemplaces el archivo, el historial del repo viejo conserva la página anterior; un repo nuevo mantiene el historial limpio desde cero.
3. **Sube TODOS los archivos de esta carpeta** al repo nuevo, descomprimidos y sueltos (no subas el ZIP).
4. En el repo nuevo: **Settings → Pages → Deploy from a branch → main / root → Save**.
5. La dirección queda igual: **https://eduz-coder.github.io/trussverify/**

## Advertencias

- **Nunca vuelvas a subir la página generada con Gemini ni datos de trabajos reales.** Esa página contenía detalles internos que no deben ser públicos. Este prototipo la reemplaza con contenido ficticio y lenguaje seguro para clientes.
- Si actualizas el sitio, edita estos archivos y vuelve a subir los archivos sueltos al repo nuevo, nada más.
- El correo `hello@trussverify.com` que aparece en la página de privacidad es un **marcador de posición**: solo será real cuando se compre el dominio. Mientras tanto no lo uses en correos de presentación como dirección de contacto válida.
- Este prototipo es solo la vitrina. La versión real (cuentas, subidas privadas, borrado automático) va en una fase posterior, fuera de GitHub Pages, porque los archivos de clientes nunca deben guardarse en GitHub.
