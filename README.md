# 🏆 Challenge 3 - "Text In Transit" 🔤

The challenge is to build a fixed-width, right-to-left text scroller capable of taking a string parameter and screen width as inputs. Seems simple, right?

### Rewards:

4️⃣ Points are awarded for a working text scroller demonstrated in either a console window or web app.

2️⃣ Further points are awarded for supporting sections of bold and underlined text (see examples)

2️⃣ Further points are awarded for supporting sections of coloured text (see examples)

1️⃣ Further point is awarded for supporting some kind of 'speed' input (e.g. characters per second)

1️⃣ Further point is awarded for supporting nested formatting (e.g. bold, underlined, coloured text (see example)).

### Examples:

```
scroll(text: "Welcome on board this service to [B]London[/B]. Please have [U]all[/U] tickets and passes ready for inspection. This service is expected to depart [C:#00FF00]on time[/C]", screenWidth: 10, speed: 2)
```

```
scroll(text: "[C:#FF0000]All of this text is Red, but [C:#0000FF][B][U]THIS[/U][/B] text is Blue.[/C][/C]", screenWidth: 8, speed: 4)
```

```
[  "          ",  "         G",  "        Go",  "       Goo",  "      Good",  "     Good ",  "    Good l",  "   Good lu",  "  Good luc",  " Good luck",  "ood luck ",  "od luck  ",  "d luck   ",  "luck     ",  "uck      ",  "ck       ",  "k        ",  "         ",]
```
