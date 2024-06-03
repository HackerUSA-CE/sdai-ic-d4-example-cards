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
        <img
          src="https://images.unsplash.com/photo-1619810816144-68dbc1f695e8?q=80&w=1470&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" />
        <h3>Bacon Pub Burger</h3>
        <p>Card 1. What a beast of a burger.</p>
        <p class="price">$17.99</p>
      </div>
      <div class="card">
        <img
          src="https://images.unsplash.com/photo-1621273581667-a3f76f4a3bca?q=80&w=1470&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" />
        <h3>Fish & Chips</h3>
        <p>Card 2. Such fish. Many chips.</p>
        <p class="price">$14.99</p>
      </div>
      <div class="card">
        <img
          src="https://images.unsplash.com/photo-1619221882161-95135fca04e4?q=80&w=1470&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" />
        <h3>Tacos al Pastor</h3>
        <p>Card 3. Mucho gusto, mi taco pequeñito.</p>
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

.card h3 {
    color: #e21;
}

.card img {
    max-width: 100%;
    border-radius: 5px 5px 0 0;
}

.price {
    color: #e21;
    font-weight: bold;
}
```