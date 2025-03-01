<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>E-Commerce PWA</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to Our E-Commerce Store</h1>
    </header>
    <main>
        <section class="product-list">
            <article class="product">
                <img src="S.jpg" alt="Product 1">
                <h2>Product 1</h2>
                <p>Price: $10</p>
            </article>
            <article class="product">
                <img src="W.jpg" alt="Product 2">
                <h2>Product 2</h2>
                <p>Price: $20</p>
            </article>
            <!-- Add more products as needed -->
        </section>
    </main>
    <script src="service-worker.js"></script>
</body>
</html># Progressive-web-Application

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}

header {
    background-color: #f8f9fa;
    padding: 1rem;
    width: 100%;
    text-align: center;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

main {
    padding: 1rem;
    max-width: 1200px;
    width: 100%;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
}

.product-list {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}

.product {
    border: 1px solid #ccc;
    border-radius: 8px;
    margin: 0.5rem;
    padding: 1rem;
    text-align: center;
    width: 200px;
}

.product img {
    max-width: 100%;
    height: auto;
    border-radius: 4px;
}

@media (max-width: 768px) {
    .product {
        width: 150px;
    }
}
