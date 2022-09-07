# -using System;

namespace Создание_переменных
{
    class Program
    {
        static void Main(string[] args)
        {
            string bikeName = "Ducati SuperSport 950S";
            int bikeAge = 2;
            bool isWork = true;
            float tankVolume = 937f;
            double pistonStroke = 67.5;

            Console.WriteLine($"Название байка: {bikeName}");
            Console.WriteLine($"Возраст байка: {bikeAge}");
            Console.WriteLine($"Рабочий ли: {isWork}");
            Console.WriteLine($"Объем бака: {tankVolume}");
            Console.WriteLine($"Ход поршня: {pistonStroke}");

            Console.ReadLine();

            string name = "Alesha";
            int age = 12;
            bool isAlive = true;
            float weight = 43.3f;
            double growth = 151.3;

            Console.WriteLine($"Имя: {name}");
            Console.WriteLine($"Возраст: {age}");
            Console.WriteLine($"Жив ли: {isAlive}");
            Console.WriteLine($"Вес: {weight}");
            Console.WriteLine($"Рост: {growth}");
        }
    }
}
