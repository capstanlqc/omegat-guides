# Verification

**OmegaT** is the open source computer-assisted translation tool (CAT tool) which will be used to translate, reconcile, adapt, review and verify materials. The software has been customized to enable you to perform your task. 

## Quick walkthrough

## Installation and setup

To install OmegaT on a computer running on Windows, please consult the [OmegaT Installation guide](/doku.php?id=ug:tec-cb-ome-ins-ver)

When opening OmegaT for the first time change your name to "VER". To do that click on Options>Preferences>team. 
Type VER in the Name/ID text box. Then press OK.

[<img src="https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:omt_team_name.jpg" class="media" alt="" width="600" />](https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:omt_team_name.jpg)

## Accessing the package

### Accessing the package for the first time

The following steps need to be performed __only once per OmegaT package__: when you access each package for the first time: 

1. Download the  from the portal

2. Store the  in a location you will remember on your computer. 

3. Import the  in OmegaT: 

  * Open OmegaT
  * Go to **Project** > **Unpack OMT file**

[<img src="https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:01_import_omt_package.jpg" class="media" alt="" width="400" />](https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:01_import_omt_package.jpg)

  * Navigate to the location where you stored the OMT package. Choose the  and click on Open

[<img src="https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:02_open_omt_package.jpg" class="media" alt="" width="400" />](https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:02_open_omt_package.jpg)

  * A pop up opens. Click **Yes**.

[<img src="https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:03_delete_original_package.jpg" class="media" alt="" width="400" />](https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:03_delete_original_package.jpg) 

4. Translate/Reconcile/Adapt/Review the files in the package.

When you are done working for the day, close OmegaT.

### Access the package after import

The next times you want to access the project in OmegaT, go to **Project>Open Recent Project**. The project you were working on is the first one in the list:

[<img src="https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:04_open_recent_project.jpg" class="media" alt="" width="500" />](https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:04_open_recent_project.jpg)

## Editing

### Editing a segment to correct an error

#### Editing a segment to correct an error

To make a segment editable, you must activate it. You can only edit the active segment. You can recognize the active segment because it is highlighted in green.

We recommend that you move through segments one by one by pressing the **Enter** key. When you press the **Enter** key, you move from one segment to the next one, activating it. Any edits you then make will be applied in the active segment.  

You can also activate a segment by double-clicking it. When you double-click a segment, it becomes active and you can then edit it. 

## Navigation

### Navigation between the different panes

When you open OmegaT you will notice the screen is split in several panes:

  * The **Editor pane** is the main pane in which you will be working.
  * Translation suggestions will appear in the **Fuzzy Matches pane**.
  * The **Glossary pane** will display the existing glossary entries and the ones you may add.
  * The **Multiple Translations pane** will show you if a repeated segment was translated differently.

[<img src="https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:05_omegat_panes.jpg" class="media" alt="" width="500" />](https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:05_omegat_panes.jpg)

### Navigation between the different files

If the project contains multiple files, they are listed in the **Project Files pane**. The file currently open is highlighted in blue.

[<img src="https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:06_project_files_pane.jpg" class="media" alt="" width="500" />](https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:06_project_files_pane.jpg)

If you want to open a different file in the Editor pane, click on it in the Project Files pane. You can also see the name of the file that is open in the Editor pane's title bar.

### Navigation between the different segments

In the editor pane, the active segment is highlighted in green. This is the segment you are working in. The translation is displayed right below the source text. 

Press the **Enter** key on your keyboard to go to the next segment. A segment can also be activated by double clicking on it. It then becomes green.

[<img src="https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:07_active_segment.jpg" class="media" alt="" width="500" />](https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:07_active_segment.jpg)

In OmegaT, a **color code** will help you find your way around between the different segments:

  * **Green** = the segment you are working in (active segment)
  * **Grey** = translated segment. The translation is displayed below the source text.
  * **Orange** = pretranslated and locked segment (e.g. trend). These segments cannot be edited in OmegaT. If you need to implement changes in a trend segment, a separate user guide will explain how to modify them using a different tool.
  * **Pink** = pretranslated but unlocked

All segments should appear translated in a project for verification either in gray or in orange (trend) or in pink (pretranslated). If you notice an untranslated segment in ****, please contact cApStAn's project managers to see how it should be handled.

