# 04. Tags

!!! tip "Reminder"

    [Tags](https://capstanlqc.github.io/omegat-guides/translation/tags/) 
    <!-- @ŧodo: make this link role-specific -->

## Exercise 04.1: insert tags

1. Go to segment #9, which is untranslated.

    > Source text reads: `There are no &lt;g1&gt;right&lt;/g1&gt; answers.` <!-- segment should be untranslated -->

2. Notice the tags in the segment.
    
    > @quiz: what do you think these are? How to we handle them: should we ignore them or reproduce them in the translation?

3. Translate segment #9. Suggested translation: "Il n’y a pas de bonne réponse."
4. Select the part of the translation that corresponds to “right”

    > Tip: you should select `bonne`

5. Press ++ctrl+space++ to open the auto-completer.
6. Press ++ctrl+space++ several times to cycle through all the sections in the auto-completer. Stop when you reach the “Missing tags” section.
7. The first option (i.e. `<g1>|</g1>`) is selected by default. Press ++enter++ to insert tag pair.
8. Notice how the two paired tags are inserted around the selected text in the translation.

    > Expected result: `Il n’y a pas de <g1>bonne</g1> réponse.`

Well done! 


## Exercise 04.2: see what tags stand for

<!-- translation: Le traducteur a dû prêter attention au formatage tel que le gras, l'italique, le soulignement</g3>. -->
1. Go to segment #39.
    
    > Source text reads: `The translator had to pay attention to formatting such as <g1>bold</g1>, <g2>italics</g2>, <g3>underline</g3>.`

2. Hover over the tags with your mouse to display a toltip that shows the line code the tags stand for.

    > Tip: the tooltip should display HTML tags `<strong>`, `<em>`, `<span class="underline">` etc.


## Exercise 04.3: insert standalone tag

if <x1/> sensor detects black
1. watch, notice
2. complete, insert
3. translate and insert

## Exercise 04.4: insert more tags

1. Still in segment #39, notice how most tags are missing in the translation.
2. Select the part of the translation that corresponds to “bold” 

    > Tip: `le gras`

3. Press ++ctrl+space++ to open the "Missing tags" section in the auto-completer.
4. The first line (i.e. `<g1></g1>`) is selected by default. Press ++enter++ to insert that tag pair.
4. Notice how the tags have been inserted around the selected text

    > Results should be `<g1>le gras</g1>`

5. Do the same for the translation of “italics”

    > Tip: `l’italique`

5. Do the same for the translation of “underline”

    > Tip: `le soulignement` 

> @quiz: insert 

!!! note "NOTE FOR HELPERS"
    Two exercises for verifiers, won't be mixed with the above. Feel free to do these two exercises now and provide feedback but they will be reviewed and wrapped up later (after the seminar).

<!-- @todo: comment this whole section, and add later to the exercises in the verifiers guide -->


## Exercise 04.5: relocate tag

In this exercise, you'll practice how to move a tag.

1. Go to segment #30 (“<g1>Don’t Open This Email</g1>”) <!-- translation: N<g1>'ouvrez pas cet </g1>e-mail -->

    > @quiz: what do you notice?

2. Notice how the position of the first tag (tag `<g1>`) is incorrect. You will fix that.

    > @quiz: it should be at the beginning of the segment / end / in the middle

3. Double click on the tag `<g1>` to select it.
4. Now drag and drop it to the correct position.
    
    > tip: the paired tags should also include "N" 

??? note "Solution"
    shows the expected result (the solution) @todo: complete

!!! note "Tip for RTL languages"

    Please use the helpdesk if you find a complicated situation and we'll help you.

Well done!

## Exercise 04.6: relocate tag

In this exercise, you'll practice another way to move a tag to its correct position.

1. Still in segment #30 (“<g1>Don’t Open This Email</g1>”) <!-- translation is now: <g1>N'ouvrez pas cet </g1>e-mail -->
2. Notice the position of the second tag (`</g1>`) is also incorrect.
3. Double click on the tag `<g1>` to select it.
4. Press +del+ on your keyboard to delete the tag.
5. Place the cursor (e.g. just click) where you want the tag to appear instead
6. Use the auto-completer to insert the tag

    > tip: ++ctrl+space++

??? note "Solution"
    shows the expected result (the solution) @todo: complete
