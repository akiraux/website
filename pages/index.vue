<template>
  <div class="wrapper">
    <header>
      <logo />
      <nav>
        <ul>
          <li><a href="features">Features</a></li>
          <li><a href="team">Team</a></li>
          <li><a href="roadmap">Roadmap</a></li>
          <li><a href="changelog">Changelog</a></li>
          <li class="cta"><a href="donate">Donate</a></li>
        </ul>

        <ul class="social">
          <li><a href="http://github.com">G</a></li>
          <li><a href="http://mastadon.com">M</a></li>
          <li><a href="http://twitter.com">T</a></li>
        </ul>
      </nav>

      <h1>Akira</h1>
      <p class="subtitle">The Linux design tool</p>

      <p>
        Akira is a native Linux design application built in Vala and GTK. Akira
        focusses on offering a modern and fast approach to UI and UX design,
        mainly targetting web designers and graphic designers. The main goal is
        to offer a valid and professional solution for designers who want to use
        Linux as their main OS.
      </p>

      <ul>
        <li><a href="#">Get it on appcenter</a></li>
        <li><a href="#">Download on flathub</a></li>
        <li><a href="#">Download on snapcraft</a></li>
      </ul>
    </header>

    <main>
      <section class="container">
        <h2>
          Features
        </h2>

        <p>
          Lorem ipsum sit amet, consectetur adipiscing elit
        </p>

        <ul>
          <li>
            <img src="" alt="Linux icon" />
            <h3>Native for linux</h3>
            <p>
              Akira is built in Vala and GTK, no electron shenanigans here, and
              specially crafted to run on Linux.
            </p>
          </li>
          <li>
            <img src="" alt="SVG icon" />
            <h3>SVG-Based Canvas</h3>
            <p>
              Akira is built in Vala and GTK, no electron shenanigans here, and
              specially crafted to run on Linux.
            </p>
          </li>
          <li>
            <img src="" alt="Shapes icon" />
            <h3>Non-Destructive Editing</h3>
            <p>
              Akira is built in Vala and GTK, no electron shenanigans here, and
              specially crafted to run on Linux.
            </p>
          </li>
          <li>
            <img src="" alt="Guides icon" />
            <h3>Pixel Precision</h3>
            <p>
              Akira is built in Vala and GTK, no electron shenanigans here, and
              specially crafted to run on Linux.
            </p>
          </li>
          <li>
            <img src="" alt="Git branches icon" />
            <h3>Built-in Version Control</h3>
            <p>
              Akira is built in Vala and GTK, no electron shenanigans here, and
              specially crafted to run on Linux.
            </p>
          </li>
          <li>
            <img src="" alt="Wireframe icon" />
            <h3>Intuitive interface</h3>
            <p>
              Akira is built in Vala and GTK, no electron shenanigans here, and
              specially crafted to run on Linux.
            </p>
          </li>
        </ul>

        <a href="features" class="cta">Learn more</a>
      </section>
    </main>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
  @apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-size: 16px;
  color: #526488;
}
</style>
