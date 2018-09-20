# Upload to Cloudinary iOS Shortcut

## What it does

This is a [Shortcut](https://support.apple.com/guide/shortcuts/welcome/ios) that allows you to upload images and videos straight from your iOS device to [Cloudinary](https://cloudinary.com).

## Installation

<ol>
<li>Get the <code>Upload to Cloudinary.shortcut</code> file in this repository onto your iOS device, somehow? Or! Just <a href="https://www.icloud.com/shortcuts/4d17232b899b45c3835fa322d0332418">click here</a>!</li>
<li>Upon importing, it should ask you for your Cloudinary cloud name, API key, and API secret, which you can find under “Account Details” in your Cloudinary console dashboard:
<img src="https://eric-cloudinary-res.cloudinary.com/image/upload/v1537460430/Screen_Shot_2018-09-20_at_9.16.45_AM.png" alt="Highlighted screenshot of where to find this info" />
</li>
</ol>

## Usage

You can feed it images in two ways:

- **Shortcut, then image:** if you tap the Shortcut from within the Shortcuts app, it will prompt you to select a resource from your Photo Library.
- **Image, then Shortcut:** alternatively, this Shortcut is accessible from the Shortcuts *action* within iOS share sheets. So you can feed it images and videos from places other than your Photo Library (e.g., from Safari/the web).

Once the Shortcut runs, it’ll give you an alert reporting either success or failure. The success report also informs you that the URL to the newly uploaded resource has been copied to your clipboard 🎉.

## TODO

- Facilitate hooking this Shortcut up to others that want to *do* things with the freshly uploaded image.
	- Maybe remove the alert?
	- Definitely figure out what the result of this Shortcut is, when fed into other Shortcuts – and make that output as useful as possible.
