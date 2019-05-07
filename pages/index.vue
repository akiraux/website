<template>
  <div class="wrapper">
    <header>
      <div>
        <logo />
        <nav>
          <ul>
            <li><a href="#features">Features</a></li>
            <li><a href="#team">Team</a></li>
            <li><a href="roadmap">Roadmap</a></li>
            <li><a href="changelog">Changelog</a></li>
            <li class="cta"><a href="donate">Donate</a></li>
          </ul>

          <ul class="social">
            <li>
              <a
                href="https://github.com/akiraux"
                target="_blank"
                title="Akira UX at Github"
                ><img
                  src="~/assets/img/glyph-github.svg"
                  alt="Link to Github"
                />
              </a>
            </li>
            <li>
              <a
                href="https://fosstodon.org/@akiraux"
                target="_blank"
                title="Akira UX at Mastadon"
                ><img
                  src="~/assets/img/glyph-mastadon.svg"
                  alt="Link to Mastadon"
                />
              </a>
            </li>
            <li>
              <a
                href="https://twitter.com/akiraux"
                target="_blank"
                title="Akira UX at Twitter"
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
        <img
          class="akiraTeen"
          src="~/assets/img/akira-teen.png"
          alt="Akira Teen mascot"
        />

        <p>
          Akira is a native Linux design application built in Vala and GTK.
          Akira focusses on offering a modern and fast approach to UI and UX
          design, mainly targetting web designers and graphic designers. The
          main goal is to offer a valid and professional solution for designers
          who want to use Linux as their main OS.
        </p>

        <ul class="downloads">
          <li>
            <a href="#"
              ><img
                src="~/assets/img/downloads-app.png"
                alt="Get it on appcenter"
            /></a>
          </li>
          <li>
            <a href="#"
              ><img
                src="~/assets/img/downloads-flat.png"
                alt="Download on flathub"
            /></a>
          </li>
          <li>
            <a href="#"
              ><img
                src="~/assets/img/downloads-snap.png"
                alt="Download on snapcraft"
            /></a>
          </li>
        </ul>
      </div>
    </header>

    <main>
      <section id="features" class="features">
        <h2>Features</h2>

        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit,sed do eiusmod
          tempor incididunt ut labore et dolore magnaaliqua.
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
              Akira is powered by GooCanvas, a native SVG-based canvas Library
              maintained by GNOME.
            </p>
          </li>
          <li>
            <img src="~/assets/img/icon-shapes.png" alt="Shapes icon" />
            <h3>Non-Destructive Editing</h3>
            <p>
              All the native shapes and elements are vector, giving you the
              ability to use boolean operations without ever loosing the
              original shape.
            </p>
          </li>
          <li>
            <img src="~/assets/img/icon-guides.png" alt="Guides icon" />
            <h3>Pixel Precision</h3>
            <p>
              An always crip and grid-hinted design thanks to the built-in pixel
              grid, rulers, and guidelines. Becuase you know, sub-pixels are not
              a thing.
            </p>
          </li>
          <li>
            <img src="~/assets/img/icon-branches.png" alt="Git branches icon" />
            <h3>Built-in Version Control</h3>
            <p>
              Never lose your work again with the Akira file format and its
              built-in local Git repository
            </p>
          </li>
          <li>
            <img src="~/assets/img/icon-wireframe.png" alt="Wireframe icon" />
            <h3>Intuitive interface</h3>
            <p>
              No need to get lost in hundreds of menus or dropdowns, watch the
              interface follow your actions and boost your productivity.
            </p>
          </li>
        </ul>

        <a href="features" class="cta">Learn more</a>
      </section>

      <section id="team" class="team">
        <h2 class="container mx-auto">Team</h2>

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

        <a href="team" class="cta">Contributors</a>
      </section>

      <section id="support" class="support">
        <h2>Support us</h2>

        <p>
          Akira is a Free and Open Source Project that aims at offering a
          professional and native Linux alternative to proprietary UX Design
          apps. Akira is made possible by the work of talented developers, help
          us to keep this project alive.
        </p>

        <a
          href="https://www.patreon.com/akiraux/posts"
          class="cta"
          target="_blank"
          title="Akira UX at Patreon"
          >Patreon
        </a>
        <a
          href="https://liberapay.com/AkiraUX/"
          class="cta"
          target="_blank"
          title="Akira UX at Liberapay"
          >Liberapay
        </a>
      </section>
    </main>

    <footer>
      <div>
        <h2>
          <Logo />
          Akira
        </h2>

        <nav>
          <ul>
            <li><a href="#features">Features</a></li>
            <li><a href="#team">Team</a></li>
            <li><a href="roadmap">Roadmap</a></li>
            <li><a href="changelog">Changelog</a></li>
          </ul>
        </nav>

        <p>
          Akira is a Free and Open Source Software under GPLv3 License,
          including all its assets, templates and this very own website. Sharing
          is caring.
        </p>

        <ul class="social">
          <li>
            <a
              href="https://github.com/akiraux"
              target="_blank"
              title="Akira UX at Github"
              ><img src="~/assets/img/glyph-github.svg" alt="Link to Github" />
            </a>
          </li>
          <li>
            <a
              href="https://fosstodon.org/@akiraux"
              target="_blank"
              title="Akira UX at Mastadon"
              ><img
                src="~/assets/img/glyph-mastadon.svg"
                alt="Link to Mastadon"
              />
            </a>
          </li>
          <li>
            <a
              href="https://twitter.com/akiraux"
              target="_blank"
              title="Akira UX at Twitter"
              ><img
                src="~/assets/img/glyph-twitter.svg"
                alt="Link to Twitter"
              />
            </a>
          </li>
        </ul>
      </div>
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
  font: 14px/1.5 'Open Sans', 'sans-serif';
}

