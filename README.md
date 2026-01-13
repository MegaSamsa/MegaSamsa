```c#
// AboutMe.cs

public void About(Developer me)
{
	foreach (var item in me.Skills)
		Console.WriteLine($"[{item.Name}] {item.Description}");

	// [C#] backend developer of web applications
	// [Python] developer of Telegram chatbots
}
```
