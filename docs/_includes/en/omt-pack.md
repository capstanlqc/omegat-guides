# Delivery

Once you have finished your task in the OmegaT project and have performed the relevant QA checks, you need to deliver the project. The delivery mode will vary depending on whether it's an _offline project_ or a _team project_.

## Online / team project (via repository)

To deliver from a team project, commit _all_ target files. To do that, do one of these two things:
 
- Go to **Project** > **Commit Target Files**, or
- In version 5.7.3 or higher: press ++ctrl+d++ to create target files and commit them (or go to **Project** > **Create Translated Documents**, if you don't like [shortcuts](../../misc/shortcuts/)).

Beware that it's also possible to commit one file at a time (in version 5.7.3 or higher):

- Press ++ctrl+shift+d++ to create and commit the current target file (go to **Project** > **Create Current Translated Document**, if you don't like [shortcuts](../../misc/shortcuts/)).

!!! info "Remote previewer"
    If you want to use a remote previewer, you might need to commit only the file you want to preview, e.g. if you make an edit in a file and you want to see the result in that file in the remote previewer. In other words, you may want to commit one file at a time. If you're working on a large project and you commit all target files every time even though you only need to see changes in one file, the commit will take longer to process unnecessarily.

## Offline project (via package)

- Go to **Project** > **Pack project as OMT file...**

    ![](../_img/29_export_omt.png)
    <!-- @todo: update screenshot with current wording -->

- In the window that pops up, select the location where you want to save the OMT package.
  <!-- @todo: link to http://127.0.0.1:8000/omegat-guides/misc/tips/#file-organization / add 01_Incoming, 02_Work, 03_Outgoing for packages -->
- Press **Save**
- Press **OK** in the Pop-up window notifying that the package was successfully created.

    ![](../_img/30_omt_successful.png)

The folder where exported package is stored will open automatically in your file explorer.

You will recognize the package because it has the extension `.omt`. That's the file you have to deliver.

![](../_img/31_recognizing_omt.png)
