<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <nav>
      <div class="logo">SEND</div>
      <div class="nav-items">
        <a href="/">Home</a> <a href="/">About</a> <a href="/">Contact</a>
      </div>
    </nav>
    <section class="hero">
      <div class="hero-container">
        <div class="column-left">
          <h1>Send Unlimited Messages</h1>
          <p>
            No contracts or unwanted fees. Exclusive offer for new customers
            only.
          </p>
          <button>Get Started</button>
        </div>
        <div class="column-right">
          <img
            src="./image-1.svg"
            alt="illustration
        "
            class="hero-image"
          />
        </div>
      </div>
    </section>
  </body>
</html>


* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande',
    'Lucida Sans', Arial, sans-serif;
}

nav {
  height: 80px;
  background: #fdcc04;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0rem calc((100vw - 1300px) / 2);
}

.logo {
  color: #000;
  font-size: 1.5rem;
  font-weight: bold;
  font-style: italic;
  padding: 0 2rem;
}

nav a {
  text-decoration: none;
  color: #000;
  padding: 0 1.5rem;
}

nav a:hover {
  color: #fff;
}

.hero {
  background: #fdcc04;
}

.hero-container {
  display: grid;
  grid-template-columns: 1fr 1fr;
  height: 95vh;
  padding: 3rem calc((100vw - 1300px) / 2);
}

.column-left {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  color: #000;
  padding: 0rem 2rem;
}

.column-left h1 {
  margin-bottom: 1rem;
  font-size: 3rem;
}

.column-left p {
  margin-bottom: 2rem;
  font-size: 1.5rem;
  line-height: 1.5;
}

button {
  padding: 1rem 3rem;
  font-size: 1rem;
  border: none;
  color: #fdcc04;
  background: #000;
  cursor: pointer;
  border-radius: 50px;
}

button:hover {
  background: #fff;
  color: #000;
}

.column-right {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 0rem 2rem;
}

.hero-image {
  width: 100%;
  height: 100%;
}

@media screen and (max-width: 768px) {
  .hero-container {
    grid-template-columns: 1fr;
  }
}

}
  } end
