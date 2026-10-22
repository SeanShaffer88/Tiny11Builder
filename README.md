> **Fork identity: development fork — distribution permission unresolved.** Derived from [ntdevlabs/tiny11builder](https://github.com/ntdevlabs/tiny11builder). The native WinUI work is present in the default branch, but [NOTICE.md](NOTICE.md) records unresolved permission for upstream material. No fork-specific packages are published by this audit. Upstream release links do not establish a download for this fork’s WinUI app. See [fork provenance](PROVENANCE.md) for ownership and reporting routes.

# Tiny11 Builder

Build a smaller Windows 11 ISO with a native WinUI app. Download an official
Windows image or use your own, choose what to remove, and create your ISO.

## Download

**No fork-specific WinUI download is advertised here.** Read [distribution restrictions](NOTICE.md) before packaging or redistribution. [Upstream releases](https://github.com/ntdevlabs/tiny11builder/releases) belong to ntdevlabs; they are not proof of a native WinUI package for this checkout.

The following sections describe source functionality. Architecture selections and executable names do not establish released packages or tested host compatibility. Running system-image operations requires administrator approval.

## Choose your build

| Mode | What it does |
| --- | --- |
| Tiny11 | Removes bundled apps and unwanted features while keeping updates, Defender and recovery. |
| Tiny11 Core | Trims further by removing servicing and recovery support and disabling Defender. |
| Custom | Choose individual apps, components, features and services to remove or keep. |

Turbo mode speeds up image processing. Interrupted builds can resume from saved
progress after the image is committed or compressed. Core and component-store
removals automatically use the legacy Windows installer.

**Core cannot be updated or serviced. Protected Custom removals can break
Windows. Test your ISO in a VM before installing it.**

## Video

[**Watch on YouTube**](https://youtu.be/LfEWIz5mQ8A)

## Screenshots

### Welcome

![Tiny11 Builder welcome screen with Tiny11, Tiny11 Core and Custom modes](docs/images/ui-welcome.png)

### Components

![Component choices and the Tiny11 Core warning](docs/images/ui-components.png)

### Build settings

![Build settings with Turbo mode and optional image cleanup](docs/images/ui-build-settings.png)

## More information

[Usage, compatibility and build instructions](docs/usage.md) ·
[Attribution and distribution notes](NOTICE.md)

The original PowerShell builders remain in this repository.

## Support the project

Tiny11 Builder is free. If it saved you time, you can help fund development,
testing across Windows releases and fixes for reported problems.

**[Monthly support](https://github.com/sponsors/ntdevlabs)** ·
**[One-time donation](https://ko-fi.com/ntdev)**

Prefer another service? [Patreon](https://www.patreon.com/ntdev) ·
[PayPal](https://paypal.me/ntdev2)

No donation is needed to use any feature. Reporting reproducible bugs,
testing builds in a VM and sharing the [demo](https://youtu.be/LfEWIz5mQ8A)
help too.

