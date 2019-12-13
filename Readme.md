# Install

```bash
Install-Package ConsoleColorsExtension
# or
dotnet add package ConsoleColorsExtension
```

![Example](https://raw.githubusercontent.com/barnuri/colors-extension-js/master/ex.png)

# Use

```c#
using ConsoleColorsExtension;

public static void Main(string[] args)
{
    Console.WriteLine("text".ColorByNumber(30)); // equals, 30 = black in ansi colors
    Console.WriteLine("black".Black());
    Console.WriteLine("red".Red());
    Console.WriteLine("green".Green());
    Console.WriteLine("yellow".Yellow());
    Console.WriteLine("blue".Blue());
    Console.WriteLine("magenta".Magenta());
    Console.WriteLine("cyan".Cyan());
    Console.WriteLine("white".White());
    Console.WriteLine("blackBg".BlackBg());
    Console.WriteLine("redBg".RedBg());
    Console.WriteLine("greenBg".GreenBg());
    Console.WriteLine("yellowBg".YellowBg());
    Console.WriteLine("blueBg".BlueBg());
    Console.WriteLine("magentaBg".MagentaBg());
    Console.WriteLine("cyanBg".CyanBg());
    Console.WriteLine("whiteBg".WhiteBg());

    Console.WriteLine("you can merge foreground  color with background color".Black().YellowBg());
}
```
