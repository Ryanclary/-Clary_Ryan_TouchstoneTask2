# -Clary_Ryan_TouchstoneTask3
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>North Star Bakery | About</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header class="site-header">
    <a class="brand" href="index.html" aria-label="North Star Bakery home">
      <img src="bakery-logo_c.png" alt="North Star Bakery">
    </a>
    <p class="tagline">A neighborhood bakery with a place for everyone.</p>
    <nav class="site-nav" aria-label="Main navigation">
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="products.html">Our products</a></li>
        <li><a href="about.html" aria-current="page">Our story</a></li>
        <li><a href="contact.html">Contact and pre-orders</a></li>
        <li><a href="media.html">Media</a></li>
      </ul>
    </nav>
  </header>
  <main>
    <h1>About North Star Bakery</h1>
    <section>
      <h2>Our story</h2>
      <p>North Star Bakery began with a borrowed mixer, a family sourdough starter, and a wish for a welcoming place on Maple Street. Today, our bakers still work in small batches and believe the best bakery is one that becomes part of the rhythm of its neighborhood.</p>
      <p>We bake early so commuters can start their day with something special, and we keep our doors open for families, friends, and event planners looking for food made with care.</p>
    </section>
    <section>
      <h2>How we source</h2>
      <p>We choose regional flour whenever possible, work with nearby growers for seasonal fruit, and buy eggs and dairy from suppliers who share our commitment to responsible practices. Seasonal baking helps us support local producers and keeps our menu connected to the place we call home.</p>
    </section>
    <section>
      <h2>Meet the team</h2>
      <dl>
        <dt><strong>Mara, head baker</strong></dt>
        <dd>Mara leads our bread program and guards the bakery's original sourdough starter.</dd>
        <dt><strong>Dev, pastry lead</strong></dt>
        <dd>Dev turns seasonal fruit, butter, and spice into the pastries that disappear first.</dd>
        <dt><strong>Jo, community host</strong></dt>
        <dd>Jo helps customers plan orders for office mornings, birthdays, and neighborhood events.</dd>
      </dl>
    </section>
    <section>
      <h2>Behind the scenes</h2>
      <video controls width="640" aria-label="Behind the scenes footage from North Star Bakery">
        <source src="media/bakery-behind-scenes_c.mp4" type="video/mp4">
        Your browser does not support video playback. Please visit us at 214 Maple Street to see the bakery in person.
      </video>
    </section>
    <section>
      <h2>Welcome from the team</h2>
      <p>Hear a short welcome from our bakery team:</p>
      <audio controls>
        <source src="media/bakery-welcome_c.mp3" type="audio/mpeg">
        Your browser does not support audio playback. Please visit us at 214 Maple Street for a warm welcome in person.
      </audio>
    </section>
  </main>
  <footer class="site-footer">
    <p>&copy; 2026 North Star Bakery. Baked with care in our community.</p>
  </footer>
</body>
</html>


