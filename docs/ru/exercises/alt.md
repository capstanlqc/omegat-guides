# 06. Альтернативные переводы

<!-- prettier-ignore -->
??? Abstract "The relevant section in the guides..."
    See the relevant section in your guide:
    [Перевод](../translation/repetitions.md#create-alternative-translation){:target="_blank" .md-button }
    [Согласование](../reconciliation/repetitions.md#create-alternative-translation){:target="_blank" .md-button }
    [Адаптация](../adaptation/repetitions.md#create-alternative-translation){:target="_blank" .md-button }
    [Верификация](../verification/repetitions.md#create-alternative-translation){:target="_blank" .md-button }

---

In the previous section you saw that translations of repeated segments (or edits in those translations) auto-propagate to all instances of that repeated segment when you save them (or leave the segment).

That is convenient in many cases, but not always. Sometimes you'll have to prevent auto-propagation. To do that, you must create an **alternative translation**.

## Упражнение 06.1: создание альтернативного перевода

1. Go to segment #16 in the project.

   > Source text reads: `Pretty good`

2. Notice that it is translated with an auto-propagated translation.

   > `Pretty good` and `Pretty bad` in segments #16 and #17 in this context refer to "level of English" which is masculine in French. However, your translations ("Plutôt bonNE" and "Plutôt mauvaisE") refers to "situation economique", which is feminine.

You want to modify the translation in segments #16 and #17 to make it masculine, so that it agrees with "level" in French.

Follow these three simple but VERY IMPORTANT steps:

1. Go to **Edit** > **Create Alternative Translation**.

   > Tip: Also available if you right-click the segment.

2. Modify the translation to make it masculine

   > Just remove the last character if you don't know French

3. Press ++ctrl+s++ to register the translation

<!-- prettier-ignore -->
!!! Предупреждение
    This is a very important and delicate function of OmegaT. It's easy to use it correctly if you grasp well the three steps above, but it's also easy to make a mess if you don't. Please make sure you really follow the three steps above to the letter.

Did you follow the steps above? If you did, now you'll notice that:

- your alternative translation appears now in the **Multiple Translations** pane, below the default translation and followed by the filename and the segment ID.
<!-- @todo: confirm the |filename will be there -->
- the **Segment Properties** pane for that segment says now "Is alternative: TRUE"
- the (default) translation of segment #13 hasn't changed

Press ++enter++ to move to segment #17 and do the same steps as above.

<!-- prettier-ignore -->
!!! info
    If you want more practice on this, go to segment #62 (source text reads: `Subject:`), which is also repeated a few times. The first occurrence refers to an email subject line, whereas the other occurrences refer to the topic or subject matter field of books in a library classification system, so each of those requires a different translation, i.e. "Objet" vs "Sujet".
