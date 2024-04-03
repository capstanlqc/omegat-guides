# 05. Repetitions

<!-- prettier-ignore -->
??? Abstract "The relevant section in the guides..."
    See the relevant section in your guide:
    [Перевод](../translation/repetitions.md){:target="_blank" .md-button }
    [Согласование](../reconciliation/repetitions.md){:target="_blank" .md-button }
    [Адаптация](../adaptation/repetitions.md){:target="_blank" .md-button }
    [Верификация](../verification/repetitions.md){:target="_blank" .md-button }

---

## Exercise 05.1: recognize repeated segments

<!-- @todo !!! note inline end "←TODO"
    @quiz: how many reps in total?  -->

1. Press ++ctrl+j++ and enter 13 to go to segment #13.

    > Source text reads: `Pretty good`

2. Notice how the segment marker says that this segment is repeated three more times.

    > `<segment 0013 +1 more ¶>`.

3. Look at the **Segment Properties** pane. It says "Is duplicate: FIRST"
4. Right click on the segment. See how all the instances are listed and identified by their segment number.
5. Select `Segment 16` on the list to go to segment #16.
6. Look at the **Segment Properties** pane for segment #16. It says "Is duplicate: NEXT"
7. Right click on segment #16 to see instances listed again, go back to segment #13 again.

## Exercise 05.2: auto-propagate translations

1. Go to segment #12.
2. Translate segment #12. <!-- put this translation in auto @todo -->

    > You can insert the match (++ctrl+i++) and update it (replace `financière` with `économique`)

3. Notice how "situation économique" is grammatically feminine in French.
4. Go to segment #13 and translate it. Suggested translation: `Plutôt bonNE`

    > The -NE ending is the feminine suffix, because "Good" here refers to "economic situation", which is feminine in French

5. Press ++enter++ after translating segment #13 to go to segment #14.
6. Notice how the translation is auto-propagated to segment #16.
7. Translate segment #14. Suggested translation: `Plutôt mauvaisE`

    > The -E ending is the feminine suffix, because "Bad" here refers to "economic situation", which is feminine in French

8. Press ++enter++ after translating segment #14 to confirm the translation of segment #14 and go to the next segment.
9. Notice how the translation is auto-propagated to segment #17.

## Exercise 05.3: auto-propagate edits in translations

1. Go to segment #16 in the project. You can see that it is translated with your auto-propagated translation.

2. Modify the translation (append "xx") in segment #16 and press ++ctrl+s++ to save the translation.
3. Notice how the translation of segment #13 also changes.
4. Do the same in segment #17 and see how changes auto-propagate to segment #14.

<!-- add link in the guide to the shortcuts page when we mention a shortcut -->

<!-- prettier-ignore -->
!!! Совет
    Shortcut ++ctrl+s++ saves the translation. You can also save in **Project** > **Save**, but using the mouse takes longer ;)

<!-- add this tip to the guides -->
