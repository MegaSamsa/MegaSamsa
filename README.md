```c#
// Hello.cs

public void About(Person me)
{
	me.TellAbout(me.Skills.First(x => x.Name == "C#").MainInfo);      // backend developer of web applications
	me.TellAbout(me.Skills.First(x => x.Name == "Python").MainInfo);  // developer of Telegram chatbots
}
```
