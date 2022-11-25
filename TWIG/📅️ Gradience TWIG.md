## Announce #1

Adwaita Manager was significantly redesigned, Thanks for hard work of @0xMRTT who maked it real and @daudix-UFO for providing design mockups.

Adwaita Manager is a tool that allows you to customize Libadwaita applications and the adw-gtk3 theme with simple UI, as well with Material You Palette generation from wallpaper, Thanks @avanishsubbiah for porting Monet engine to Python!

Also, @ArtyIF has migrated Adwaita Manager to Adwaita Manager Team, which allowed to add new maintainers, @0xMRTT and @daudix-UFO

More amazing changes will come in near future!

## Announce #2

This week, Adwaita Manager have some improvements

- Project was renamed to "Gradience" to remove any confusion with official GNOME app

- Monet engine performance improved (2 sec in v0.2.0 and 2.5 minutes in v0.1.0)

- Fixed invisible text in "cards" when Monet palette was applied

- Added "Nightly" header bar and icon

- Small UI improvements

## Announce #3

`Nothing Here`

## Announce #4

After more than a month of hard developement, we happy to announce that Gradience is now avialable on [Flathub](https://flathub.org/apps/details/com.github.GradienceTeam.Gradience) 🎉

Thanks to all contributers who maked it real 🚀

Some changes in v0.2.0 - v0.2.1

- App published on Flathub (We submitted it at moment of publication last TWIG)
- Added perferences window for managing flatpak ovverides
- Added backup functionality for gtk.css to prevent loss of users current settings
- Various UI improvements

You can download v0.2.0 from [Flathub](https://flathub.org/apps/details/com.github.GradienceTeam.Gradience), or test newest versions by downloading [Nightly build](https://github.com/GradienceTeam/Gradience/actions/workflows/flatpak.yml)

## Announce #5

Gradience 0.3.0 is [Released](https://github.com/GradienceTeam/Gradience/releases), some of the new exiting features:

- Added plugins support, this allows creating plugins for customizing other apps
- Added support for custom repos, this allows creating own selection of presets
- Preset Manager performance are significantly enhanced, presets are downloading much faster and app don't freeze on preset removal
- Added search to Preset Manager
- Preset Manager is attached to the main window
- Added Quick Preset Switcher back, with it you can switch presets with less clicks
- Save dialog now shows up when you close app with unsaved preset
- Currently applied preset now auto-loads on app start-up
- Toasts are less annoying
- Added aarch64 builds

You can download Gradience v0.3.0 from [Flathub](https://flathub.org/apps/details/com.github.GradienceTeam.Gradience) or from [GitHub](https://github.com/GradienceTeam/Gradience)

## Announce #5 (Alt)

Gradience Team is happy to announce new version of Gradience - 0.3.0, this version is result of a month of hard work. This release introduces many new features and improvements.

- Added plugins support, this allows creating plugins for customizing other apps
- Preset Manager performance are significantly enhanced, presets are downloading much faster and app don't freeze on preset removal
- Added search to Preset Manager
- Community presets refactor
- Preset Manager is attached to the main window
- Added Quick Preset Switcher back, with it you can switch presets with less clicks
- Save dialog now shows up when you close app with unsaved preset
- Currently applied preset now auto-loads on app start-up
- Toasts now less annoying
- Added theming warning to Welcome screen
- Added Mini Welcome screen on update from previous version
- Translation updates
- Added aarch64 builds

###### Currently it sounds too "Advanced", it need to be more user friendly, there is no problem if you remove some of the features, as this is not changelog, this is just a small announcement. @daudix-UFO

## Announce #6

This week, Gradience gained some UI polish, usability and under-hood improvements, some of them:

- Preset Manager now opens immediately
- "Log Out" message after applying theme
- Improved UI of Preset Manager
    - Now presets can be starred
    - Added preset repo switcher with which you can display only presets from specific repo
- All contributors now listed in "About" window, **let us know if you are not listed**
- Text now follows GNOME Writing Guidelines
- Fixed flatpak theming
- Added repo template for user preset sharing

This changes will be available in version 0.3.1 that will be available on [Flathub](https://beta.flathub.org/apps/details/com.github.GradienceTeam.Gradience) very soon.

## Announce #7

Gradience 0.3.2 is out! This version fixes some major issues and introduces some under-the-hood improvements, as well as some new features, some of them are:

- Issues with the [Firefox GNOME theme](https://github.com/rafaelmardojai/firefox-gnome-theme) plugin under Flatpak are fixed
- CSS now loads correctly after applying a preset
- Fixed an issue with presets always being saved as `User.json`
- Presets are now removed correctly
- The internal structure was refactored
- Various typos were fixed
- The README was fully rewritten
- All screenshots are now in high resolution
- New and updated translations
