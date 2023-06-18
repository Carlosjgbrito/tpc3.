## Calculadora

Este é o código JavaScript para uma calculadora simples.

### HTML

O código HTML define a estrutura da calculadora e inclui os elementos necessários para exibir os operandos e os botões de operação.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Calculadora</title>
    <link rel="stylesheet" href="styles.css" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap"
      rel="stylesheet"
    />
  </head>
  <body>
    <div class="grid-container">
      <div class="output">
        <div data-previous-operand class="previous-operand"></div>
        <div data-current-operand class="current-operand"></div>
      </div>
      <button data-all-clear class="span-two">AC</button>
      <button data-delete>DEL</button>
      <button data-operator class="operator">÷</button>
      <button data-number>1</button>
      <button data-number>2</button>
      <button data-number>3</button>
      <button data-operator class="operator">*</button>
      <button data-number>4</button>
      <button data-number>5</button>
      <button data-number>6</button>
      <button data-operator class="operator">+</button>
      <button data-number>7</button>
      <button data-number>8</button>
      <button data-number>9</button>
      <button data-operator class="operator">-</button>
      <button data-number class="span-two">.</button>
      <button data-number>0</button>
      <button data-equals class="operator">=</button>
    </div>
    <script src="scripts.js"></script>
  </body>
</html>
# tpc3.
calculadora
