```c#
// AboutMe.cs

public void About(Developer me)
{
	foreach (var item in me.Skills)
		Console.WriteLine($"[{item.Name}] {item.Description}");

	// [C#] Backend-разработчик веб-приложений
	// [Python] Разработчик чат-ботов под Telegram
}
```
