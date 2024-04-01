# 09. QA checks

<!-- prettier-ignore -->
??? Abstract "The relevant section in the guides..." 
	See the relevant section in your guide:

    [Translation](../translation/qa-checks.md){:target="_blank" .md-button }
    [Reconciliation](../reconciliation/qa-checks.md){:target="_blank" .md-button }
    [Adaptation](../adaptation/qa-checks.md){:target="_blank" .md-button }
    [Verification](../verification/qa-checks.md){:target="_blank" .md-button }

---

## Exercise 09.1: check tag issues

1. Open the _QA checks_ dialog in **Tools** > **Check for issues...**.
2. Uncheck all options except "Tag Issues"

   > The "Tag Issues" check is mandatory, you cannot unselect it.

3. Press "OK"
4. Notice that there is (at least) an issue about "Bad nesting".
5. Press the "Jump to segment" button.
6. OmegaT will open the segment with the issue.

   > You should be on segment #25

7. Look at the tags and notice what the issue is about.

   > The order of tags is incorrect.

8. Remove the two tags and insert them again.

   > Expected result: `De manière générale, dites-moi si à quel point <g1>vous êtes satisfait</g1> avec les transports publics là où vous vivez. `

9. Press the "Refresh" button in the **Issues** dialog to confirm that the issue is gone.
<!--
Old stuff


10. There are two segments with tag errors, can you find them?
11. On which segment is there a glossary error?

-->

<!-- QA checks for verifiers: they should not uncheck spelling (at least)... -->

<!-- prettier-ignore -->
!!! tip
	If you're not sure how to fix a tag issue during a production task, please request support through the Helpdesk.

## Exercise 09.2: check completion

1. Go to **Tools** > **Statistics**.
2. Look at the **Remaining** row in the project statistics.
3. Notice whether the project is fully translated.

<!-- prettier-ignore -->
!!! tip
	If you see a number higher than zero in the **Remaining** row(s), that means that there are still some remaining untranslated segments. All segments should be translated before you can finalize your task.

<!-- prettier-ignore -->
!!! tip
	Press ++ctrl+u++ to go to the next _untranslated_ segment.
