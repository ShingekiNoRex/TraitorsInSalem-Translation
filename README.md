# Traitors in Salem - Translation
This is an unofficial translation repo for game [Traitors in Salem](https://store.steampowered.com/app/1497640/Traitors_in_Salem/).

Please feel free to ask questions or submit pull requests.


# How to install the translation replacer plugin

## Method #1:

1. Choose your language and download the latest `.rar` pack from [here](https://github.com/ShingekiNoRex/TraitorsInSalem-Translation/releases)

2. Extract to `steamapps\common\Traitors in Salem\`

## Method #2:

1. Download and install [BepInEX](https://github.com/BepInEx/BepInEx/releases)

2. Launch game for once then close

3. Download the latest `TiS_TranslationReplacer.dll` and `FontAsset-SIMYOU`(Optional) from [here](https://github.com/ShingekiNoRex/TownOfSalem-Translation/releases)

4. Put `ToS_TranslationReplacer.dll` into `Town of Salem\BepInEx\plugins`

    * (Optional) Put `FontAsset-SIMYOU` into `Town of Salem\TownOfSalem_Data\StreamingAssets`

5. Launch game again then close

6. Download `StringTable.{lang_code}.xml` in this repo
    * (i.e. `StringTable.zh-CN.xml` for Simplified Chinese)

7. Put `StringTable.{lang_code}.xml` into `Traitors in Salem\TraitorsInSalem_Data\StreamingAssets\Translation\{game_version}\`

8. Open `Traitors in Salem\BepInEx\config\TiS-TranslationReplacer.cfg` with notepad

9. Make sure the `Language` settings in `[General]` section has the same value as {lang_code}

# How to contribute
*Before contributing, a GitHub account is required - you can sign up for one [here](https://github.com/join). If you wish to contribute from your desktop (i.e. using a local text editor), a Git client is required. We recommend [GitHub Desktop](https://desktop.github.com/), which provides a GUI and is easier for novice users to use. However, any Git client will work - it is ultimately a matter of personal preference. For help with GitHub Desktop, refer to [the Help section here](https://help.github.com/en/desktop). If you wish to contribute directly through GitHub, please see the relevant section below.*
***
## From local editor:   
1. Create fork of this repository
    * Scroll to the top of this page and click 'Fork'. Doing so will add a copy of this repo to your GitHub account.
2. Clone the forked repository
    * Log into your GitHub account in GitHub Desktop. On the home screen, you will see a list of your repositories. Select the forked repo, and then click `Clone <yourusername>/TraitorsInSalem-Translation` - doing so will download the repo onto your computer. If you are using Git Bash or a similar CLI client, refer to [this guide](https://help.github.com/en/articles/fork-a-repo). 
3. Open a file and edit/add what you want to change with a text editor
4. Commit the modified files
   * Please include a meaningful commit describing exact changes that were made. This is helpful to us when reviewing Pull Requests and commit history.
    * __Only__ commit changes to files you've added/edited. **Don't** commit changes to `StringTable.en-US.xml`
   - Usually most GUI clients, such as GitHub desktop will only commit modified files. 
6. Push your commit(s) to GitHub
    * When changes are committed, only the files on disk (i.e. in the *cloned* repo) are modified. By pushing these commits, these changes are also reflected in the forked repository on GitHub. This is necessary for the next step:
7. Open a Pull Request (see below).
## From GitHub:
1. Open a desired file and click "Edit this file".
   - This will automatically create a fork of this repo to your account. Any changes made to files will only be reflected in the forked repo. Learn more about forking on GitHub [here](https://help.github.com/en/articles/about-forks)
2. Make any desired changes. 
3. Commit your changes with a meaningful message.
   * Please include a meaningful commit message describing the exact changes that were made. This is helpful to us when reviewing Pull Requests and commit history.
    * __Only__ commit changes to files you've edited. **Don't** commit changes to `StringTable.en-US.xml`
4. Open a Pull Request (see below).
## Opening a Pull Request
To merge your modified fork with the master, a Pull Request must be made. **Please ensure that you have committed and pushed all desired changes before opening a Pull Request.**
1. Return to this repo and click the **New pull request** button, located at the top of the page.
2. On the next page, click **compare across forks**.
3. Select the base and head forks
   * The *base* fork is the repository that you wish to merge changes into (i.e. this one!) and the *head* (or *compare*) fork is the repository that contains the said changes (i.e. your fork). Ensure that both the base and compare fields are set to **master**. 
  * In the event that you created further forks of this repository, please refer to [this guide](https://help.github.com/en/articles/creating-a-pull-request-from-a-fork) for further guidance.
4. Create your Pull Request.
   * **Ensure that the 'Allow edits from maintainers' is selected.**
   * Write a meaningful title and message for your pull request described the changes that have been made.


# Used libraries

- [BepInEX](https://github.com/BepInEx/BepInEx/)
- [BepInEx/HarmonyX](https://github.com/BepInEx/HarmonyX)
