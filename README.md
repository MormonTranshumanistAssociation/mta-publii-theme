# mta-publii-theme

## Setting up Publii 
- Download and install [Publii](https://getpublii.com/download/)
- Download and install [Google Drive for Desktop](https://support.google.com/drive/answer/7329379). If you are on a Mac, be sure you have MacOS High Sierra or newer.
  - Grant Google Drive security permissions as requested. (At least on macOS, this seems to have the potential to be finicky, resulting in repeated requests to reboot in order to make system changes take effect. We seem to have had success by signing in to our MTA accounts prior to performing the system restart, but this may not have been what made the difference.)
  - On macOS, Google Drive should appear as an icon in your menu bar. If you don't see it there, launch Google Drive from your Applications folder.
  - Select the Google Drive icon in the menu bar and sign in to your MTA account (if you haven't already).
  - When Google Drive has finished syncing, you should now be able to find the MTA website content at `/Google Drive/Shared drives/IT/www` (macOS).
- Open Publii for the first time
  - Specify "Mormon Transhumanist Association" as the site name
  - Specify "MTA Admin" as the author
  - Click the three dots in the top-right corner of the Publii interface and select "App settings"
  - For "Sites location" specify your Google drive location (usually "/Volumes/GoogleDrive/Shared drives/IT/www")

## Developing
- Clone this project in ~/Documents/Publii/themes
- To see theme changes after modifying something:
  - Delete previous mta-publii-theme.zip file if present
  - Right-click on mta-publii-theme subfolder and select **Compress "mta-publii-theme"**
  - Click three dots in top-right corner of Publii app and select "Themes"
  - Click **Install theme** and select the zip file
  - Click **Go back**
  - Click **Site settings**
  - Install and use the new theme inside the drop-down select
  - Click **Save and preview**. Verify that your new changes are present.