<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Contact and Pre-Orders | North Star Bakery</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header class="site-header">
    <a class="brand" href="index.html" aria-label="North Star Bakery home">
      <img src="bakery-logo_c.png" alt="North Star Bakery">
    </a>
    <p class="tagline">Good mornings begin at the bakery.</p>
    <nav class="site-nav" aria-label="Main navigation">
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="products.html">Our products</a></li>
        <li><a href="about.html">Our story</a></li>
        <li><a href="contact.html" aria-current="page">Contact and pre-orders</a></li>
        <li><a href="media.html">Media</a></li>
      </ul>
    </nav>
  </header>
  <main>
    <h1>Let's plan something delicious</h1>
    <p>Have a question or something special in mind? Send a request and our team will follow up to confirm availability and details. Requests are not confirmed orders until we reply.</p>
    <section aria-labelledby="request">
      <h2 id="request">Send an inquiry or pre-order request</h2>
      <form action="#" method="post">
        <fieldset>
          <legend>Your details</legend>
          <p>
            <label for="name">Name</label>
            <input id="name" name="name" type="text" autocomplete="name" required>
          </p>
          <p>
            <label for="email">Email</label>
            <input id="email" name="email" type="email" autocomplete="email" required>
          </p>
          <p>
            <label for="pickup-date">Preferred pickup date</label>
            <input id="pickup-date" name="pickup-date" type="date" required>
          </p>
        </fieldset>
        <fieldset>
          <legend>Your request</legend>
          <p>
            <label for="request-type">Request type</label>
            <select id="request-type" name="request-type" required>
              <option value="" selected disabled>Choose one</option>
              <option value="pre-order">Pre-order</option>
              <option value="general-question">General question</option>
            </select>
          </p>
          <p>
            <label for="item-details">What would you like? Include item, quantity, and any helpful details.</label>
            <textarea id="item-details" name="item-details" rows="5" required></textarea>
          </p>
          <p>
            <label for="allergy-notes">Allergy notes, if applicable</label>
            <textarea id="allergy-notes" name="allergy-notes" rows="3"></textarea>
          </p>
        </fieldset>
        <button type="submit">Send request</button>
      </form>
    </section>
    <section aria-labelledby="visit">
      <h2 id="visit">Visit the bakery</h2>
      <p>North Star Bakery is in the North Star neighborhood, near the town center.</p>
      <p>Monday-Friday, 6:30 a.m.-4 p.m.<br>Saturday-Sunday, 7 a.m.-2 p.m.</p>
    </section>
  </main>
  <footer class="site-footer">
    <p>North Star Bakery | Baked with care, shared with neighbors.</p>
    <p><a href="index.html">Back to home</a></p>
  </footer>
</body>
</html>

# North Star Bakery: Design Explanation
## Client alignment
The site uses a warm, calm visual style to reflect North Star Bakery's neighborhood focus and small-batch products. Rounded content panels, bakery photography, and the repeated invitation to explore products or contact the team help visitors find information and take the next step.
## Color palette
The four main colors are cream (`#fff6e8`), dark brown (`#30241e`), terracotta (`#80391f`), and wheat (`#e9cda3`). Cream and brown keep long passages readable, terracotta distinguishes headings and links, and wheat gives the header and borders a warm bakery feel.
## Typography
Georgia is used for body copy, while Arial is used for headings and form legends. The restrained two-font pairing keeps paragraphs comfortable to read and gives headings a clear, compact hierarchy.
## Responsive design
The layout starts as a single column on narrow screens, with navigation links wrapping as needed and images, audio, and video constrained to the available width. At 48rem, Flexbox places content sections side by side and changes the header to a horizontal layout; at 72rem, three sections can fit across the page.
## Design challenge
The pages have different content, including a product list, image gallery, media players, and a request form, but need to feel like one website. Shared header, navigation, section, and footer styles create consistency, while flexible sections and gallery figures let each page adapt to its content without fixed-width overflow.

<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>North Star Bakery | Fresh from our ovens</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header class="site-header">
    <a class="brand" href="index.html" aria-label="North Star Bakery home">
      <img src="bakery-logo_c.png" alt="North Star Bakery">
    </a>
    <p class="tagline">Good mornings begin at the bakery.</p>
    <nav class="site-nav" aria-label="Main navigation">
      <ul>
        <li><a href="index.html" aria-current="page">Home</a></li>
        <li><a href="products.html">Our products</a></li>
        <li><a href="about.html">Our story</a></li>
        <li><a href="contact.html">Contact and pre-orders</a></li>
        <li><a href="media.html">Media</a></li>
      </ul>
    </nav>
  </header>
  <main>
    <h1>A neighborhood bakery, made for sharing</h1>
    <p>Follow the smell of warm bread to North Star Bakery. We bake in small batches for early commutes, slow family breakfasts, and tables worth gathering around.</p>
    <section aria-labelledby="known-for">
      <h2 id="known-for">What we're known for</h2>
      <p>Crackly-crusted loaves, buttery pastries, and cakes made to bring people together. Everything is prepared with care and a little extra time for the details.</p>
      <img src="bakery-storefront_c.png" alt="The welcoming storefront of North Star Bakery">
    </section>
    <section aria-labelledby="this-week">
      <h2 id="this-week">This week's favorite: the morning bun</h2>
      <picture>
        <source media="(min-width: 700px)" srcset="bakery-feature-large_c.png">
        <img src="bakery-feature-small_c.png" alt="This week's freshly baked bakery feature" width="600" height="400">
      </picture>
      <p>Flaky layers, a tender center, and a bright finish make this a lovely companion to your morning coffee. Stop by to see what's fresh or ask us to set one aside.</p>
      <p><a href="products.html">Explore breads, pastries, and cakes</a></p>
    </section>
    <section aria-labelledby="visit-us">
      <h2 id="visit-us">Come by for a fresh start</h2>
      <p>Find us in the North Star neighborhood, near the town center.</p>
      <p>Monday-Friday, 6:30 a.m.-4 p.m.<br>Saturday-Sunday, 7 a.m.-2 p.m.</p>
      <p><a href="contact.html">Ask a question or request a pre-order</a></p>
    </section>
  </main>
  <footer class="site-footer">
    <p>North Star Bakery | Baked with care, shared with neighbors.</p>
    <p><a href="contact.html">Contact us</a></p>
  </footer>
