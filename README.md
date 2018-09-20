# Upload to Cloudinary iOS Shortcut

## What it does

This is a [Shortcut](https://support.apple.com/guide/shortcuts/welcome/ios) that allows you to upload images and videos straight from your iOS device to [Cloudinary](https://cloudinary.com).

## Installation

<ol>
<li>Get the <code>.shortcut</code> file in this repository onto your iOS device, somehow? Or! Just <a href="https://www.icloud.com/shortcuts/4d17232b899b45c3835fa322d0332418">click here</a>!</li>
<li>It should ask you for your Cloudinary cloud name, API key, and API secret, which you can find under “Account Details” in your Cloudinary console dashboard:
<img src="https://eric-cloudinary-res.cloudinary.com/image/upload/v1537460430/Screen_Shot_2018-09-20_at_9.16.45_AM.png" alt="Highlighted screenshot of where to find this info" />
</li>
</ol>

## Usage

You can feed it images in two ways:

- **Shortcut, then image:** if you tap the Shortcut from within the Shortcuts App, it will prompt you to select a resource from your Photo Library.
- **Image, then Shortcut:** alternatively, it’s accessible from the “Shortcuts” action within an iOS share sheet. So you can feed it images and videos from places other than your photo library (e.g., from the web, within Safari).

Once the Shortcut runs, it’ll give you an alert reporting either success or failure. The success report also informs you that the URL to the newly uploaded resource has been copied to your clipboard.

## TODO

- Facilitate hooking this Shortcut up to others that want to *do* things with the freshly uploaded image. Maybe remove the alert? Definitely figure out what the result of the Shortcut is, when fed into other Shortcuts, and make it as useful as possible.
