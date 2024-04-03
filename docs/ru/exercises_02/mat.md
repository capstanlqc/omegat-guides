# 02. Matches @WIP

@todo: check whether tags + matches or matches + tags
@todo: update numbers or remove them

## Exercise 02.1: translate from scratch

1. Translate segment #1.

   > Suggested translation: `Bienvenue à cette enquète.`

2. Press ++ctrl+u++ to go to segment #2.

## Exercise 02.2: insert match and update it

You're in segment #2.

3. Notice that there's a fuzzy match you can use.
4. Press ++ctrl+i++ to insert it.
5. Looking at the **Matches** pane, notice that there's a difference between the new source text and the source text in the match.
6. Update the inserted translation so that it corresponds to the source text you're translating.

   > Tip: Replace `financiere` with `économique`.

7. Press ++ctrl+u++ to go to segment #3.

## Exercise 02.3: insert exact match

You're in segment #3.

8. Notice that there's an exact match which you can use as is.
9. Press ++ctrl+i++ to insert it.

   > There's nothing else to do this time :)

10. Press ++ctrl+u++ to go to segment #4.

## Exercise 02.4: insert match and update it

You're in segment #4. Your previous translation is now a 50% match that you could use.

11. Press ++ctrl+i++ to insert the 50% match.
12. Now update the translation so that it corresponds to the source text.

   > Tip: delete `bon`, type `mauvaise`

   > Expected result: `Plutôt mauvaise`


## Exercise 02.5: pretranslated and editable

You're still in segment #4.

14. Notice how segment #5 is pretranslated.
15. Notice that it has a pink background. That means that it is editable, if necessary.
16. Press ++ctrl+u++ to go to segment #8.

## Exercise 02.6: almost identical match

You're in segment #8.

> Source text reads `Welcome to this survey!`

17. Notice how this segment is almost identical to the first segment you translated.

   > The only difference is in the final punctuation.

18. Press ++ctrl+i++ to insert the match.
19. Update the translation now.

   > Replace final dot `.` with exclamation mark ` !`

## Exercise 02.7: pretranslated and locked

You're still in segment #8.

20. Notice how segments #9, #11 and a few others are pretranslated.
21. Notice that they have an orange background. That means they are enforced translations, in other words: not editable.
22. Modify the translation (just add a few characters)
23. Press F5 to reload the project.
24. Notice how your edits are now gone.

<!-- harmonize: move to -> go to @todo -->

## Exercise 02.8: select match

1. Press ++ctrl+j++ and enter number 15 to go to segment #15.
2. Notice that this segment is pretranslated.
3. Go to segment #16.

   > Source text reads `Good`

4. Notice how the **Matches** pane presents two matches you could use.
5. Press ++ctrl+2++ to select the second match (match #2).
6. Press ++ctrl+i++ to insert the selected match (match #2).
7. Delete `plutôt` and change the case.

   > Expected result: `Bon`

<!-- @todo: disable predictive typing and delete files... -->

!!! Примечание
    In this case both matches required the same amount of work to update them.  
    The only reason why you have to select and insert match #2 is to make you practice ;)

## Exercise 02.9: insert selection

8. Press ++ctrl+u++ to go to segment #17.
9. Select "mauvaise" in the fuzzy match
10. Now press ++ctrl+i++ to insert the selected text
11. Update the match.

   > Change case of `m` to `M`

   > Expected result: `Mauvais`ç

## Exercise 02.10:

12. Press ++ctrl+u++ to go to segment #18.
13. Press ++ctrl+2++, then press ++ctrl+3++, as many times as you want.
14. Notice how match #2 and match #3 get seleted when you press the shortcuts above.
15. Select one and insert it, then updated it.

   > Here you're free to update the fuzzy match as you like.

   > Expected resul: `Très mauvais`

!!! info "Recap"
    To recap, the available options are:
    1. Write  `Très`, then select `mauvaise` in match #2 and press ++ctrl+i++
    2. Press ++ctrl+2++, then ++ctrl+i++ to insert match #2, then replace `PLutôt` with `Très`
    3. Press ++ctrl+3++, then ++ctrl+i++ to insert `Mauvaise`, then update it, then add `Très` at the beginning
    4. Write `Très`, then press ++ctrl+3++, then ++ctrl+i++ to insert match #3, then update it.

    They are all valid approaches, any is fine as long as the result is correct.


<!--
quiz: which one is more efficient?
-->


<!--

#15 -> Très + select "bon" -> ctrl+i
ctr+u -> #16
ctrl+i -> + delete très
ctrl+u -> #17
select "mauvaise" + ctrl+i + update (m -> M)
ctrl+u -> #18
<. three matches
press ctrl+2 to select the second match
press ctrl+i to insert it
write "Très" + ctrl+i to insert  + update
-->

<!--
quiz: do you prefer to select and insert, or insert and update?
-->
