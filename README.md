<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF8">
        <meta name="viewpoert" content="width=device-width, initial-scale=1.0">
        <title>Membuat Kalkulator Sederhana</title>
        <link rel="stylesheet" href="style.css">
    </head>

    <body>
        <div class="calculator">
            <input type="text" class="calculator-screen" value="" disabled />
            <div class="calculator-keys">
                <button type="button" class="operator" value="+">+</button>
                <button type="button" class="operator" value="-">-</button>
                <button type="button" class="operator" value="*">&times;</button>
                <button type="button" class="operator" value="/">&divide;</button>
                <button type="button" class="operator" value="Sin">Sin</button>
                <button type="button" class="operator" value="Cos">Cos</button>
                <button type="button" class="operator" value="Tan">Tan</button>
                <button type="button" value="7">7</button>
                <button type="button" value="8">8</button>
                <button type="button" value="9">9</button>
                <button type="button" value="4">4</button>
                <button type="button" value="5">5</button>
                <button type="button" value="6">6</button>
                <button type="button" value="1">1</button>
                <button type="button" value="2">2</button>
                <button type="button" value="3">3</button>
                <button type="button" value="0">0</button>
                <button type="button" class="decimal" value=".">.</button>
                <button type="button" class="all-clear" value="all-clear">AC</button>
                <button type="button" class="equal-sign operator" value="=">=</button>
            </div>
        </div>
        <script src="script.js"></script>
    </body>
</html>
