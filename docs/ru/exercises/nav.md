# 01. Навигация

<!-- prettier-ignore -->
??? Abstract "The relevant section in the guides..."
    See the relevant section in your guide:
    [Перевод](../translation/navigation.md){:target="_blank" .md-button }
    [Согласование](../reconciliation/navigation.md){:target="_blank" .md-button }
    [Адаптация](../adaptation/navigation.md){:target="_blank" .md-button }
    [Верификация](../verification/navigation.md){:target="_blank" .md-button }

---

<!-- prettier-ignore -->
!!! tip "Remember"
    **The active segment always has a green background.**{ .active }

## Exercise 01.1: moving through the project

<!--
NAVIGATION in first file???
to avoid directing the user to later in the project ...
-->

1. Press ++ctrl+j++ and enter `1` to go to segment #1.

    > Source text reads `Welcome to this survey!`

2. Press ++enter++ to move to the _next_ segment.

    > You are now in segment #2.

    <!-- > Source text reads `How is your economic situation?` -->

3. Press ++ctrl+u++ to move to the next _untranslated_ segment.

    > You are now in segment #3.

    <!-- Source text reads `Pretty good` -->

4. Press ++enter++ twice in a row to go forward 2 segments.

    > You end up in segment #5.

    <!-- > Source text reads `Pretty good` again -->

5. Press ++ctrl+enter++ twice in a row to go backwards 2 segments.

    > You are now in segment #3.

    <!-- > Source text reads `Pretty bad` -->

6. Press ++ctrl+u++ once to go to the next _untranslated_ segment.

    > You end up in segment #5 again.

    <!-- > Source text reads `Pretty good` again -->

7. Notice that you have jumped segment #4, which is already translated (in pink).

<!-- prettier-ignore -->
!!! Совет
    Press ++ctrl+u++ when you're translating.  
    Press ++enter++ when you're reviewing a translation.

<!--
adri's exercise: more practice
remove if unnecessary, check with adri
-->

## Exercise 01.2: moving through the project a bit more

<!---Check segment numbers!!-->
<!-- @demo about navigation: explain color green = active segment -->
<!-- @todo (AM): add notice green color to exercise -->

1. Press ++ctrl+j++ and enter number 25 to go to segment #25.

    > Source text reads: `Generally speaking, please tell me <g1>how satisfied</g1> you are with public transport where you live.`

2. Press ++ctrl+u++ to jump to the next untranslated segment.

    > You are now on segment #30.

3. Press ++enter++ to move the next segment.

    > You are now on segment #31.

4. Oops, you haven't translated segment #30. Press ++ctrl+enter++ to go back to it.

    > You are now on segment #30 again.

5. Scroll down until you see another untranslated segment in that file.

    > Source text reads: `Generally speaking, please tell me <g1>how satisfied</g1> you are with schools and other educational facilities where you live.`

6. Double click on that segment.

    > You are now on segment #53.

7. Press keyboard shortcut ++ctrl+j++ and enter number 1 to go to segment number #1.

<!-- prettier-ignore -->
!!! info "Recap"
    In this exercise you have practiced several ways to activate a segment:
    - ++enter++ opens the next segment
    - ++ctrl+enter++ opens the previous segment
    - ++ctrl+u++ opens the next _untranslated_ segment
    - ++ctrl+j++ (plus the segment numberj) opens a specific segment