[<img src="https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:08_color_coding.jpg" class="media" alt="" width="600" />](https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:08_color_coding.jpg)

## Handling tags (++ctrl+t++)

### Recognizing tags

If you are in a segment which contains tags, you will recognize them because they are in **red font**. 

[<img src="https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:09a_tags_recognizing_ada.jpg" class="media" alt="" width="400" />](https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:09a_tags_recognizing_ada.jpg)

There are two types of tags - standalone tags and double tags:

  * **Standalone tags** = a single tag with a precise role (e.g. <br/> tag which introduces a new paragraph in HTML)
  * **Double tags** are composed of an opening and a closing tag, such as the HTML tags for making text bold, italic, underlined, etc. **Double tags** affect the text between them and you need to ensure they are positioned around the exact same words in the source and in the translation.

[<img src="https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:10_types_of_tags.jpg" class="media" alt="" width="400" />](https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:10_types_of_tags.jpg)

### Fixing tag issues

For your language task, all tags should be present in the translation. What is important is to correct potential errors that you may see. In the screenshot below, in the source segment the **** are around the letter **"n"** while in the target they are around the word **"which"**. 

[<img src="https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:09b_tags_issue_ada.jpg" class="media" alt="" width="500" />](https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:09b_tags_issue_ada.jpg)

To correct this issue, you would have to perform the following steps:

  * **double click** on the first incorrectly inserted tag in the target segment to select it and press **Backspace** on your keyboard to delete it 
  * repeat the operation until you deleted all incorrectly inserted tags
  * place your mouse where the first tag should be correctly inserted and press ++ctrl+t++ on your keyboard to insert the first tag
  * insert all other missing tags.

[<img src="https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:11a_tag_order_ada.jpg" class="media" alt="" />](https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:11a_tag_order_ada.jpg)

Please note that tags are inserted in the order of their appearance in the source segment.

### Most common HTML tags

Below you will find the most common HTML tags you may encounter.

[<img src="https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:11_b_tags_html.jpg" class="media" alt="" width="400" />](https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:11_b_tags_html.jpg)

## Using Fuzzy matches (++ctrl+i++)

Any changes you make during adaptation are saved in the project's translation memory. When you activate a segment which is similar to one you have already adapted, you may see suggestions in the fuzzy matches pane. 

The source in the fuzzy matches pane shows the difference between the active segment and the previous translation in ???track changes??? mode like in Word:

  * Parts that do not appear in the active segment are in ~~~~
  * Parts that are added are in ____

[<img src="https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:12a_fuzzy_matches_ada.jpg" class="media" alt="" width="400" />](https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:12a_fuzzy_matches_ada.jpg)

Do not hesitate to consult the fuzzy matches pane to ensure you make the same changes consistently throughout. 

You can insert a fuzzy match or a part of a fuzzy match with ++ctrl+I++:

  * Activate the fuzzy match you wish to use by **double clicking** on it. 
  * With your mouse, **select** the part you wish to insert.
  * Press ++ctrl+I++ on your keyboard to insert it.
  * Do not forget to **delete** all unnecessary/remaining text from the target segment to ensure everything is correct.

[<img src="https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:14a_select_part_fuzzy_ada.jpg" class="media" alt="" />](https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:14a_select_part_fuzzy_ada.jpg)

## Using the Glossary

OmegaT supports glossaries. Your package may already contain a glossary with key terms, but you can also add terms to the glossary yourself.

### Inserting glossary terms

When you arrive in an active segment which contains a glossary term, the respective term is underlined in blue in the source segment. 
You will see the suggested target term in the **Glossary pane**, on the right.

[<img src="https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:20_glossary_term.jpg" class="media" alt="" width="500" />](https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:20_glossary_term.jpg)

OmegaT has **predictive typing**: when you start typing the first character of the target term in the glossary, the auto-completer will suggest the term. To insert it, press **Enter** on your keyboard.

[<img src="https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:21_predictive_typing.jpg" class="media" alt="" width="500" />](https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:21_predictive_typing.jpg)

### Adding terms to the glossary

