Feel free to play around with this example, and don't be afraid to break it.

Here's the original code if desired.

HTML:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>CSS Cards Example</title>
    <link href="styles.css" rel="stylesheet" />
  </head>
  <body>
    <section class="menu">
      <h2>Entrées</h2>
      <div class="card">
        <img src="assets/images/bacon-pub-burger.jpg" />
        <h3>Bacon Pub Burger</h3>
        <p class="card-number">Card 1.</p>
        <p>What a beast of a burger.</p>
        <p class="price">$17.99</p>
      </div>
      <div class="card">
        <img src="assets/images/fish-and-chips.jpg" />
        <h3>Fish & Chips</h3>
        <p class="card-number">Card 2.</p>
        <p>Such fish. Many chips.</p>
        <p class="price">$14.99</p>
      </div>
      <div class="card">
        <img src="assets/images/tacos-de-carnitas.jpg" />
        <h3>Tacos de Carnitas</h3>
        <p class="card-number">Card 3.</p>
        <p>Mucho gusto, mi taco pequeñito.</p>
        <p class="price">$12.99</p>
      </div>
    </section>
  </body>
</html>


```

CSS:

```
/* at some sizes this will break because of how the box model interacts with the page - don't worry, we'll learn to solve that on day 5 */

h2 {
    text-align: center;
    font-size: 3.5rem;
    color: #e43;
}

.menu {
    text-align: center;
}

.card {
    padding: 0 0 20px;
    margin: 1rem;
    border: 1px solid #212;
    font-size: 1.3rem;
    border-radius: 10px;
    background-color: #edf45a;
    color: #212;
    text-align: center;
    display: inline-block;
    max-width: 28%;
}

.card img {
    max-width: 100%;
    border-radius: 5px 5px 0 0;
}

.card h3 {
    color: #e21;
}

.card-number {
    font-weight: bold;
}

.price {
    color: #e21;
    font-weight: bold;
}
```