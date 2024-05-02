# 03. Reconciliation

This section includes some bonus exercises specifically addressed to reconcilers.  
You may skip this section if you're not going to reconcile.

## Getting started

Here's a UI preference that may be useful for you when you reconcile.

1. In OmegaT, go to **Options** > **Preferences** > **TM Matches**.
2. Change value of setting "Minimal threshold to show a fuzzy match" to 100

With that setting, the **Matches** pane will show you only the translations you need to reconcile.

Please remember to restore the default value when you're not reconciling.

## Exercise 04.01: inserting one match

1. Go to segment #62 and read it. Here comes a story for you.

   > Source text reads `Once upon a time there was a reconciler who worked in OmegaT.`

2. You have one exact match. Press ++ctrl+i++ to insert it.
3. Easy start. Now press ++ctrl+u++ to move to the next _unreconciled_ segment.
4. Read segment #63.
5. You have one exact match. Press ++ctrl+i++ to translate the segment with that match.
6. Still easy. Press ++ctrl+u++ to move to the next _unreconciled_ segment.

!!! info "Информация"
    You only see one match if "translation 1" and "translation 2" are identical.

<!-- add info above to the guides @todo -->

## Exercise 04.02: selecting the match

> You're now on segment #64.

7. Read segment #64.
8. Notice that now you can see **_two_** matches because "translation 1" and "translation 2" are different now.
9. You want to use the first translation (selected by default). Press ++ctrl+i++ to insert match #1.

   > Translation reads `Parfois, l'une des deux traductions était bonne, et l'autre était mauvaise, donc le choix était clair.`

10. Press ++ctrl+u++ to move to the next _unreconciled_ segment.

   > You're now on segment #65.
11. Read segment #65.
11. Here you want to use the second translation. Press ++ctrl+2++ to select match #2.
12. Press ++ctrl+i++ to insert it.

   > Translation reads `D'autres fois, la première traduction était mauvaise, mais la seconde était bonne, donc le choix était également clair.`

13. Press ++ctrl+u++ to move to the next _unreconciled_ segment.

## Exersise 04.03: editing the inserted translation

> You're now on segment #66.

14. Read segment #66.
14. Press ++ctrl+i++ to insert the exiting match.
15. Edit the translation to make it a good translation.

   > Tip: Remove the excessive `SSs` in `parfoisSSs`.

16. Press ++ctrl+u++ to move to the next _unreconciled_ segment.

## Exercise 04.03: assembling fragments

> You are in segment #67.

17. In match #1, select `Et encore d'autres fois, la première traduction avait une partie qui était bonne, `
18. Press ++ctrl+i++ to insert the text you have selected.
19. In match #2, select `, mais l'autre partie était meilleure dans la deuxième traduction, ou vice versa, donc il fallait les combiner les combiner.`
20. Press ++ctrl+i++ to insert the text you have selected now.

   > Expected result: `Et encore d'autres fois, la première traduction avait une partie qui était bonne, mais l'autre partie était meilleure dans la deuxième traduction, ou vice versa, donc il fallait les combiner les combiner.`

You have combined two parts of two translations to create one single reconciled version. Congrats!

## Finally

Please remember to restore the default threshold to show matches:

1. In OmegaT, go to **Options** > **Preferences** > **TM Matches**.
2. Change value of setting "Minimal threshold to show a fuzzy match" to 50.

