Amigo Secreto - Aplicación JavaScript 🎁

📋 Descripción
Esta aplicación simple de JavaScript permite crear una lista de amigos y sortear aleatoriamente un "amigo secreto" entre los participantes agregados.

👨‍💻 Autor
Desarrollado por: Abdiel Bernal

GitHub: 2apty507

Instagram: 2apty

🛠️ Funcionalidades
1. agregarAmigo()
Esta función permite añadir nombres a la lista de amigos:

Funcionamiento:
Limpia cualquier mensaje de resultado previo
Obtiene el valor del campo de entrada
Valida que el campo no esté vacío
Crea un nuevo elemento <li> con el nombre ingresado
Añade el elemento a la lista en el DOM
Limpia el campo de entrada para el siguiente nombre.

2. sortearAmigo()
Esta función realiza el sorteo aleatorio:

Funcionamiento:
Convierte los elementos de la lista en un array de nombres
Genera un número aleatorio dentro del rango de la lista
Selecciona un nombre al azar usando el índice generado
Muestra el resultado del sorteo en el elemento designado
Limpia la lista de amigos y el campo de entrada

💡 Características técnicas
Manipulación del DOM para agregar y eliminar elementos
Uso de Math.random() para la selección aleatoria
Conversión de elementos HTML a array mediante Array.from()
Implementación de validación básica de entrada

🚀 Uso
Ingresa nombres en el campo de texto
Haz clic en el botón para agregar amigos a la lista
Cuando todos los participantes estén agregados, haz clic en el botón de sorteo
El resultado mostrará el nombre del amigo secreto seleccionado
