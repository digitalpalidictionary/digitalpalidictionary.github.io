# Install GoldenDict on Mac

## In Brief

1. download the latest version of `dpd-goldendict.zip` from [GitHub](https://github.com/digitalpalidictionary/dpd-db/releases/latest)
2. install [GoldenDict NG](https://github.com/xiaoyifang/goldendict-ng/releases/latest). Use `macOS-arm64.dmg` for Apple Silicon M1 chip and newer, or `macOS-x86_64.dmg` for Intel AMD64 machines.
3. in settings, direct GoldenDict to the DPD folder.

Below are detailed *step-by-step* instructions. 


## Download GoldenDict

If you are using an Apple Silicon M1 chip or newer, download `macOS-arm64.dmg` from [GoldenDict NG Releases on Gitgub](https://github.com/digitalpalidictionary/dpd-db/releases/latest).

If you are using an Intel AMD64 chip, download `macOS-x86_64.dmg` from [GoldenDict NG Releases on Gitgub](https://github.com/digitalpalidictionary/dpd-db/releases/latest). 


## Install GoldenDict

Double click the `GoldenDict.dmg` file in your Downloads folder.

<!-- <img width="470" alt="download gd" src="pics/mac-install/download%20gd.png"> -->

Double click the installer.

<img width="628" alt="goldendict install" src="pics/mac-install/goldendict%20install.png">

You'll probably get a security warning like this. 

<img width="258" alt="warning" src="pics/mac-install/warning.png">

Click cancel and open Security and Privacy Preferences. Click on the lock at the bottom left corner. Then choose “Open anyway” and GoldenDict will open. Click Open Anyway.

<img width="627" alt="allow gd" src="pics/mac-install/allow%20gd.png">

Click Open on the next security warning. 

<img width="258" alt="next security warning" src="pics/mac-install/next%20security%20warning.png">

Ok, you're installed. Now let's add a dictionary. 

-------------------------------------------------

## Download DPD

Download the latest version of `dpd-goldendict.zip` from [GitHub](https://github.com/digitalpalidictionary/dpd-db/releases/latest). 

## Unzip

Find the .zip file in your downloads folder and unzip it.

<img width="485" alt="unzip dpd" src="pics/mac-install/unzip%20dpd.png">

## Make a GoldenDict folder

It is recommended to make an easily accessible GoldenDict folder, for example `/Documents/GoldenDict`

<img width="470" alt="documents folder" src="pics/mac-install/documents%20folder.png">

Copy the unzipped DPD folder into `/Documents/GoldenDict`

<img width="485" alt="documents gd dpd" src="pics/mac-install/documents%20gd%20dpd.png">

-------------------------------------------------

## Adding Dictionaries to GoldenDict

Launch the GoldenDict application.

Go to Menu > Edit > Dictionaries (Shortcut **F3**).

<img width="552" alt="edit dictionaries" src="pics/mac-install/edit%20dictionaries.png">

Go to Sources > Files. Click Add.

<img width="989" alt="sources files" src="pics/mac-install/sources%20files.png">

Select the folder `/Documents/GoldenDict`.

<img width="798" alt="select gd folder" src="pics/mac-install/select%20gd%20folder.png">

Click the recursive tick box √ (this makes sure GoldenDict searches in sub-folders).

<img width="430" alt="recursive" src="pics/mac-install/recursive.png">

Click Rescan now or OK and wait a few moments while the dictionaries are indexing.

<img width="917" alt="indexing" src="pics/mac-install/indexing.png">

You're all setup!

-------------------------------------------------

Next learn how to [set up the hotkey](setup_hotkey.md) so you can click on any inflected Pāḷi word in any text and open it immediately in the dictionary.

