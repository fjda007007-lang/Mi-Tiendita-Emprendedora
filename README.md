# Mi-Tiendita-Emprendedora
Acá podras encontrar todo lo que debes saber para empezar tu primer negocio.
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Tienda Digital - Productos Digitales</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f4f4f4; }
        header { background-color: #333; color: white; text-align: center; padding: 20px; }
        .container { max-width: 1200px; margin: 20px auto; padding: 20px; background: white; border-radius: 8px; box-shadow: 0 0 10px rgba(0,0,0,0.1); }
        .product { display: inline-block; width: 30%; margin: 10px; text-align: center; vertical-align: top; }
        .product img { width: 100%; height: 200px; object-fit: cover; border-radius: 8px; }
        .combo { text-align: center; margin-top: 40px; padding: 20px; background-color: #e0e0e0; border-radius: 8px; }
        button { background-color: #28a745; color: white; border: none; padding: 10px 20px; cursor: pointer; border-radius: 5px; font-size: 16px; }
        button:hover { background-color: #218838; }
        footer { text-align: center; padding: 10px; background-color: #333; color: white; margin-top: 20px; }
    </style>
</head>
<body>
    <header>
        <h1>Mi Tienda Digital</h1>
        <p>Vende tus productos digitales de manera fácil y gratuita.</p>
    </header>
    
    <div class="container">
        <h2>Productos Disponibles</h2>
        
        <!-- Producto 1 -->
        <div class="product">
            <img src="https://via.placeholder.com/300x200?text=Producto+1" alt="Producto 1">
            <h3>Producto 1</h3>
            <p>Descripción breve del producto digital 1. Ideal para [uso].</p>
            <p>Precio: $10 USD</p>
            <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
                <input type="hidden" name="cmd" value="_xclick">
                <input type="hidden" name="business" value="tu-email@paypal.com"> <!-- Reemplaza con tu email de PayPal -->
                <input type="hidden" name="item_name" value="Producto 1">
                <input type="hidden" name="amount" value="10.00">
                <input type="hidden" name="currency_code" value="USD">
                <button type="submit">Comprar Producto 1</button>
            </form>
        </div>
        
        <!-- Producto 2 -->
        <div class="product">
            <img src="https://via.placeholder.com/300x200?text=Producto+2" alt="Producto 2">
            <h3>Producto 2</h3>
            <p>Descripción breve del producto digital 2. Perfecto para [uso].</p>
            <p>Precio: $15 USD</p>
            <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
                <input type="hidden" name="cmd" value="_xclick">
                <input type="hidden" name="business" value="tu-email@paypal.com"> <!-- Reemplaza con tu email de PayPal -->
                <input type="hidden" name="item_name" value="Producto 2">
                <input type="hidden" name="amount" value="15.00">
                <input type="hidden" name="currency_code" value="USD">
                <button type="submit">Comprar Producto 2</button>
            </form>
        </div>
        
        <!-- Producto 3 -->
        <div class="product">
            <img src="https://via.placeholder.com/300x200?text=Producto+3" alt="Producto 3">
            <h3>Producto 3</h3>
            <p>Descripción breve del producto digital 3. Excelente para [uso].</p>
            <p>Precio: $20 USD</p>
            <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
                <input type="hidden" name="cmd" value="_xclick">
                <input type="hidden" name="business" value="tu-email@paypal.com"> <!-- Reemplaza con tu email de PayPal -->
                <input type="hidden" name="item_name" value="Producto 3">
                <input type="hidden" name="amount" value="20.00">
                <input type="hidden" name="currency_code" value="USD">
                <button type="submit">Comprar Producto 3</button>
            </form>
        </div>
        
        <!-- Combo de los tres -->
        <div class="combo">
            <h3>Combo Especial: Los Tres Productos</h3>
            <p>Compra los tres productos juntos y ahorra $10. Precio total: $35 USD (en lugar de $45).</p>
            <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
                <input type="hidden" name="cmd" value="_xclick">
                <input type="hidden" name="business" value="tu-email@paypal.com"> <!-- Reemplaza con tu email de PayPal -->
                <input type="hidden" name="item_name" value="Combo: Producto 1, 2 y 3">
                <input type="hidden" name="amount" value="35.00">
                <input type="hidden" name="currency_code" value="USD">
                <button type="submit">Comprar Combo</button>
            </form>
        </div>
    </div>
    
    <footer>
        <p>&copy; 2023 Mi Tienda Digital. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
