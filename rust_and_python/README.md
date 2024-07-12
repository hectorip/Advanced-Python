# Usando Rust desde Python

El objetivo de este módulo es mostrarte cómo puedes usar módulos (o librerías, o progrmas) escritos
en Rust desde una interfaz de programación hecha en un módulo de Python.

Aunque nos estamos centrando en Rust, los principios generales son igualmente aplicacbles
a otros lenguajes de programación, sobre todo de más bajo nivel, como C o C++. La idea
es que tengas más control sobre el rendimiento sin sacrificar completamente la facilidad de uso.

## El módulo de Rust

El módulo de Rust que vamos a implementar es un caché LRU o "Least Recently Used".
Esta estructura de datos que guarda un número fijo de elementos y cuando se llena va
eliminando los elmentos usados menos recientemente. Una de sus características importantes
es que es muy eficiente en términos de acceso, con un costo promedio de O(1) para encontrar
una llave.
