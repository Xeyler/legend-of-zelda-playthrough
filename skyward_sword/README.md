# Skyward Sword

## Wii/Wii U Installation Instructions

To transfer Skyward Sword's save data to a Wii/Wii U, you will need a compatible SD card and an up-to-date Wii/Wii U. These systems are compatible with most SDHC SD cards up to 32GB. As always, if you come across any problems while following this guide, please create a new issue on this project's GitHub page.

1. Download the .bin save file. This can be done either via GitHub directly, or by cloning the repo.
2. Format an SD card, using the FAT32 file system.
3. Create several folders on the SD card to make a directory tree equivalent to the one shown:

    ```
    private
    └── wii
        └── title
            └── SOUE
    ```

    Creating folders in this structure should allow the wii to be able to locate the save file and attribute it to the correct game. (NOTE: The `private` folder should be in the root directory of the SD card with subsequent folders nested inside it)

4. Move the .bin save file from wherever it was downloaded to during step 1 into the 'SOUE' folder that you created on the SD card during step 3.
5. Eject the SD card from your computer, insert it into your Wii/Wii U, then turn the system on. If you're using a Wii U, enter the  original Wii Menu by selecting the Wii Menu icon from the Wii U Menu.
6. In the Wii Menu, select the `Wii` button in the bottom-left corner of the main screen. Then select `Data Management`, `Save Data`, then `Wii`.
7. Select the `SD` tab, select the game save shown for Skyward Sword, then select `Copy`. If save data for Skyward Sword already exists on your Wii/Wii U, you may need to delete the save from the `Wii` tab before you can copy the save data from the SD.
