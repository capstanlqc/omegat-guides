# 06. Special characters

!!! note inline end "←TODO"
Add link to the section in the guide.
You may insert special characters in different ways: autotext shortcut, character table, etc.

## Exercise 06.1: use a known autotext shortcut

You may use the autotext shortcut `\sub2` to insert a subscript number 2 (i.e. `₂`). Now you know! :)

!!! tip
    The "suB" part in the shorcut `\sub2` stands for subindex or subscript.


<!-- @todo: add "subindex" and "superindex" to cheatsheet -->

!!! note inline end "←TODO"
@quiz: what do you notice in segment #47 (@todo: complete)
1. Go to segment #47 and read the source text.

   > Target text reads `Le dioxyde de carbone (CO2) se dissout dans l'eau de mer pour former de l'acide carbonique.`

2. Delete number 2 in “CO2” (and keep the cursor right after "CO").

   > A subscript number should be used instead of a regular digit.

3. In that same position, type the autotext shortcut `\sub2`
3. Notice how the auto-completer window opens showing the autotext entry.
4. Press ++enter++ to insert the special character `₂`.

   > The result should be: `CO₂`

In this exercise you have used an autotext shortcut that you knew already. In the following exercises you'll find out an autotext entry that you don't know.


## Exercise 06.2: find special character in the list of autotext entries

In this exercise, you must insert the multiplication symbol but you don't know what autotext entry you can use.

1. Go to segment #52

   > Source text reads: `Thermal conductivity coefficient <br/>(W/m × K)`

2. Open the list of available shortcuts [here](../../misc/autotext/){:target="_blank"}.
3. Look for the autotext entry for the multiplication symbol.

   > You can use either `\times` or `\x` (how lucky, this one is shorter!)

4. Translate segment #52 as you like (don't forget the part in parentheses).
5. To translate the part in parenthesis, type `\x` (or `\times`) between `W/m` and `K`.
<!-- 5. In segment #52, remove the regular “x” in the formula and insert the autotext corresponding to the multiplication symbol, i.e. \times or \x. -->
6. Notice how the auto-completer opens when you typed the autotext shortcut.
7. Press ++enter++ to insert the caracter.

   > Result should be: `W/m × K`  
   > Incorrect translation: `W/m x K`

!!! info
    You can find the list of autotext entries in [OmegaT guides](../../) > [Miscellanea](../../misc/) > [Autotext](../../misc/autotext/)

## Exercise 06.3: insert special character from the character table

Remember the auto-completer? You used it to insert tags. You'll use it again now to insert a special character.

1. Go to segment #49

   > Target text reads: “La densité de population est de 62 personnes par km2 en 2023.”

2. Delete number 2 in “km2” (and keep your cursor right after “km”).
3. Press ++ctrl+space++ several times to cycle through all the sections in the auto-completer. Stop when you reach the “Character table”.
4. Spot the relevant character `²` and double click on it to insert it.

   > The result should be: `km²`

!!! tip
    You could have inserted character ² with shortcut `\sup2` (where "suP" stands for superscript or superindex or superordinate).

<!-- @todo: add to the guides: if you find the character table handy but it does not contain ghe charcter you need to insert, you can let us know through the Helpdesk and we'll add it there for you -->
