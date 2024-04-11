using System;

// Модуль Auth
public class AuthModule
{
    public bool Authenticate(string username, string password)
    {
        // Логіка аутентифікації користувача
        return true; // чи false, залежно від успішності
    }
}

// Модуль Users
public class UsersModule
{
    public void CreateUser(string username, string password)
    {
        // Логіка створення користувача
    }

    public void GetUserDetails(string username)
    {
        // Логіка отримання даних користувача
    }
}

// Модуль Subscriptions
public class SubscriptionsModule
{
    public void SubscribeUser(string username, string subscriptionType)
    {
        // Логіка підписки користувача на певний тип послуги
    }

    public void GetSubscriptionDetails(string username)
    {
        // Логіка отримання деталей підписки користувача
    }
}

// Головний клас програми
class Program
{
    static void Main(string[] args)
    {
        // Ініціалізація модулів
        AuthModule authModule = new AuthModule();
        UsersModule usersModule = new UsersModule();
        SubscriptionsModule subscriptionsModule = new SubscriptionsModule();

        // Сценарій користувача: аутентифікація та взаємодія з іншими модулями
        Console.WriteLine("Введіть ваш логін:");
        string username = Console.ReadLine();
        Console.WriteLine("Введіть ваш пароль:");
        string password = Console.ReadLine();

        if (authModule.Authenticate(username, password))
        {
            Console.WriteLine("Аутентифікація успішна!");

            // Діаграма взаємодії між модулями:
            // Від Auth до Users
            usersModule.GetUserDetails(username);

            // Від Auth до Subscriptions
            subscriptionsModule.GetSubscriptionDetails(username);

            // Додаткові операції користувача тут...
        }
        else
        {
            Console.WriteLine("Помилка аутентифікації. Невірний логін або пароль.");
        }
    }
}