</body>
</html>

<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Bakery Media | North Star Bakery</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header class="site-header">
    <a class="brand" href="index.html" aria-label="North Star Bakery home">
      <img src="bakery-logo_c.png" alt="North Star Bakery">
    </a>
    <p class="tagline">Good mornings begin at the bakery.</p>
    <nav class="site-nav" aria-label="Main navigation">
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="products.html">Our products</a></li>
        <li><a href="about.html">Our story</a></li>
        <li><a href="contact.html">Contact and pre-orders</a></li>
        <li><a href="media.html" aria-current="page">Media</a></li>
      </ul>
    </nav>
  </header>
  <main>
    <h1>A little look inside the bakery</h1>
    <p>From the first light in the shop to the loaves cooling after a bake, here's a glimpse of life at North Star Bakery.</p>
    <section class="media-gallery" aria-labelledby="bakery-gallery">
      <h2 id="bakery-gallery">Around the bakery</h2>
      <figure>
        <img src="bakery-storefront_c.png" alt="The storefront of North Star Bakery">
        <figcaption>Our neighborhood shop, ready to welcome you.</figcaption>
      </figure>
      <figure>
        <img src="bakery-bread_c.png" alt="Freshly baked artisan bread">
        <figcaption>Fresh bread, baked in small batches.</figcaption>
      </figure>
      <figure>
        <img src="bakery-signature-loaf_c.png" alt="Golden Signature Loaf with a crisp crust">
        <figcaption>The Signature Loaf, one of our bakery favorites.</figcaption>
      </figure>
    </section>
    <section aria-labelledby="behind-scenes">
      <h2 id="behind-scenes">Behind the scenes</h2>
      <video controls width="640" poster="bakery-storefront_c.png">
        <source src="bakery-behind-scenes_c.mp4" type="video/mp4">
        Your browser does not support HTML video. Please visit the bakery to see our bakers at work.
      </video>
    </section>
  </main>
  <footer class="site-footer">
    <p>North Star Bakery | Baked with care, shared with neighbors.</p>
    <p><a href="contact.html">Contact us</a></p>
  </footer>
</body>
</html>

