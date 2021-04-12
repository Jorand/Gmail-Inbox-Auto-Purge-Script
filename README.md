# Gmail Inbox Auto-Purge Script
Auto-Purge Emails Script
📦 Setup rules and labels to clean up all emails older than 10, 30 or 90 days

## Set it up

1. Sign in to your Google Account.
2. To open the script editor, go to [script.google.com](script.google.com). If this is the first time you've been to script.google.com, click `View Dashboard`.
3. At the top left, click `New project`.
4. Delete any code in the script editor and add the `Code.gs` file.
5. At the top, click `Save`.
6. At the top left, click `Untitled project` and enter a name for your script.

## Create labels to filter your emails you want to be purge

1. Open [Gmail](https://mail.google.com/).
2. In the search box at the top, click the Down arrow.
3. Enter your search criteria. If you want to check that your search worked correctly, see what emails show up by clicking Search.
4. At the bottom of the search window, click `Create filter`.
5. Choose `Apply the label`: and choose/create a label with the name you setup in the script. example:
  . `Deleted after 10 days` will automatically delete emails with this label 10 days after been receipt.
  . `Deleted after 30 days` will be deleted 30 days after been receipt.
  . `Deleted after 90 days` will be deleted 90 days after been receipt.
6. Click `Create filter`.

## Try it out

1. Update the config in the editor to custom your labels and pruge schedule
2. At the top of the editor, select `Initialize` and click `Run`.
3. In the first dialog box that appears, click `Review permissions`. In the second dialog box, review the permissions your script uses and click `Allow`.
4. At the top of the editor, select `Install` and click `Run` to install the script.
5. You can now exit this window and any email messages in Gmail folder will automatically get purged after 'n' days. The script will run by itself everyday at 01:00 hours.

```Also, to stop the purging script anytime you can select Uninstall and click Run.```