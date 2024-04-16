<template>
  <nav>
    <ul>
      <li>Inicio</li>
      <li>Ver Más</li>
      <li>Resumen</li>
      <li>Datos Importantes</li>
      <li>Usos</li>
      <li>Contactenos</li>
    </ul>
  </nav>
  <div class="">
    <h1>FRAMEWORKS DE DESARROLLO DE JAVASCRIPT</h1>
    <p>Conoce los principales frameworks de desarrollo de JavaScript</p>
    <a href="http://">Ver Más</a>
  </div>
  <div class="">
    <div class="">
      <i class="fa-brands fa-vuejs"></i>
      <h3>Vue</h3>
      <p>Framework progresivo para construir interfaces de usuario interactivas y aplicaciones de una sola página, con
        un enfoque gradual y herramientas para el desarrollo de componentes reutilizables.</p>
    </div>
    <div>
      <i class="fa-brands fa-react"></i>
      <h3>React</h3>
      <p>Biblioteca para construir interfaces de usuario interactivas, desarrollada por Facebook, enfocada en
        componentes reutilizables y unidireccionalidad de datos.</p>
    </div>
    <div>
      <i class="fa-brands fa-angular"></i>
      <h3>Angular</h3>
      <p>Framework desarrollado por Google para construir aplicaciones web de una sola página y aplicaciones web
        progresivas, utilizando TypeScript y proporcionando un conjunto completo de características para el desarrollo
        web, como enrutamiento, gestión de formularios e inyección de dependencias.</p>
    </div>
    <div>
      <i class="fa-solid fa-atom"></i>
      <h3>Electron</h3>
      <p>Framework para crear aplicaciones de escritorio multiplataforma utilizando tecnologías web como HTML, CSS y
        JavaScript, permitiendo a los desarrolladores crear aplicaciones de escritorio con habilidades y herramientas
        web.</p>
    </div>
  </div>
  <div>
    <h1>{{ titulo }}</h1>
    <p>{{ descripcion }}</p>
  </div>
  <div>
    <p></p>
  </div>
  <div>
    <div>
<p>React:

Fecha de lanzamiento inicial: Marzo de 2013.
Desarrollador principal: Facebook.
Popularidad: Es uno de los frameworks más populares para el desarrollo de interfaces de usuario, con una gran comunidad de desarrolladores y una amplia adopción en la industria.
Empresas que lo utilizan: Facebook, Instagram, Netflix, Airbnb, WhatsApp, entre otros.
Vue:

Fecha de lanzamiento inicial: Febrero de 2014.
Desarrollador principal: Evan You.
Popularidad: Ha experimentado un rápido crecimiento en popularidad debido a su curva de aprendizaje suave y su flexibilidad. Es considerado uno de los frameworks más fáciles de aprender.
Empresas que lo utilizan: Alibaba, Xiaomi, Baidu, Adobe, Nintendo, entre otros.
Electron:

Fecha de lanzamiento inicial: Mayo de 2013.
Desarrollador principal: GitHub (anteriormente conocido como Atom Shell).
Popularidad: Ha ganado popularidad como una opción para desarrollar aplicaciones de escritorio multiplataforma debido a su simplicidad y la posibilidad de utilizar tecnologías web estándar.
Aplicaciones populares construidas con Electron: Slack, Discord, Visual Studio Code, Twitch, Skype, entre otros.
Angular:

Fecha de lanzamiento inicial: Septiembre de 2016 (Angular 2, la versión original de Angular fue lanzada en 2010).
Desarrollador principal: Equipo de Angular en Google.
Popularidad: Es un framework ampliamente utilizado para la construcción de aplicaciones web empresariales debido a su robustez y las características que proporciona.
Empresas que lo utilizan: Google, Microsoft, Deutsche Bank, Forbes, PayPal, entre otros.</p>
    </div>
    <div>
<img src="https://www.orangemantra.com/blog/wp-content/uploads/2019/10/Top-7-Best-Javascript-Frameworks-to-Choose-in-2023.png" alt="">
    </div>
  </div>
  <div>
    <h1>Usos</h1>
    <p>React:

      Construcción de aplicaciones web de una sola página (SPA) con interfaces de usuario dinámicas y altamente
      interactivas.
      Desarrollo de componentes reutilizables para integrar en diferentes partes de una aplicación web.
      Creación de aplicaciones móviles nativas utilizando React Native.
      Implementación de interfaces de usuario para aplicaciones de administración y paneles de control.
      Vue:

      Desarrollo de aplicaciones web de una sola página (SPA) y aplicaciones de múltiples páginas (MPA) con interfaces
      de usuario dinámicas y fluidas.
      Integración gradual en proyectos existentes, permitiendo la adopción progresiva de Vue en aplicaciones web
      preexistentes.
      Construcción de interfaces de usuario para aplicaciones móviles utilizando frameworks como Quasar o
      NativeScript-Vue.
      Electron:

      Creación de aplicaciones de escritorio multiplataforma (Windows, macOS, Linux) utilizando tecnologías web estándar
      (HTML, CSS, JavaScript).
      Desarrollo de aplicaciones de escritorio para diversas industrias, como herramientas de productividad, editores de
      texto, reproductores multimedia, etc.
      Implementación de aplicaciones de escritorio con acceso a recursos del sistema operativo, como archivos locales,
      notificaciones y dispositivos periféricos.
      Angular:

      Desarrollo de aplicaciones web de una sola página (SPA) y aplicaciones web progresivas (PWA) con estructura
      modular y escalabilidad.
      Construcción de aplicaciones empresariales complejas con características como enrutamiento, gestión de formularios
      y autenticación.
      Creación de aplicaciones móviles híbridas utilizando frameworks como Ionic, que se basa en Angular para la capa de
      interfaz de usuario.
      Desarrollo de aplicaciones web con características avanzadas de accesibilidad y rendimiento, adecuadas para
      proyectos de gran escala.</p>
  </div>
  <div class="footer">
    <div>
      <p></p>
    </div>
    <div>
      <p></p>
    </div>
    <div>
      <i class="fa-brands fa-square-facebook"></i>
      <i class="fa-brands fa-square-whatsapp"></i>
      <i class="fa-brands fa-square-instagram"></i>
      <i class="fa-brands fa-square-x-twitter"></i>
    </div>
  </div>

</template>

<script>
export default {
  name: 'PageWeb',
  data() {
    return {
      titulo: 'Bienvenido a mi componente',
      descripcion: 'Este es un ejemplo de un componente Vue.js'
    };
  }
};
</script>

<style></style>