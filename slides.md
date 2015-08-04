# Javascript for non developers
## XOOM Code School // 2015-08-04
J. Jossemar Cordero R.

---

# ¿Quien es el expositor?

- Ingeniero de software*<!-- .element: class="fragment" -->
- Hackerpreneur<!-- .element: class="fragment" -->
- Developer, Infra structure, DevOps...<!-- .element: class="fragment" -->

---

<!-- .slide: data-background="#dd0000" -->

# Disclaimer

----

<!-- .slide: data-background="img/halpme.png" -->

----

<!-- .slide: data-background="#C10C06" -->
![Keep calm](img/keep-calm.png)<!-- .element: style="margin-top: -20px; border:none" -->

---

# Repaso

----

## Variables

----

<!-- .slide: data-background="img/box.jpg" -->

----

## Tipos de datos

- Interger
- Float
- String
- Boolean

----

## Tipos de datos "especiales"

- undefined
- null
- NaN

----

## Arreglos

----

<!-- .slide: data-background="img/row-boxes.jpg" -->

----

## Objectos / Maps

![Octopus](img/octopus_blocks.png)

----

## Ejercicio

```
Cree un script en el cual se solicite su nombre y apellido (por aparte), al igual
que su edad, luego escriba en consola "Hola soy {nombres} tengo {años} años y mis
apellidos son {apellidos}".
```

Tiempo: 10 minutos.

---

# Aprendiendo lo esencial
## Statements

----

<!-- .slide: data-background="img/talk-software.png" -->

---

# Expresiones

----

## Expresiones aritmeticas

```javascript
5 + 3 * 2 + Math.sqrt(1)
```

----

## Expresiones lógicas

```javascript
var1 > 5 && 7 < var1
```

----

## Operadores lógicos

- `< > <= >=`
- `== !=`
- `=== !==`
- `!`
- `&& ||`

---

# Instrucciones de decisión

----

## IF

```
SI hay otra persona en la habitación

	saludo

	SI la otra persona me da la mano
		yo le doy la mano
	SI NO
		no hago nada
	FIN SI

FIN SI
```

----

```javascript
if(cuarto.masPersonas()){
	yo.saludo()

	if(otraPersona.darMano()){
		yo.doyLaMano();
	} else {
		yo.noHagoNada();
	}
}
```

----

## SWITCH

```
SI me siento

	CON hambre
		como
	CON sueño
		duermo
	SIN animos
		no hago nada

FIN SI
```

----

```javascript
switch (yo.estado()) {
	case 'hambre':
		como();
		break;
	case 'sueño':
		duermo();
		break;
	default:
		noHagoNada();
}
```

---

# Instrucciones de control

----

## FOR

----

```
POR cada persona en salon
 	revisar ejercicio
FIN POR
```

----

```javascript
for (var contadorPersona = 0; contadorPersona < salon.length; contadorPersona++) {
	revisarEjercicio(salon[contadorPersona]);
}
```

----

## WHILE

----

```
MIENTRAS este vivo
 	como
	duermo
	rio
	hago algo mas
FIN MIENTRAS
```

----

```javascript
while (yo.esteVivo()) {
	como();
	duermo();
	rio();
	hagoAlgoMas();
}

do {
	como();
	duermo();
	rio();
	hagoAlgoMas()
} while (yo.esteVivo());
```

---

# Practicando

----

Escriba un script en el cual se solicite su nombre y apellido por aparte, al igual
que su edad, si su edad es mayor a 20 años muestre el nombre completo en el caso contrario
solo diga hola.

---

# ¿Dudas?
(Busquen los correos de los tutores en confluence)

---

# Gracias
