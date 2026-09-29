# Демонстрация форматирования в C#
Код программы сохранен в файле `FormatDemo.cs`.

```csharp
// Жирный текст в комментарии
// Курсивный текст
// Жирный курсив
// Зачеркнутый текст
// Использование Console.ReadLine() для ввода
using System;
class FormatDemo {
static void Main() {
Console.Write("Введите первое число: ");
double number1 = Convert.ToDouble(Console.ReadLine());
Console.Write("Введите второе число: ");
double number2 = Convert.ToDouble(Console.ReadLine());
double sum = number1 + number2;
Console.WriteLine($"Результат операции: {sum}");
}
}```