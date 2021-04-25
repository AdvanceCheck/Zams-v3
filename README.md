# Zams-v3

Zams is a free MacOS, Windows, and linux Discord-RPC!

# I AM NOT RESPONSIBLE FOR ANYTHING YOU MAY DO WITH THIS SOFTWARE! USE WITH CAUTION!

What is needed:

Node.js --> https://nodejs.org/en/download/current/

Atom --> https://atom.io/

Git --> https://git-scm.com/

Keep this tab open --> https://discord.com/developers/applications

The Discord Rich Presence Download --> https://mega.nz/file/6dMD1AxA#YQUyRumnIjl9dQi5aG2-X3aRi4Jv-5eUFFIc4h2uxRg

--------

# DISCORD TEXT AND IMAGES

1. First, create an application at Discord's New App page. (https://discord.com/developers/applications)
2. Set the App Name to the title of your Rich Presence playing status. For example, if you want `Playing with discord`, set the app name to `with discord`. You don't need to set a Redirect URI, Description, or App Icon, just click Create App.
[[https://github.com/NotTez/Zams-v3/blob/main/ez.png]]

# UPLOADING IMAGES

Now you can upload your images.
Go back to Discord Applications, go here.
[[https://github.com/NotTez/Zams-v3/blob/main/rich.png]]
Add images at Art Assets.

# SETTING UP CONFIG

1. Now that you have uploaded your images and set a title, it's time to set up your Rich Presence.
2. Go back to the file where Zams is.
3. Duplicate the `config.json.example` file, then rename it to `config.json`.
4. Now, open `config.json` in a code editor. (Atom)
5. Edit the Client ID only, and you can find that on your bot in Discord Applications.

# INSTRUCTIONS

1. If you're on Mac/Linux, open Terminal. On Windows, go to the Start Menu, type in `cmd.exe` and press Enter.
2. Run `git clone https://github.com/justdotJS/SimplePresence.git` to download the repo.
3. Run `cd Zams` to go to the folder.
4. Run (Windows only) copy `config.json.example config.json` or (on macOS/Linux) `cp config.json.example config.json` to initialise the configuration.
5. Run `npm install` to install all the requirements.
6. Open a file browser - this could be Finder on Mac or Windows Explorer.
7. Now, go to the folder where Zams was downloaded.
8. Open `config.json` with the Atom app.
9. If you'd like different default text, change the values of the stuff inside textConfig. For example, changing state to "hi" will make "hi" be the text used by default on the start of Zams.
10. Save `config.json` and close Atom.
11. Make sure Discord is running (only one - you can't have more than one open!)
12. Go back to Cmd or Terminal, and run `npm run custom`.

# You have successfully set up and started Zams!

# Support

If you need help, join our discord server! --> https://discord.gg/NTQWFwxqRb

