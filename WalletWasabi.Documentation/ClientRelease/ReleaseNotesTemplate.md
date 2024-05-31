### _[Wasabi Wallet](https://WasabiWallet.io) is an easy to use, privacy-focused, open-source, non-custodial, Bitcoin wallet_

# Download
:window: [Windows](https://github.com/WalletWasabi/WalletWasabi/releases/download/v2.0.x/Wasabi-2.0.8.msi)
:green_apple: [Apple M1/M2](https://github.com/WalletWasabi/WalletWasabi/releases/download/v2.0.x/Wasabi-2.0.8-arm64.dmg)
:apple: [Apple Intel](https://github.com/WalletWasabi/WalletWasabi/releases/download/v2.0.x/Wasabi-2.0.8.dmg)
:penguin: [Ubuntu / Debian](https://github.com/WalletWasabi/WalletWasabi/releases/download/v2.0.x/Wasabi-2.0.8.deb)
:penguin: [Other Linux](https://github.com/WalletWasabi/WalletWasabi/releases/download/v2.0.x/Wasabi-2.0.8.tar.gz)

---
## Release Highlights
:pushpin: Exclude UTXOs from autocoinjoin
:earth_americas: Coordinator selection in GUI
:snowflake: Tor bridges
:boom: Tails & Whonix OS support
:floppy_disk: Install Linux udev rules for hardware wallets

## Release Summary

Wasabi Wallet v2.0.8 introduces new coinjoin tools and many long awaited accessibility options for advanced users. Additionally, Wasabi’s Github repository has transferred from zkSNACKs to its own self-named organization.

# Exclude UTXOs from autocoinjoin

Wasabi automatically selects inputs and outputs for users when they participate in a coinjoin transaction. The randomization of coin selection provides huge privacy benefits, but gives users limited flexibility.

An “exclude coins” menu option is now available from the coinjoin status box that allows users to restrict which coins are consumed as coinjoin inputs. This option was previously only available using the RPC.

# Coordinator selection in GUI

A new field in the application settings is now available which makes it easy for users to paste the connection information for their chosen coinjoin coordinator without needing to edit any config files. As of June 1st 2024, the default coinjoin coordination service provided by zkSNACKs is being discontinued.

# Tor bridges

Some ISPs limit their users’ access to the Tor network. Tor bridges are now supported in Wasabi which help overcome this obstacle.

# Tails & Whonix OS support

Tails and Whonix users can use Wasabi by switching their Tor connection option from Enabled to Enabled (connect-only mode) or by using the command line option: --UseTor=EnabledOnlyRunning

# Install Linux udev rules for hardware wallets

Hardware wallets require additional configuration of udev rules to use with Linux machines. Automatic installation of udev rules is now supported to streamline the setup of cold storage devices.

Read the [related blog](https://blog.wasabiwallet.io/) for more information.

---
## Installation Guide
Download the operating system relevant software package and install Wasabi like you would with any other software on your computer. 
For a detailed installation guide, including **signature verification**, see [the documentation](https://docs.wasabiwallet.io/using-wasabi/InstallPackage.html).

## Documentation
:spider_web: [Website](https://wasabiwallet.io)
:onion: [Tor onion site](http://wasabiukrxmkdgve5kynjztuovbg43uxcbcxn6y2okcrsg7gb6jdmbad.onion/)
:orange_book: [Documentation](https://docs.wasabiwallet.io)
:grey_question: [FAQ](https://github.com/WalletWasabi/WalletWasabi/discussions/categories/faq)

## Advanced Guide
If you want to build or update Wasabi from source code, check out [these easy instructions](https://docs.wasabiwallet.io/using-wasabi/BuildSource.html).

Wasabi uses [reproducible builds](https://reproducible-builds.org/), which you can verify with [this guide](https://github.com/WalletWasabi/WalletWasabi/blob/master/WalletWasabi.Documentation/Guides/DeterministicBuildGuide.md).

## Requirements
- Windows 10 1607+
- Windows 11 22000+
- macOS 12.0+
- Ubuntu 22.04+
- Fedora 37+
- Debian 11+
---

## Full Changelog
