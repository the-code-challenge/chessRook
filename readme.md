# Code Challenge: ChessRook

Digamos que estamos colaborando en el desarrollo de un juego de ajedrez online y debemos validar el movimiento de un usuario sobre su torre.

Dada la posición de la torre (parámetro 1) y la posición destino que elegió el usuario (parametro 2) validar si el movimiento es valido. Se debe retornar **true** si el movimiento es valido o **false** si es invalido. 

### Moviemiento de la torre
La torre tiene la característica de moverse de forma recta a traves de todo el tablero
![Moviemiento Torre](https://firebasestorage.googleapis.com/v0/b/fullstack-extraordinary.appspot.com/o/TheCodeChallenge%2Fmovimiento_de_torre_ajedrez.png?alt=media&token=14261bcc-f992-4c6a-8d16-5332f3a49c53)

### Coordenadas en tablero de Ajedrez
La posición de una pieza en el tablero de ajedrez se identifica mediante una coordenada alfanumérica.   
- El eje horizontal o eje X se identifica con una letra entre la "A" y la "H" (A,B,C,D,E,F,G,H)  
- El eje vertical o eje Y se identiica con un numero entre el "1" y el "8" (1,2,3,4,5,6,7,8)  

Por ejemplo: "A1", "G7", "F3"  

![Tablero Ajedrez](https://firebasestorage.googleapis.com/v0/b/fullstack-extraordinary.appspot.com/o/TheCodeChallenge%2FtablerAjedrez.jpg?alt=media&token=8864816b-a981-4541-a203-a9dd69fe37a1)

## Instrucciones
- Crear un nuevo repositorio utilizando este repositorio como template (Boton: use this template).
- Editar el código de la función definida en el archivo index.js con un algoritmo que permita obtener los resultados esperados en los test.
- Ejecutar los test validando que todos resulten exitosos

## Ejecutar Pruebas

Instalar dependencias (mocha)
```
npm install
```

Ejecutar test
```
npm run test
```
## Entrada

##### Parámetro 1
- **nombre**: num
- **tipo**: Number (Integer)
- **limitaciones**: 0 < **num** <= 10

## Salida

- **tipo**: Number (Integer)

## Ejemplo
**1** debe retornar **1** porque: 1 == 1

## Tests

### Test 1  

- **Parametros**: param = 1  
- **Resultado esperado**: xxx
---
### Test 2  

- **Parametros**:  param = 2  
- **Resultado esperado**: xxx
---
### Test 3  

- **Parametros**: param = 3  
- **Resultado esperado**: xxx
