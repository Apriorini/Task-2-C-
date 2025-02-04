# Task-2-C

Console.InputEncoding = System.Text.Encoding.GetEncoding("UTF-16"); // Это взял с хабра когда пытался понять почему кирилицу не принимает https://qna.habr.com/q/1160590
Console.WriteLine("Как вас зовут?");
string a = Console.ReadLine();
Console.WriteLine("Какая ваша фамилия?");
string b = Console.ReadLine();
Console.WriteLine("Введите День Вашего Рождения");
string c = Console.ReadLine();
int d = Convert.ToInt32(c);
Console.WriteLine("Введите номер месяца вашего Рождения");
string x = Console.ReadLine();
Console.WriteLine($"Вас зовут: {a}");
Console.WriteLine($"Ваша Фамилия: {b}");
switch (x)
{
    case "1":
        if (d <= 20 && d > 0)
        {
            Console.WriteLine("Вы козерог");
        }
        else if (d > 20 && d < 32)
        {
            Console.WriteLine("Вы Водолей");
        }
        else
        {
            Console.WriteLine("Неправильный день рождения, попробуйте еще раз");
        }
        break;
    case "2":
        if (d <= 20 && d > 0)
        {
            Console.WriteLine("Вы Водолей");
        }
        else if (d > 20 && d < 30)
        {
            Console.WriteLine("Вы Рыбы");
        }
        else
        {
            Console.WriteLine("Неправильный день рождения, попробуйте еще раз");
        }
        break;
    case "3":
        if (d <= 20 && d > 0)
        {
            Console.WriteLine("Вы Рыбы");
        }
        else if (d > 20 && d < 32)
        {
            Console.WriteLine("Вы Овен");
        }
        else
        {
            Console.WriteLine("Неправильный день рождения, попробуйте еще раз");
        }
        break;
    case "4":
        if (d <= 20 && d > 0)
        {
            Console.WriteLine("Вы Овен");
        }
        else if (d > 20 && d < 31)
        {
            Console.WriteLine("Вы Телец");
        }
        else
        {
            Console.WriteLine("Неправильный день рождения, попробуйте еще раз");
        }
        break;
    case "5":
        if (d <= 20 && d > 0)
        {
            Console.WriteLine("Вы Телец");
        }
        else if (d > 20 && d < 30)
        {
            Console.WriteLine("Вы близнецы");
        }
        else
        {
            Console.WriteLine("Неправильный день рождения, попробуйте еще раз");
        }
        break;
    case "6":
        if (d <= 21 && d > 0)
        {
            Console.WriteLine("Вы Близнецы");
        }
        else if (d > 21 && d < 30)
        {
            Console.WriteLine("Вы Рак");
        }
        else
        {
            Console.WriteLine("Неправильный день рождения, попробуйте еще раз");
        }
        break;
    case "7":
        if (d <= 22 && d > 0)
        {
            Console.WriteLine("Вы Рак");
        }
        else if (d > 22 && d < 30)
        {
            Console.WriteLine("Вы Лев");
        }
        else
        {
            Console.WriteLine("Неправильный день рождения, попробуйте еще раз");
        }
        break;
    case "8":
        if (d <= 23 && d > 0)
        {
            Console.WriteLine("Вы Лев");
        }
        else if (d > 23 && d < 30)
        {
            Console.WriteLine("Вы Дева");
        }
        else
        {
            Console.WriteLine("Неправильный день рождения, попробуйте еще раз");
        }
        break;
    case "9":
        if (d <= 23 && d > 0)
        {
            Console.WriteLine("Вы Дева");
        }
        else if (d > 23 && d < 30)
        {
            Console.WriteLine("Вы Весы");
        }
        else
        {
            Console.WriteLine("Неправильный день рождения, попробуйте еще раз");
        }
        break;
    case "10":
        if (d <= 23 && d > 0)
        {
            Console.WriteLine("Вы Весы");
        }
        else if (d > 23 && d < 30)
        {
            Console.WriteLine("Вы Скорпион");
        }
        else
        {
            Console.WriteLine("Неправильный день рождения, попробуйте еще раз");
        }
        break;
    case "11":
        if (d <= 23 && d > 0)
        {
            Console.WriteLine("Вы Скорпион");
        }
        else if (d > 23 && d < 30)
        {
            Console.WriteLine("Вы Стрелец");
        }
        else
        {
            Console.WriteLine("Неправильный день рождения, попробуйте еще раз");
        }
        break;
    case "12":
        if (d <= 22 && d > 0)
        {
            Console.WriteLine("Вы Стрелец");
        }
        else if (d > 22 && d < 30)
        {
            Console.WriteLine("Вы Козерог");
        }
        else
        {
            Console.WriteLine("Неправильный день рождения, попробуйте еще раз");
        }
        break;
    default:
        Console.WriteLine("Знак Зодиака не определен");
        break;
}
