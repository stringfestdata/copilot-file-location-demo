# Copilot file-location demo

A small fictional source for the Stringfest Analytics article "Where do Copilot uploads go? Why I start in OneDrive or SharePoint."

## What you need

Microsoft 365 Copilot Chat with a work or school account, plus access to that account's OneDrive. Menus and cloud-file access vary by license and organization. This example uses the main Copilot website, not Excel's Copilot pane.

## Follow one file

1. Download and unzip this repository. Open `upload-location-demo.txt` and inspect the source marker, month, and travel variance.
2. At https://copilot.cloud.microsoft/, open a new chat. Choose **+ > Upload images and files** and select that TXT file from your device.
3. Read the upload notice. In the demonstrated account it says that uploading from the device sends a copy to OneDrive (work/school). Follow **Manage uploads**, if shown, and locate the file in **My files > Microsoft Copilot Chat Files**.
4. Return to the chat and use this prompt:

```text
Read the attached upload-location-demo.txt. Return only three labeled lines: Source marker, Reporting month, and Travel variance. Quote the values from the file exactly. Do not edit any files.
```

5. Compare the answer with the TXT file. It should identify ORIGINAL UPLOAD, November 2026, and $5,000 under budget. Inspect the source rather than accepting the filename as proof.
6. To practice the alternative, put the TXT file in a deliberately named project folder in work OneDrive (or an appropriate team SharePoint library). In a new chat, choose **Attach cloud files** and select that existing document. If the cloud picker is not available in your account, keep the maintained source organized and treat any upload as a deliberate task copy.

Editing the local original does not update the separate device upload. Selecting a cloud file also does not rewrite an earlier answer; after a meaningful correction, select the intended source again, request a fresh analysis, and verify a changed fact.

The data is entirely fictional. Review the demo copies before removing any files. No macros, code, or account configuration are needed.
