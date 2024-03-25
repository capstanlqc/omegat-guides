## Fixing tag issues

All tags you see in the source text should be present in the translation too and in the correct position. You must correct any errors that you may see when that's not the case.

You may find two types of issue:

- A tag or tag pair is missing: in that case, the solution is simply to [insert it](#inserting-tags).

- A tag is inserted but misplaced: the solution may be either to [drag and drop](#moving-tags) single tags to the correct position, or simply to [delete the tag](#deleting-tags) (or tag pair) and [insert it](#inserting-tags) again correctly.

??? warning "Warning for RTL languages"
In right-to-left languages such as Arabic or Hebrew, moving tags will not work. Please delete the tag and insert it again if you work with any of these languages.

### Deleting tags

If you have inserted a tag incorrectly and need to [insert it](#inserting-tags) again, **double click** on the tag to select it in full and press ++backspace++ or ++delete++ on your keyboard to delete it first.

![](../../_assets/img/omt-tags-delete.gif)

### Moving tags

If you have inserted a tag in the wrong position and need to insert it somewhere else, you can simply **drag and drop** it. Alternatively, you can also delete it and insert it again.

![](../../_assets/img/omt-tags-moving.gif)

<!-- @todo: explain the auto-completer as the main insertion method -->

<!-- @todo: FINISH -->

<!--
In the screenshot below, in the source segment the **paired tags** **&lt;i&gt;**{ .omttag } and **&lt;/i&gt;**{ .omttag } are around the letter `n` while in the target they are around the word `which`.


![](../../_assets/img/09b_tags_issue_ada.jpg)

To correct this issue, you would have to perform the following steps:

  1. Double click on the each incorrectly inserted tag in the translation to select it and press ++backspace++ or ++del++ on your keyboard to delete it
  2. Select the text that must encompassed by the paired tags.
  3. Press ++ctrl+space++ to launch the auto-completer. You might need to press ++ctrl+space++ several times to cycle through the different options until you see the list of tags.
  4. Select the paired tags that you want to insert and press ++enter++.
  <!-- ![](../../_assets/img/11a_tag_order_ada.jpg)

The tags are inserted around the text you have selected.
-->