If in the project you are working on you keep adapting the same term over and over you may wish to add it to the glossary to ensure you adapt consistently throughout.

  * In the active segment,** select the term** you want to insert with your mouse
  * **Right click** and choose **Add glossary entry** from the contextual menu
  * [<img src="https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:22_add_glossary_entry.jpg" class="media" alt="" width="400" />](https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:22_add_glossary_entry.jpg)
  * A pop-up window will open
  * Enter the Target term and press the **OK** button.

## Handling repeated segments

Some segments are identical to each other. They are called ???**repeated segments**??? and their translation is __autopropagated__. 

### Identifying repeated segments

You can recognize that you are in a repeated segment because it has gray font.
When a repeated segment is active, the segment number will indicate how many repetitions exist: 

[<img src="https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:15_repeated_segment.jpg" class="media" alt="" width="400" />](https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:15_repeated_segment.jpg)

If you **right click** on a repeated segment, the contextual menu will point out the other occurrences of a repeated segment. It can be useful to jump to them (by selecting them from the contextual menu) to see the different contexts in which a repeated segment appears.

[<img src="https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:16_repeated_context.jpg" class="media" alt="" width="500" />](https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:16_repeated_context.jpg)

### Autopropagation

If you edit the translation of a repeated segment, by default, the changes will be automatically reflected in all the repetitions. This happens in the same file, but also in all the files of the OmegaT package.

[<img src="https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:17_autopropagation.jpg" class="media" alt="" width="400" />](https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:17_autopropagation.jpg)

### Create alternative translation

In some cases, you may not wish to modify the translation of all repeated segments. Due to a different context, you may need to change only ONE of the repeated segments:

  * **Right click** on the segment 
  * Choose **Create Alternative Translation** from the contextual menu

[<img src="https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:18_create_alternative_translation.jpg" class="media" alt="" width="400" />](https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:18_create_alternative_translation.jpg)

  * Change the translation of your active segment and then either press ++ctrl+s++ or move to the next one.

[<img src="https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:19_alternative_translation_created.jpg" class="media" alt="" width="800" />](https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:19_alternative_translation_created.jpg)

If you return on the repeated segment, you will see the different translations appear in the Multiple Translations pane.

## Other useful features

### Using the character table

**Special characters** can be inserted with the Special Characters Table. Special characters can be:

  * quotation marks: ????, ??????, ??????, etc. 
  * mathematical symbols: ??, ??, ??, ???, ???, ???, etc. 
  * other characters: ??, ???

When you arrive in a segment in which you need to insert a special character, perform the following steps:

  * Press ++ctrl+space++ on your keyboard several times until you reach the special characters table.

[<img src="https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:25_character_table.jpg" class="media" alt="" width="400" />](https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:25_character_table.jpg)

  * Select the character you want to insert
  * Press **Enter** and continue editing your segment.

[<img src="https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:26_inserted_special_characters.jpg" class="media" alt="" width="300" />](https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:26_inserted_special_characters.jpg)

### Inserting non-breaking spaces

In order to insert non-breaking spaces in OmegaT, please make sure you have installed **Auto Hot Key**. If you haven't installed it yet, please check the **Third Party Tools** section of the [OmegaT Installation guide](/doku.php?id=ug:tec-cb-ome-ins)

Once **Auto Hot Key** is installed, you can insert non-breaking spaces with the same keyboard shortcut as in Word: ++ctrl+shift+space++. You can recognize a non breaking space because it is gray. 

[<img src="https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:27_non-breaking_spaces.jpg" class="media" alt="" width="300" />](https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:27_non-breaking_spaces.jpg)

### Performing concordance searches

A concordance search allows you to look for words and expressions in the translation memory and the glossary. To perform a search follow the steps below:

  * In the active segment, select the word you want to search for with your mouse.
  * Press ++ctrl+f++ on your keyboard.
  * The Search window will open.
  * Press Search. 
  * The results will be displayed.
  * You can copy (select with mouse and press ++ctrl+c++ on your keyboard) what you need from the results and paste it in the target translation at the right place.

[<img src="https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:38_concordance_search.jpg" class="media" alt="" width="500" />](https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:38_concordance_search.jpg)

