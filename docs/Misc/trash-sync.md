# TRaSH Sync

These are 3rd party applications to sync several sections of the guide with your Sonarr/Radarr (or multiple).

- Radarr Custom Formats [^1] [^2]
- Radarr Scores [^1] [^2]
- Radarr Quality Settings (File Size) [^2]
- Sonarr Release Profile RegEx (WEB-DL) [^1] [^2]
- Sonarr Release Profile RegEx (Anime) [^1] [^2]
- Sonarr Quality Settings (File Size) [^2]

## Notifiarr

It's possible with [Notifiarr](https://notifiarr.com/profile.php){:target="_blank" rel="noopener noreferrer"} ([Patron feature](https://notifiarr.wiki/FAQ#patron){:target="_blank" rel="noopener noreferrer"})

After setup it's fully automated and will check every X minutes for updates to the Custom Formats or Sonarr Release Profile and will update it to your Radarr or Sonarr (Multiple Client Support).

Just enable the Custom Formats/Release Profiles you want.

??? check "Examples - [CLICK TO EXPAND]"

    Radarr Custom Formats Table
    ![!Notifiarr Custom Format Table](images/sync/notifiarr-cf-table.png)

    Radarr Custom Formats (Multiple Instances possible)
    ![!Notifiarr Custom Formats Audio](images/sync/notifiarr-cf-audio.png)

    Radarr Custom Formats (Multiple Instances possible)
    ![!Notifiarr Custom Formats HDR Metadata](images/sync/notifiarr-cf-audio.png)

    Radarr scoring (Multiple profiles possible)
    ![!Notifiarr Scores](images/sync/notifiarr-scores.png)

    Sonarr Release Profile (Multiple Instances possible)
    ![!Notifiarr Sonarr](images/sync/notifiarr-sonarr.png)

[Instructions](https://notifiarr.wiki/en/Website/Integrations/Trash){:target="_blank" rel="noopener noreferrer"}

------

## TRaSH Updater

It's possible with [trash-updater](https://github.com/rcdailey/trash-updater){:target="_blank" rel="noopener noreferrer"}

Automatically mirror TRaSH guides to your Sonarr/Radarr instance based on your setup scheduler.

[Instructions](https://github.com/rcdailey/trash-updater#getting-started){:target="_blank" rel="noopener noreferrer"}

--8<-- "includes/support.md"

[^1]:
    Notifiarr

[^2]:
    TRaSH Updater
