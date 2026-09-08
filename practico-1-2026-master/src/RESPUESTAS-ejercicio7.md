# Ejercicio 7 — `type` vs `interface`

> Este archivo no se corrige con tests automáticos: lo lee el docente.
> Respondé con tus palabras, en base a lo que probaste en `ej07-tipos-interfaces.ts`.

## ¿Qué permite hacer `interface` que `type` no (o no tan bien)?

_(tu respuesta)_
La interface sirve mas que nada para definir como va a ser un objeto y tambien se puede extender usando extends. Ademas si hacemos dos interfaces con el mismo nombre se pueden juntar cosa que con type no pasa.

## ¿Qué permite hacer `type` que `interface` no?

_(tu respuesta — pensá en uniones, tuplas, tipos primitivos con alias, mapped types)_
Con type se pueden hacer mas cosas como uniones tuplas o ponerle un nombre a tipos simples. Por ejemplo podemos hacer un tipo que sea string o number.

## ¿Ambas se pueden extender? ¿Cómo se hace en cada caso?

_(tu respuesta)_
Si las dos se pueden extender. Con interface se usa extends y con type se puede usar el & para juntar dos tipos.

## ¿Cuál elegirían para representar una entidad del dominio (por ejemplo, `Alumno`)? ¿Por qué?

_(tu respuesta)_
Para algo como Alumno usaria interface porque me parece mas simple para definir como es el objeto y si despues quiero agregarle mas cosas lo puedo extender. Usaria type mas cuando necesito hacer uniones o cosas un poco mas especificas.