<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Our Products | North Star Bakery</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header class="site-header">
    <a class="brand" href="index.html" aria-label="North Star Bakery home">
      <img src="bakery-logo_c.png" alt="North Star Bakery">
    </a>
    <p class="tagline">Good mornings begin at the bakery.</p>
    <nav class="site-nav" aria-label="Main navigation">
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="products.html" aria-current="page">Our products</a></li>
        <li><a href="about.html">Our story</a></li>
        <li><a href="contact.html">Contact and pre-orders</a></li>
        <li><a href="media.html">Media</a></li>
      </ul>
    </nav>
  </header>
  <main>
    <h1>From the oven to your table</h1>
    <p>Our selection changes with the seasons and the rhythm of the ovens. Here are a few neighborhood favorites; availability can vary by day.</p>
    <section aria-labelledby="breads">
      <h2 id="breads">Breads</h2>
      <img src="bakery-bread_c.png" alt="A fresh selection of artisan bakery bread">
      <p>Slow-fermented loaves with crisp crusts and soft, flavorful middles. Great for toast, sandwiches, and sharing at dinner.</p>
      <p>Typical range: $5-$12 per loaf.</p>
      <figure>
        <img src="bakery-signature-loaf_c.png" alt="North Star Bakery's golden Signature Loaf, just out of the oven">
        <figcaption>Our Signature Loaf: a deeply golden crust and a tender, airy crumb.</figcaption>
      </figure>
    </section>
    <section aria-labelledby="pastries">
      <h2 id="pastries">Pastries</h2>
      <p>Buttery morning pastries and small treats, baked in batches throughout the day. Ask what's warm when you visit.</p>
      <p>Typical range: $3-$7 each.</p>
    </section>
    <section aria-labelledby="cakes">
      <h2 id="cakes">Cakes and celebration bakes</h2>
      <p>Simple, generous cakes for birthdays, family tables, and milestones. Share your date and ideas with us, and we'll talk through the details.</p>
      <p>Typical range: $28-$65, depending on size and finish.</p>
      <p><a href="contact.html">Ask about a cake or pre-order</a></p>
    </section>
  </main>
  <footer class="site-footer">
    <p>North Star Bakery | Baked with care, shared with neighbors.</p>
    <p><a href="contact.html">Contact us</a></p>
  </footer>
</body>
</html>

# -Clary_Ryan_TouchstoneTask2
This repository contains a small static website for North Star Bakery.
Open `index.html` in a browser to view the home page, or browse the additional pages:
- `products.html`
- `about.html`
- `contact.html`
- `media.html`
All pages share `styles.css`, which uses a mobile-first Flexbox layout and adjusts at wider screen sizes. See `design-explanation.md` for the palette, typography, responsive behavior, and design rationale.


