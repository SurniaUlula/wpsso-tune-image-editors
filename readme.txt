=== WPSSO Tune WP Image Editors ===
Plugin Name: WPSSO Tune WP Image Editors
Plugin Slug: wpsso-tune-image-editors
Text Domain: wpsso-tune-image-editors
Domain Path: /languages
License: GPLv3
License URI: https://www.gnu.org/licenses/gpl.txt
Assets URI: https://surniaulula.github.io/wpsso-tune-image-editors/assets/
Tags: image, sharpen, imagemagick, imagick, resize
Contributors: jsmoriss
Requires PHP: 7.0
Requires At Least: 4.5
Tested Up To: 5.7
Stable Tag: 2.7.1

Improves the appearance of WordPress images for better click-through-rates from social and search sites.

== Description ==

<p><img class="readme-icon" src="https://surniaulula.github.io/wpsso-tune-image-editors/assets/icon-256x256.png"> <strong>Have you noticed that WordPress creates small images that seems a bit "fuzzy" &mdash; nothing like the nice sharp original you uploaded?</strong></p>

The reason is that after an image is resized, that image *must* be sharpened &mdash; but WordPress doesn't do any sharpening, so the resized image remains a bit "fuzzy" &mdash; not what you want for a featured image or shared image on social sites! ;-)

The WPSSO Tune WP Image Editors (aka WPSSO TIE) add-on provides this missing WordPress feature &mdash; it automatically applies sharpening to all JPEG images resized by the WordPress ImageMagick library.

**Compatible with all image compression / optimization plugins:**

Image sharpening / adjustments are applied during the WordPress image resize operation, so the resulting resized image / thumbnail can be optimized afterwards as usual.

<h3>Users Love the WPSSO TIE Add-on</h3>

&#x2605;&#x2605;&#x2605;&#x2605;&#x2605; &mdash; "This plugin helped me tune my images to look really good on social media. Great job!" - [undergroundnetwork](https://wordpress.org/support/topic/really-useful-at-making-your-social-media-images-the-best/)

<h3>WPSSO TIE Add-on Features</h3>

Extends the features of the [WPSSO Core plugin](https://wordpress.org/plugins/wpsso/) (required plugin).

Applies adjustments to resized images (aka thumbnails) using ImageMagick:

* Enable or disable image adjustments / sharpening for resized images.
* Uses a better compression quality of 92% (WordPress default is 82%).
* Applies a default amount of sharpening values to all resized images.

Optionally select different primary / secondary image editor(s) for WordPress:

* GD Only
* GD and ImageMagick
* ImageMagick Only
* ImageMagick and GD (WordPress default)

Optionally fine-tune the image filter priority and image adjustment options:

* Modify the default 'image_make_intermediate_size' filter hook priority.
* Enable / disable contrast leveling.
* Increase / decrease the compression quality percentage.
* Adjust sharpening values individually (sigma, radius, amount, threshold).

<h3>WPSSO Core Plugin Required</h3>

WPSSO Tune WP Image Editors (aka WPSSO TIE) is an add-on for the [WPSSO Core plugin](https://wordpress.org/plugins/wpsso/). WPSSO Core and its add-ons make sure your content looks best on social sites and in search results, no matter how webpages are shared, re-shared, messaged, posted, embedded, or crawled.

== Installation ==

<h3 class="top">Install and Uninstall</h3>

* [Install the WPSSO Tune WP Image Editors add-on](https://wpsso.com/docs/plugins/wpsso-tune-image-editors/installation/install-the-plugin/).
* [Uninstall the WPSSO Tune WP Image Editors add-on](https://wpsso.com/docs/plugins/wpsso-tune-image-editors/installation/uninstall-the-plugin/).

== Frequently Asked Questions ==

== Screenshots ==

01. WPSSO TIE settings page to select the default WordPress image editors and fine-tune the ImageMagick PHP extension.

== Changelog ==

<h3 class="top">Version Numbering</h3>

Version components: `{major}.{minor}.{bugfix}[-{stage}.{level}]`

* {major} = Major structural code changes / re-writes or incompatible API changes.
* {minor} = New functionality was added or improved in a backwards-compatible manner.
* {bugfix} = Backwards-compatible bug fixes or small improvements.
* {stage}.{level} = Pre-production release: dev < a (alpha) < b (beta) < rc (release candidate).

<h3>Standard Version Repositories</h3>

* [GitHub](https://surniaulula.github.io/wpsso-tune-image-editors/)
* [WordPress.org](https://plugins.trac.wordpress.org/browser/wpsso-tune-image-editors/)

<h3>Changelog / Release Notes</h3>

**Version 2.7.1 (2021/02/25)**

* **New Features**
	* None.
* **Improvements**
	* Updated the banners and icons of WPSSO Core and its add-ons.
* **Bugfixes**
	* None.
* **Developer Notes**
	* None.
* **Requires At Least**
	* PHP v7.0.
	* WordPress v4.5.
	* WPSSO Core v8.23.0.

**Version 2.7.0 (2020/12/04)**

* **New Features**
	* None.
* **Improvements**
	* None.
* **Bugfixes**
	* None.
* **Developer Notes**
	* Included the `$addon` argument for library class constructors.
* **Requires At Least**
	* PHP v7.0.
	* WordPress v4.5.
	* WPSSO Core v8.16.0.

**Version 2.6.1 (2020/10/17)**

* **New Features**
	* None.
* **Improvements**
	* Refactored the add-on class to extend a new WpssoAddOn abstract class.
* **Bugfixes**
	* Fixed backwards compatibility with older 'init_objects' and 'init_plugin' action arguments.
* **Developer Notes**
	* Added a new WpssoAddOn class in lib/abstracts/add-on.php.
	* Added a new SucomAddOn class in lib/abstracts/com/add-on.php.
* **Requires At Least**
	* PHP v5.6.
	* WordPress v4.4.
	* WPSSO Core v8.13.0.

== Upgrade Notice ==

= 2.7.1 =

(2021/02/25) Updated the banners and icons of WPSSO Core and its add-ons.

= 2.7.0 =

(2020/12/04) Included the `$addon` argument for library class constructors.

= 2.6.1 =

(2020/10/17) Refactored the add-on class to extend a new WpssoAddOn abstract class.

