## Check and fix tags

To ensure that all tags have been inserted correctly:

  * Go to **Tools** > **Check Issues**. A pop up window will open.

    ![](../_assets/img/33_check_issues.jpg)

By default, other types of checks (Spelling, Terminology, LanguageTool) are ticked. If you want to check for issues related to tags before performing the rest of the checks, you can untick them. You will notice that the **Tag Issues** box cannot be unticked.

  * Press **OK**.
  * An error report will open.

    ![](../_assets/img/34_error_report.jpg)

  * Go through the issues one by one:

    1. Correct the issue by clicking on **Jump to Segment**. 
    2. You will arrive at the appropriate segment in the editor pane. 
    3. Place your cursor where the missing tag needs to be inserted and press ++ctrl+t++ to insert the missing tag.
    4. Press Enter to move to the next segment.
    5. Open the Error report again. It has automatically refreshed.
    6. Finish going through the issues.

!!! caution
    Please do not click on "Apply fix", fix each issue manually.

!!! info "Note"
    If in the source there are tags that you do not use in your language which are present in the source segment, to avoid having false positives in the error report, you can insert them at the end of the segment. They would not have an impact on any text.

