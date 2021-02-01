<div align="center">
    <img src="pix/ompdf-logo.png">
</div>

# OMPDF (Onyet Activity:Moodle - PDF Folder)

How PDFs are opened in browsers seem to depend on many things, like which
browser the user is using, the configuration of PDF readers and which
operating system is being used. To a smaller degree, it depends on the
settings in Moodle.

In most cases, the handling of PDFs should be left under the control of
the user but in some cases there are valid reasons to try to standardize
the experience.

OMPDF is a Moodle 3.10+ plugin intended to make sure that PDFs always
open in the browser (with the option of downloading), regardless of if the
user is using a desktop or mobile device.

## OMPDF is built on [PDF.js](https://github.com/mozilla/pdf.js):

* PDF.js is Portable Document Format (PDF) viewer that is built with HTML5.
* PDF.js is community-driven and supported by Mozilla Labs. Our goal is to create a general-purpose, web standards-based platform for parsing and rendering PDFs.
* PDF.js will not work in all browsers, [most notably IE8 and below](https://github.com/mozilla/pdf.js/wiki/Frequently-Asked-Questions#what-browsers-are-supported).
* PDF.js, at the moment, performs rather poorly on mobile devices with limited memory and processing power (which covers almost all devices out there, new and old). Some PDFs are fine but others are too big, to complex, contain too many images, etc. Your mileage may vary.

OMPDF works much like the regular folder resource in Moodle and handles
images as well as PDFs (for practical reasons). Zip files can be uploaded and
unpacked.

There are a few options:

    * Should PDFs open in the current tab/window or open in a new tab/window?
    * Should folder contents be shown inline on the course page or on a separate page?
    * Should subfolders be shown expanded or not?
    * Should download links be displayed for each PDF so that users with devices not capable of displaying all PDFs through PDF.js have another option?

## Example

[![Youtube Video](https://img.youtube.com/vi/oDLCNRJa9YI/0.jpg)](https://www.youtube.com/watch?v=oDLCNRJa9YI)

Klick to play video sample.

## Installation

Unzip the zip file in the `mod` folder of the Moodle directory and, if
necessary, rename the folder to "OMPDF".
-- OR --
Go to Administration > Site Administration > Install add-ons to install
the "OMPDF" (mod_OMPDF) module directly from your Moodle
installation.

Default settings can be set by going to Administration > Site
Administration > Plugins > Activity Modules > OMPDF.

## Note

OMPDF base on PDF.jS Folder, write by [Jonas Nockert](https://moodle.org/plugins/mod_pdfjsfolder).

## Use

See the LICENSE file for licensing details.
