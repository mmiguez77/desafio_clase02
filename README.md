# desafio_clase02
Principios de Programación en Javascript y ES6

1) Declarar una función constructora llamada Usuario que reciba: nombre (string), apellido(string), libros (array de objetos) y mascotas (array de objetos).
Implementar las propiedades instancia desde los valores recibidos como argumento y los siguiente metodos en su prototipo.
getFullName: debe retornar un string con el nombre y apellido del usuario (utilizar templete string).
addMascota: debe agregar una mascota (mascota) al arreglo de mascotas del usuario. No debe retornar nada.
getMascotas: debe retornar la cantidad de mascotas que tiene el usuario.
addBook: recibe un string 'book' y un string 'autor' y debe agregar un objeto: {nombre:book, autor:autor} al arreglo de libros del usuario. No debe retornar nada.
getBooks: de retornar un arreglo con sólo los nombres del arreglo de libros del usuario.
Crear un objeto llamado usuario a partir de la función constructora, con valores que permitan probar todos sus métodos. Hacer el test completo empleando la consola del navegador.

2) Realizar todo lo anterior utilizando el contructor class de ES6.
