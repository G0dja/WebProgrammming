#3. Напишіть функцію-конструктор
Об'єкт, який вона створює, має вміти таке:
Зберігати «поточне значення» як value. Початкове значення встановлюється в аргументі конструктора startingValue.
Метод read()використовує promptдля отримання числа та додає його до властивості value.

function Constructor(startingValue) {
  this.value = +startingValue
  this.read = () => {
    this.value = +prompt('Enter value:')
  }
}
