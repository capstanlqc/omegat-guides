# 08. Search

<!-- prettier-ignore -->
??? Abstract "The relevant section in the guides..."
	See the relevant section in your guide:

    [Translation](../translation/other-useful-features.md#running-concordance-searches){:target="_blank" .md-button }
    [Reconciliation](../reconciliation/other-useful-features.md#running-concordance-searches){:target="_blank" .md-button }
    [Adaptation](../adaptation/other-useful-features.md#running-concordance-searches){:target="_blank" .md-button }
    [Verification](../verification/other-useful-features.md#running-concordance-searches){:target="_blank" .md-button }

---

## Exercise 08.1: search for a selected expression

Try to find the translation of "translator" in the translation memories.

1. Press ++ctrl+j++ and enter 47 to go to segment #47.
2. Select the word `translator`.
3. Press ++ctrl+f++ to open the **Text Search** dialog.
4. Notice how the word "translator" is already filled in in the search box.
5. Check option "Translated" so that you will only find translated segments.
6. Check box "TMs" under "Search in" to search in the translations memories.
7. Press the **Search** button.

    > Expected result: `traducteur`

<!-- @todo: add exercise that shows how sometimes you don't get a fuzzy match because of low similarity score and poor matching algorithm but there's a useful concordance in the TM -->

## Exercise 08.2: search for a segment identifier

You might need to refer to a certain segment by its identifier (the segment ID or key).

1. Press ++ctrl+f++ to open the **Text Search** dialog unless it's already open.
2. Check option:

    - In comments

3. Type `123abc` in the search box, and press **Search**.

    > Expected results:
    >
    > > 01_qq/03_qq_paq.xml  
    > > -- 22> Neither good nor bad  
    > > \# name = 123abc

<!-- prettier-ignore -->
!!! info
	Here `# name` refers to the segment identifier.

<!--
## Exercise 08.4:

4. Find source text "Subject" in the project, but only if it has a translation.
-->

## Exercise 08.3: search for some source text

One instance of the repeated segment "Rather satisfied" was not translated consistenly.

1. Press ++ctrl+f++ to open the **Text Search** dialog.
2. Check options:

    - Exact search
    - In source
    - All matching segments
    - Search in: Memory

3. Do not check options:

    - Search in: TMs

    <!-- screenshot! -->

4. Type `Rather satisfied` in the search box, and press **Search**.

    > Expected results:
    >
    > - 27> Plutôt satisfait
    > - 32> Assez satisfait
    > - 37> Plutôt satisfait

5. Notice that here is one instance of the repeated segment "Rather satisfied" that was not translated consistenly.

    > Can you see which translation is inconsistent?

<!-- @todo: write RFF: go to next segment with a comment -->
