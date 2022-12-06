# Handling repeated segments

Some segments may be repeated. The translation of a repeated segment is is __autopropagated__ to all its instances.

## Identifying repeated segments

You can recognize that you are in a repeated segment because it has gray font.
When a repeated segment is active, the segment number will indicate how many repetitions exist: 

  ![](assets/15_repeated_segment.jpg)

If you **right click** on a repeated segment, the contextual menu will point out the other occurrences of a repeated segment. It can be useful to jump to them (by selecting them from the contextual menu) to see the different contexts in which a repeated segment appears.

  ![](assets/16_repeated_context.jpg)

## Autopropagation

If you edit the translation of a repeated segment, by default, the changes will be automatically reflected in all the repetitions. This happens in the same file, but also in all the files of the OmegaT package.

  ![](assets/17_autopropagation.jpg)

## Create alternative translation

In some cases, you may not wish to modify the translation of all repeated segments. Due to a different context, you may need to change only ONE of the repeated segments:

  * **Right click** on the segment 
  * Choose **Create Alternative Translation** from the contextual menu

    ![](assets/18_create_alternative_translation.jpg)

  * Change the translation of your active segment and then either press ++ctrl+s++ or move to the next one.

    ![](assets/19_alternative_translation_created.jpg)

If you return on the repeated segment, you will see the different translations appear in the Multiple Translations pane.