a {
  text-decoration: none;
}

h1 {
  font: normal 80px/1 'Open Sans', 'sans-serif';
  margin: 90px 0 0;
  text-transform: uppercase;
}

h2 {
  font-size: 60px;
  font-weight: normal;
  line-height: 1;
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

p {
  margin: 25px auto 40px;
  max-width: 598px;
}

header {
  color: #ffffff;
  padding: 30px 0 60px;
  position: relative;
}

header:after {
  background: linear-gradient(-45deg, #4f4f44, #353535);
  bottom: 0;
  content: '';
  height: 180%;
  position: absolute;
  transform: skewY(-5deg);
  width: 100%;
  z-index: -2;
}

header:before {
  background: url(~assets/img/header-bg.svg) no-repeat center center;
  content: '';
  top: 0;
  height: 120%;
  left: 0;
  opacity: 0.5;
  position: absolute;
  right: 0;
  z-index: -1;
}

header > div {
  margin: 0 auto 0;
}

header .logo {
  float: left;
}

header nav {
  display: flex;
  justify-content: space-between;
  margin: 0 0 0 63px;
}

header h1 {
  clear: left;
}

header p {
  margin: 30px 0;
}

img {
  vertical-align: top;
}

nav li {
  display: inline-block;
  margin: 25px 0 0 75px;
  text-transform: uppercase;
}

nav .social li {
  margin: 25px 25px 0 0;
}

nav a {
  color: #ffffff;
}

nav .cta {
  background: linear-gradient(#ffa154, #f37329);
  border-radius: 4px;
  color: #fff;
  padding: 4px 10px;
  text-decoration: none;
  text-shadow: 0 1px 3px rgba(0, 0, 0, 0.15);
}

nav .cta:before {
  background: url('~assets/img/glyph-heart.svg') no-repeat center center;
  content: '';
  display: inline-block;
  height: 13px;
  margin: 0 6px 0 0;
  vertical-align: middle;
  width: 15px;
}

ul {
  list-style: none;
  margin: 0;
  padding: 0;
}

.subtitle {
  font-size: 20px;
  line-height: 1;
  margin: 0;
}

.akiraTeen {
  max-width: 565px;
  right: 55px;
  top: 10px;
}

.downloads li {
  display: inline-block;
  margin: 0 25px 0 0;
}

.wrapper {
  overflow: hidden;
}

.features {
  margin: 65px 0;
  padding: 120px 0 65px;
}

.features ul {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  margin: 0 auto;
}

.features li {
  width: 266px;
}

.team {
  padding: 110px 0 100px;
  position: relative;
}

.team:before {
  background: #f5f5f5;
  content: '';
  height: 180%;
  left: 0;
  position: absolute;
  top: 0;
  transform: skewY(6deg);
  width: 100%;
  z-index: -1;
}

.team img {
  border-radius: 50%;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.25);
  margin: 0 0 27px;
  width: 198px;
}

.team ul {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  margin: 90px auto 78px;
  max-width: 1100px;
}

.team li {
  width: 198px;
}

.support {
  padding: 110px 0 110px;
  position: relative;
}

.support:before {
  background: #ffffff;
  content: '';
  height: 180%;
  left: 0;
  position: absolute;
  top: 0;
  transform: skewY(-6deg);
  width: 100%;
  z-index: -1;
}

.support .cta {
  margin: 0 45px;
}

footer {
  color: #ffffff;
  padding: 110px 0 0;
  margin: 0 0 50px;
  position: relative;
  text-align: center;
}

footer:before {
  background: linear-gradient(-45deg, #4f4f4f, #323233);
  content: '';
  height: 180%;
  left: 0;
  position: absolute;
  top: 0;
  transform: skewY(6deg);
  width: 100%;
  z-index: -1;
}

footer > div {
  margin: 0 auto;
  max-width: 392px;
}

footer ul {
  display: flex;
  justify-content: space-between;
  margin: 30px 0 auto;
}

footer li {
  margin: 0;
}

footer .social {
  margin: 0 auto;
  max-width: 100px;
}

@media (min-width: 1260px) {
  header > div {
    margin: 0 auto 0;
    max-width: 1260px;
    position: relative;
  }

  .akiraTeen {
    position: absolute;
  }

  .features ul {
    margin: 0 auto;
    max-width: 1050px;
  }
}
</style>
