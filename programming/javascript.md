# JavaScript

## Random Hex Color

Source: https://css-tricks.com/snippets/javascript/random-hex-color/

    const randomColor = Math.floor(Math.random()*16777215).toString(16);


## Random Int with Min/Max

Source: https://stackoverflow.com/a/7228322

    const randomNumber = (min, max) => Math.floor(Math.random() * (max - min + 1) + min);

## Create Quick Array of Objects

    const arr = Array.from({ length: 5 }, (v, i) => ({ i }));

    // [{"i":0},{"i":1},{"i":2},{"i":3},{"i":4}]
    
