Lutris scripts for the installation of the GOG versions of the following games. The scripts install the games and apply different patches (like the popular REbirth patch) to make the games work flawlessly on Steam Deck.


- Resident Evil (1996)
  - Classic REbirth
  - Unofficial MediaKite 1.01 patch for USA
  - HQ movie pack
- Resident Evil 2 (1998)
  - Classic REbirth
  - SourceNext 1.1.0 official patch
- Resident Evil 3 (1999)
  - Classic REbirth
  - SourceNext 1.1.0 official patch
- Dino Crisis (1999)
  - Classic REbirth
  - Windows XP patch
  - HQ movie pack
  - HQ audio pack
  - HQ texture pack
- Dino Crisis 2 (2000)
  - Classic REbirth
  - Windows XP patch
  - HQ movie pack
  - HQ audio pack

## **Install Guide for Steam Deck**

1. Switch to Desktop Mode on Steam Deck.

2. Download the setup files (`.bin` and `.exe`) for the game you want to install from your GOG account.

3. Download the install script (a `.yaml` file) for the game you want to install from this repository's `scripts` folder.

4. Install `Lutris` from the Discover Store.

5. Run `Lutris` and click the + sign to add a game.

6. Select `Install from local install script` and point to the yaml file you downloaded in step 3. Then click `Install` and `Install` again on the next screen.

7. Choose where to install the game. The default is fine unless you want to change it. Also click `Create steam shortcut` so the game will be available in your library in Game Mode. Click Continue.

8. Click the `...` button under `GOG setup exe` and select the setup exe file from step 2. (Note: for Dino Crisis 1+2 you also need to download the HQ (audio, video, texture) packs manually and link the files here.)

9. Click `Install` and let it do it's thing.

10. Done! When you now launch the game you should get the REbirth settings window.