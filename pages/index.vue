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
          <li>
            <a href="#"
              ><img src="~/assets/img/glyph-github.svg" alt="Link to Github" />
            </a>
          </li>
          <li>
            <a href="#"
              ><img
                src="~/assets/img/glyph-mastadon.svg"
                alt="Link to Mastadon"
              />
            </a>
          </li>
          <li>
            <a href="#"
              ><img
                src="~/assets/img/glyph-twitter.svg"
                alt="Link to Twitter"
              />
            </a>
          </li>
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
        <h2>Features</h2>

        <p>
          Lorem ipsum sit amet, consectetur adipiscing elit
        </p>

        <ul>
          <li>
            <img src="~/assets/img/icon-linux.png" alt="Linux icon" />
            <h3>Native for linux</h3>
            <p>
              Akira is built in Vala and GTK, no electron shenanigans here, and
              specially crafted to run on Linux.
            </p>
          </li>
          <li>
            <img src="~/assets/img/icon-svg.png" alt="SVG icon" />
            <h3>SVG-Based Canvas</h3>
            <p>
              Akira is built in Vala and GTK, no electron shenanigans here, and
              specially crafted to run on Linux.
            </p>
          </li>
          <li>
            <img src="~/assets/img/icon-shapes.png" alt="Shapes icon" />
            <h3>Non-Destructive Editing</h3>
            <p>
              Akira is built in Vala and GTK, no electron shenanigans here, and
              specially crafted to run on Linux.
            </p>
          </li>
          <li>
            <img src="~/assets/img/icon-guides.png" alt="Guides icon" />
            <h3>Pixel Precision</h3>
            <p>
              Akira is built in Vala and GTK, no electron shenanigans here, and
              specially crafted to run on Linux.
            </p>
          </li>
          <li>
            <img src="~/assets/img/icon-branches.png" alt="Git branches icon" />
            <h3>Built-in Version Control</h3>
            <p>
              Akira is built in Vala and GTK, no electron shenanigans here, and
              specially crafted to run on Linux.
            </p>
          </li>
          <li>
            <img src="~/assets/img/icon-wireframe.png" alt="Wireframe icon" />
            <h3>Intuitive interface</h3>
            <p>
              Akira is built in Vala and GTK, no electron shenanigans here, and
              specially crafted to run on Linux.
            </p>
          </li>
        </ul>

        <a href="features" class="cta">Learn more</a>
      </section>

      <section class="container team">
        <h2>Team</h2>

        <p>
          Akira exists thanks to the contribution of hundreds of developers and
          designers, but the four guys that started all of this need a bit of a
          shout out.
        </p>

        <ul>
          <li>
            <img
              src="~/assets/img/avatar-albertoFanjul.png"
              alt="Alberto Fanjul photo"
            />
            <h3>Alberto Funjul</h3>
          </li>
          <li>
            <img
              src="~/assets/img/avatar-alessandroCastellani.png"
              alt="Alessandro Castellani photo"
            />
            <h3>Alessandro Castellani</h3>
          </li>
          <li>
            <img
              src="~/assets/img/avatar-bilalElmoussaoui.png"
              alt="Bilal Elmoussaoui photo"
            />
            <h3>Bilal Elmoussaoui</h3>
          </li>
          <li>
            <img
              src="~/assets/img/avatar-felipeEscoto.png"
              alt="Felipe Escoto photo"
            />
            <h3>Felipe Escoto</h3>
          </li>
        </ul>
      </section>

      <section class="container">
        <h2>Support us</h2>

        <p>
          Akira is a Free and Open Source Project that aims at offering a
          professional and native Linux alternative to proprietary UX Design
          apps. Akira is made possible by the work of talented developers, help
          us to keep this project alive.
        </p>

        <a href="#" class="cta">Patreon</a>
        <a href="#" class="cta">Liberapay</a>
      </section>
    </main>

    <footer>
      <h2>
        <Logo />
        Akira
      </h2>

      <nav>
        <ul>
          <li><a href="features">Features</a></li>
          <li><a href="team">Team</a></li>
          <li><a href="roadmap">Roadmap</a></li>
          <li><a href="changelog">Changelog</a></li>
        </ul>
      </nav>

      <p>
        Akira is a Free and Open Source Software under GPLv3 License, including
        all its assets, templates and this very own website. Sharing is caring.
      </p>

      <ul>
        <li>
          <a href="#"
            ><img src="~/assets/img/glyph-github.svg" alt="Link to Github" />
          </a>
        </li>
        <li>
          <a href="#"
            ><img
              src="~/assets/img/glyph-mastadon.svg"
              alt="Link to Mastadon"
            />
          </a>
        </li>
        <li>
          <a href="#"
            ><img src="~/assets/img/glyph-twitter.svg" alt="Link to Twitter" />
          </a>
        </li>
      </ul>
    </footer>
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
body {
  font-family: 'Open Sans', 'sans-serif';
}

.subtitle {
  font-size: 16px;
  color: #526488;
}

h3 {
  font: bold 18px 'Open Sans Condensed', 'sans-serif';
}

section {
  text-align: center;
}

section .cta {
  background: linear-gradient(#ffa154, #f37329);
  border-radius: 4px;
  color: #fff;
  display: inline-block;
  font: bold 18px 'Open Sans';
  padding: 15px 0 14px;
  text-align: center;
  text-decoration: none;
  text-shadow: 0 1px 3px rgba(0, 0, 0, 0.15);
  width: 177px;
}

header {
  background: #333333;
  color: #ffffff;
}

nav li {
  display: inline-block;
}

nav a {
  color: #ffffff;
}

ul {
  list-style: none;
  margin: 0;
  padding: 0;
}

.team img {
  border-radius: 50%;
  width: 196px;
}

footer {
  background: #333333;
  color: #ffffff;
}
</style>
