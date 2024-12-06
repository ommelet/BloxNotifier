<p align="center">
    <img src="https://github.com/ommelet/BloxNotifier/blob/ac7a9b0d5057d69fba38e803e07cecb2942501a3/Images/logo_dark.png#gh-dark-mode-only" width="840">
    <img src="https://github.com/ommelet/BloxNotifier/blob/ac7a9b0d5057d69fba38e803e07cecb2942501a3/Images/logo_light.png#gh-light-mode-only" width="840">
</p>

<div align="center">

</div>

----

BloxNotifier is a bot that delivers notifications for Welcome to Bloxburg updates, offering detailed information on games, users, and more, enhancing your Roblox experience.

This bot is currently under development, and errors may occur. If you encounter any issues, please reach out to us via our [Discord Server](https://img.shields.io/discord/1313318679072473109?logo=discord&logoColor=white&label=discord&color=4d3dff) for assistance.

## Frequently Asked Questions

**Q: What does this bot do?**

**A:** The bot sends notifications about updates for *Welcome to Bloxburg* and provides information about Roblox users, games, and groups.

**Q: Can I customize update notifications?**

**A:** You can personalize your notifications by setting the language, adjusting notification intervals, deciding whether messages include mentions, and more. All of this can be configured using the `/config setup` command.

**Q: Can the bot be used in private messages?

**A:** Yes, the bot works seamlessly in both servers and direct messages. You can configure it to send notifications to the channel or DM that suits you best.

**Q: How can I report bugs or suggest features?

**A:** If you encounter any issues or have ideas for improvements, you can use the `/bot support` command. This allows you to submit bug reports or suggestions, and even attach images to provide more context.


## Features

- Hassle-free Discord Rich Presence to let your friends know what you're playing at a glance
- Simple support for modding of content files for customizability (death sound, mouse cursor, etc)
- See where your server is geographically located (courtesy of [ipinfo.io](https://ipinfo.io))
- Ability to configure graphics fidelity and UI experience

## Installing
Download the [latest release of Bloxstrap](https://github.com/bloxstraplabs/bloxstrap/releases/latest), and run it. Configure your preferences if needed, and install. That's about it!

Alternatively, you can install Bloxstrap via [Winget](https://winstall.app/apps/pizzaboxer.Bloxstrap) by running this in a Command Prompt window:
```
> winget install bloxstrap
```

You will also need the [.NET 6 Desktop Runtime](https://aka.ms/dotnet-core-applaunch?missing_runtime=true&arch=x64&rid=win11-x64&apphost_version=6.0.16&gui=true). If you don't already have it installed, you'll be prompted to install it anyway. Be sure to install Bloxstrap after you've installed this.

It's not unlikely that Windows Smartscreen will show a popup when you run Bloxstrap for the first time. This happens because it's an unknown program, not because it's actually detected as being malicious. To dismiss it, just click on "More info" and then "Run anyway".

Once installed, Bloxstrap is added to your Start Menu, where you can access the menu and reconfigure your preferences if needed.

## Code

Bloxstrap uses the [WPF UI](https://github.com/lepoco/wpfui) library for the user interface design. We currently use and maintain our own fork of WPF UI at [bloxstraplabs/wpfui](https://github.com/bloxstraplabs/wpfui).