**TIP:** There might be small differences (in punctuation, spacing, etc.) between the text you're searching for and other occurrences of the same text that would prevent an *exact match*. The option "Keyword search" might help overcome that problem, please use it if you don't get the results you were expecting.

## Performing QA checks in OmegaT

### Completion check

All segments of the OmegaT package must have a translation. To ensure that is the case, please check for completion prior to delivery:

  * Go to **Project>Project Files**
  * The project files pane will open
  * **OK:** If the **Number of unique segments** __is equal to__ the number of **Translated unique segments**.

[<img src="https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:32_completion.jpg" class="media" alt="" width="500" />](https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:32_completion.jpg)

  * **NOT OK**: the **Number of unique segments** __is different from__ the number of **Translated unique segments**. To correct: 

  1. Close the Project Files Pane
  1. Press ++ctrl+u++ on your keyboard to jump to the __Next Untranslated Segment__. 
  1. When the cursor stops moving from the active segment then all segments have a translation.

Recheck for completion, to make sure by opening the Project Files pane.

### Check and fix tags

To ensure that all tags have been inserted correctly:

  * Go to **Tools>Check Issues**. A pop up window will open.

[<img src="https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:33_check_issues.jpg" class="media" alt="" width="200" />](https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:33_check_issues.jpg)

By default, other types of checks (Spelling, Terminology, LanguageTool) are ticked. If you want to check for issues related to tags before performing the rest of the checks, you can untick them. You will notice that the **Tag Issues** box cannot be unticked.

  * Press **OK**.
  * An error report will open.

[<img src="https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:34_error_report.jpg" class="media" alt="" width="300" />](https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:34_error_report.jpg)

  * Go through the issues one by one:

  1. Correct the issue by clicking on **Jump to Segment**. 
  1. You will arrive at the appropriate segment in the editor pane. 
  1. Place your cursor where the missing tag needs to be inserted and press ++ctrl+t++ to insert the missing tag.
  1. Press Enter to move to the next segment.
  1. Open the Error report again. It has automatically refreshed.
  1. Finish going through the issues.

**TIP**: If in the source there are tags that you do not use in your language which are present in the source segment, to avoid having false positives in the error report, you can insert them at the end of the segment. They would not have an impact on any text.

!!! caution
    Please do not click on "Apply fix", fix each issue manually.

### Glossary adherence check

You can check whether the translation adheres to the glossary and key terms have been translated consistently throughout:

  * Go to **Tools>Check Issues**
  * Make sure the box next to **Terminology Issues** is ticked

[<img src="https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:35_terminology_issues.jpg" class="media" alt="" width="200" />](https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:35_terminology_issues.jpg)

  * Press** OK.** 
  * An error report will open

[<img src="https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:36_error_report_terminology.jpg" class="media" alt="" width="600" />](https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:36_error_report_terminology.jpg)

  * Go through the issues one by one and jump to segment to correct the eventual error if needed.

## Creating target files

Press ++ctrl+shift+d++ to create the target file you were working on. This will allow you to preview the translated file with your changes.

To access the file, go to **Project>Access Project Contents>Target Files**. A window with the contents of the "target" folder will open. Find the file you were working on, if there are several files and preview it to read the translation in context.

[<img src="https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:28_target_files.jpg" class="media" alt="" width="300" />](https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:28_target_files.jpg)

## Delivering the project

Once you have finished editing the OmegaT package and have performed the appropriate Q&A checks, you need to Export the .

  * Go to **Project>Export OMT Package**

[<img src="https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:29_export_omt.jpg" class="media" alt="" width="300" />](https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:29_export_omt.jpg)

  * A pop up window will open.
  * Click Save
  * Press OK in the Pop-up window notifying that the package was successfully created.

[<img src="https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:30_omt_successful.jpg" class="media" alt="" width="300" />](https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:30_omt_successful.jpg)

  * You will be automatically directed to the location the exported package is stored.
  * You will recognize the package because it has the extension OMT. It should be the 4th from the bottom.

[<img src="https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:31_recognizing_omt.jpg" class="media" alt="" width="400" />](https://pisawiki.capstan.be/lib/exe/fetch.php?media=ug:31_recognizing_omt.jpg)

This is the file you have to deliver.

<!-- section: shortcuts -->
{% include 'cheatsheet.md' %}