# Aerolinea

> Generación de Boletos de Aerolínea

## Introduction

> Los boletos de avión para una aerolínea tienen un código específico dependiendo de 4 variables: 
    - El destino del vuelo.
    - La hora del vuelo.
    - El sexo del pasajero.
    - La comida que prefiere el pasajero y la tarifa del boleto.

> Las reglas que sigue el código de cada uno de los boletos 
    es la siguiente:

> Regla 1: 
    -  Los vuelos al Oceanía están codificados A.
    - Los vuelos a Europa están codificados B.
    - Los vuelos a Asia están codificados C.
    - A a las Américas D.
    
> Regla 2: 
    - Si un vuelo se lleva a cabo entre las 10 p.m. y las 6a.m. Se usa el mismo código .
    de la “Regla 1” pero con letras minúsculas (a, b, c y d).
    
> Regla 3: 
    - Los pasajeros varones se codifican X. 
    - Las mujeres se codifican como Y.
    - Los niños se codifican con las mismas letras en minúsculas (x - y).
    
> Regla 4: Las comidas están codificadas de la siguiente manera: 
    - Comida europea G.
    - Comida asiática H.
    - Comida vegetariana K.
    - Comidas infantiles codificadas con las mismas letras en minúsculas (g, h, k).

> Regla 5: 
    - Los pasajeros de primera clase están codificados como P.
    - Clase ejecutiva Q.
    - Clase económica R.

## Installation

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```