:root {
  color-scheme: light;
  --cream: #fff6e8;
  --ink: #30241e;
  --terracotta: #80391f;
  --wheat: #e9cda3;
  --content-width: 72rem;
  --shadow: 0 0.6rem 1.8rem rgb(48 36 30 / 9%);
}
* {
  box-sizing: border-box;
}
html {
  scroll-behavior: smooth;
}
body {
  display: flex;
  min-height: 100vh;
  flex-direction: column;
  margin: 0;
  background: var(--cream);
  color: var(--ink);
  font-family: Georgia, "Times New Roman", serif;
  font-size: 1rem;
  line-height: 1.65;
}
a {
  color: var(--terracotta);
  font-weight: 700;
  text-underline-offset: 0.2em;
}
a:hover {
  text-decoration-thickness: 0.15em;
}
a:focus-visible,
button:focus-visible,
input:focus-visible,
select:focus-visible,
textarea:focus-visible {
  outline: 0.2rem solid var(--terracotta);
  outline-offset: 0.2rem;
}
.site-header {
  padding: 1.25rem clamp(1rem, 5vw, 3rem);
  border-bottom: 0.25rem solid var(--wheat);
  background: var(--wheat);
  text-align: center;
}
.brand {
  display: inline-flex;
  align-items: center;
  justify-content: center;
}
.brand img,
.site-header > a img {
  display: block;
  width: min(100%, 14rem);
  height: auto;
  border-radius: 0.75rem;
}
.tagline {
  margin: 0.5rem 0 1rem;
  font-size: 1.1rem;
  font-style: italic;
}
.site-nav ul {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 0.4rem;
  margin: 0;
  padding: 0;
  list-style: none;
}
.site-nav a {
  display: inline-block;
  padding: 0.55rem 0.85rem;
  border-radius: 999px;
  color: var(--ink);
  text-decoration: none;
}
.site-nav a[aria-current="page"],
.site-nav a:hover {
  background: var(--terracotta);
  color: var(--cream);
}
main {
  display: flex;
  width: min(100% - 2rem, var(--content-width));
  flex: 1;
  flex-wrap: wrap;
  align-content: flex-start;
  align-items: stretch;
  gap: 1.25rem;
  margin: 0 auto;
  padding: 2rem 0 3rem;
}
main > h1,
main > p {
  flex: 0 0 100%;
}
h1,
h2,
h3 {
  color: var(--terracotta);
  font-family: Arial, Helvetica, sans-serif;
  line-height: 1.2;
}
h1 {
  margin: 0;
  font-size: clamp(2rem, 7vw, 3.25rem);
}
h2 {
  margin: 0 0 0.75rem;
  font-size: clamp(1.35rem, 4vw, 1.8rem);
}
main > p:first-of-type {
  max-width: 68ch;
  margin: -0.5rem 0 0.25rem;
  font-size: 1.1rem;
}
main > section {
  display: flex;
  min-width: 0;
  flex: 1 1 100%;
  flex-direction: column;
  align-items: flex-start;
  padding: clamp(1.15rem, 3vw, 1.75rem);
  border: 1px solid var(--wheat);
  border-radius: 1rem;
  background: var(--cream);
  box-shadow: var(--shadow);
}
main > section > :last-child {
  margin-bottom: 0;
}
img,
video,
audio {
  max-width: 100%;
}
main > section > img,
figure img,
main > section picture,
main > section picture img {
  display: block;
  width: 100%;
  height: auto;
}
main > section > img,
figure img,
main > section picture img {
  border-radius: 0.65rem;
}
figure {
  width: 100%;
  margin: 1rem 0 0;
}
figcaption {
  margin-top: 0.5rem;
  font-style: italic;
}
dl {
  width: 100%;
  margin: 0;
}
dt {
  margin-top: 1rem;
  color: var(--terracotta);
}
dt:first-child {
  margin-top: 0;
}
dd {
  margin: 0.25rem 0 0;
}
video,
audio {
  display: block;
  width: 100%;
  border-radius: 0.65rem;
}
form {
  width: 100%;
}
fieldset {
  min-width: 0;
  margin: 0 0 1.25rem;
  padding: 1rem;
  border: 1px solid var(--wheat);
  border-radius: 0.75rem;
}
legend {
  padding: 0 0.35rem;
  color: var(--terracotta);
  font-family: Arial, Helvetica, sans-serif;
  font-weight: 700;
}
label {
  display: block;
  margin-bottom: 0.35rem;
  font-weight: 700;
}
input,
select,
textarea {
  width: 100%;
  min-height: 2.8rem;
  padding: 0.65rem 0.75rem;
  border: 1px solid var(--ink);
  border-radius: 0.45rem;
  background: var(--cream);
  color: var(--ink);
  font: inherit;
}
textarea {
  min-height: 7rem;
  resize: vertical;
}
button {
  min-height: 2.8rem;
  padding: 0.65rem 1.1rem;
  border: 2px solid var(--terracotta);
  border-radius: 999px;
  background: var(--terracotta);
  color: var(--cream);
  cursor: pointer;
  font: inherit;
  font-weight: 700;
}
button:hover {
  background: var(--ink);
  border-color: var(--ink);
}
.site-footer {
  padding: 1.25rem 1rem;
  background: var(--ink);
  color: var(--cream);
  text-align: center;
}
.site-footer p {
  margin: 0.25rem;
}
.site-footer a {
  color: var(--wheat);
}
@media (min-width: 48rem) {
  .site-header {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: space-between;
    gap: 0.5rem 2rem;
    text-align: left;
  }
  .tagline {
    flex: 1;
    margin: 0;
  }
  .site-nav {
    flex: 0 0 100%;
  }
  .site-nav ul {
    justify-content: flex-start;
  }
  main {
    gap: 1.5rem;
    padding-top: 3rem;
  }
  main > section {
    flex-basis: calc(50% - 0.75rem);
  }
  .media-gallery {
    flex-direction: row;
    flex-wrap: wrap;
    gap: 1rem;
  }
  .media-gallery h2 {
    flex: 0 0 100%;
  }
  .media-gallery figure {
    flex: 1 1 12rem;
    margin: 0;
  }
}
@media (min-width: 72rem) {
  main > section {
    flex-basis: calc(33.333% - 1rem);
  }
}
@media (prefers-reduced-motion: reduce) {
  html {
    scroll-behavior: auto;
  }
}

