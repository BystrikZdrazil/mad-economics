---
{"dg-publish":true,"permalink":"/02-programming/c-sharp/switch/"}
---

Switch is used for checking for [[02 - Programming/C-SHARP/If statements and conditions\|comparisons]] against multiple possible cases. Normally, we could do it like this:

```Cpp
string name = "Aramin";
if (name == "Aramin")
{
	Console.WriteLine("Hello Aramin!");
}

string name = "Joe";
if (name == "Joe")
{
	Console.WriteLine("Hello Joe!");
}

string name = "Denis";
if (name == "Denis")
{
	Console.WriteLine("Hello Denis!");
}
```

This is good but not that efficient. A better way is using **switch**

```Cpp
switch (name)
{
	case "Aramin":
		Console.WriteLine("Hello Aramin!");
		break;
	case "Joe":
		Console.WriteLine("Hello Joe!");
		break;
	case "Denis":
		Console.WriteLine("Hello Denis!");
		break;
	case default: // default is run when there is no match
		Console.WriteLine("Hello stranger!");
		break;
}
```

When we want some code to execute when there is no match we can use the **default** case. The default case runs **each time there is no match** inside the case. If there is no default in a case nothing will be executed (it will be "skipped")
By not inserting any code and a break after a case, multiple cases can have the same outcome

```Cpp
switch (name)
{
	case "Aramin":
	case "Denis":
	case "Litacka":
		Console.WriteLine("You practise karate");
		break;
}
```