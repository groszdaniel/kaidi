![kaidi-beta-logo](/docs/icons/kaidi_112.png)

# Kaidi Remote (Beta)

### The Kodi remote app for KaiOS (for now...)

| Supported KaiOS version | Supported Kodi version |
|:-----------------------:|:----------------------:|
|       >= KaiOS 2.5      |     >= Kodi Krypton    |

**PROJECT STATE: Beta (version 0.4.8)**

## Key features:

![kaidi-home-screen](/docs/screenshots/kaidi-home-screen.png)
![kaidi-player-screen](/docs/screenshots/kaidi-playing-screen.png)
![kaidi-settings-screen](/docs/screenshots/kaidi-settings-screen.png)

- Basic Kodi interface navigation (Up/Down/Left/Right/Context Menu/Home control).

- Kodi volume controls (increment, decrement, mute).

- A Kodi player control (Play/Pause/Set shuffle/Set repeat/Next/Previous/Wind forward/Wind backward).

- Notifications of now playing track (available if app is in background/screen off).

- Written in vanilla HTML/CSS/JS, no framework used, so we are quick ⏩.

## Building the app:

**To run:**

The app can be run directly from `src` for testing and debugging purposes, just point WebIDE/gDeploy/make-kaios-install to it and install.

**To build:**

- Run `npm install` to install dependencies.

- Run `gulp` (or `npm run_script build`) to generate a deployable minified app from the source to `./dist/deploy` (contains bare `application.zip` for KaiStore submission too). This will also generate an OmniSD-compatible package @ `.dist/omnisd/kaidi-*version number*-omnisd.zip`.

## You found a bug?

Please submit the bug to the [issues tracker](https://github.com/jkelol111/kaidi/issues).

## Want to help out?

Feel free to fork this repo and add your improvements, then create a pull request.

We are especially looking for improvements to the player, as well as added localizations.

We now enforce [Standard JS](https://standardjs.com/) since 27/3/2020. Some files might not have been modified to reflect this change yet, but please do practice Standard JS (use ESLint, installable if you run `npm install` to install our dev-dependencies) if you ever submit your pull requests/modifications for review. This doesn't mean we will reject your pull request, but for large changes, bad Standard JS compliance will lead to rejected pull requests.