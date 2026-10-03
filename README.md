<div align="center">
  <img src="assets/icon-192.png" alt="Inventar.io" width="88" height="88" />
  <h1>Inventar.io</h1>
  <p><strong>El inventario, bajo control.</strong></p>
  <p>Una página de presentación para conocer el producto, sus flujos principales y solicitar una demo.</p>
  <p>
    <a href="https://danidevsdbk.github.io/Inventar.io.info/">Ver la página</a>
    ·
    <a href="mailto:danidevsdbk@gmail.com?subject=Quiero%20conocer%20Inventar.io">Contactar</a>
  </p>
</div>

---

## Sobre esta página

Este repositorio contiene la web pública de Inventar.io. Presenta una aplicación de inventario en uso real y explica, de forma breve, cómo ayuda a consultar existencias, ubicar productos y registrar operaciones desde móvil o escritorio.

La aplicación incluye catálogo con variantes, stock por ubicación, entradas, salidas, traspasos, reservas, identificación QR/NFC, estadísticas y una experiencia PWA.

## Explorar

- **El reto:** información de stock y ubicación accesible para el equipo.
- **El producto:** espacios preparados para capturas reales, sin pantallas inventadas.
- **Demo:** reproductor opcional para un vídeo de demostración.
- **Tecnología y contribución:** stack, decisiones de arquitectura y uso de IA descritos con transparencia.
- **Contacto:** [danidevsdbk@gmail.com](mailto:danidevsdbk@gmail.com).

## Publicación automática

La web es estática y se publica con GitHub Pages mediante GitHub Actions. Cada cambio en `main` ejecuta `.github/workflows/pages.yml` y despliega `index.html` junto a sus recursos.

Para activarla la primera vez:

1. Abre **Settings → Pages** en el repositorio.
2. En **Build and deployment**, selecciona **GitHub Actions** como fuente.
3. Haz un push a `main` o inicia manualmente el workflow desde **Actions**.

La URL del proyecto es [danidevsdbk.github.io/Inventar.io.info](https://danidevsdbk.github.io/Inventar.io.info/).

## Capturas y demo

Las tarjetas marcadas **Captura real pendiente** son marcadores visuales, no capturas de la aplicación. Cuando se añadan imágenes, deben usar información ficticia y no revelar datos de clientes.

El vídeo es opcional: añade `demoInventario.mp4` en la raíz del repositorio para que se incluya en el despliegue. Al publicarse en Pages, el archivo será accesible públicamente; usa únicamente datos sintéticos y elimina credenciales o información privada.

## Contacto

Para conocer el producto o coordinar una demostración: [danidevsdbk@gmail.com](mailto:danidevsdbk@gmail.com).
