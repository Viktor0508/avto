/*!
Theme Name: News Hub
Theme URI: https://adorethemes.com/downloads/news-hub/
Author: Adore Themes
Author URI: https://adorethemes.com/
Description: News Hub is a clean and elegantly designed multipurpose WordPress theme perfect for dynamic news, newspapers, magazine, publishers, blogs, editors, online and gaming magazines, newsportals,personal blogs, publishing or review site and any new-related websites. The modern and professional design is easy and quick to set up, especially with pre-built demo. The theme is fully widgetized & customize based theme, so users can manage the content by using widgets and live WordPress customizer. It is fully responsive and works flawlessly on all types of devices like mobiles, tablets, laptops, and computers. It is a simple, easy-to-use, modern and creative, user-friendly WordPress magazine theme. The codes included in the theme are made SEO-friendly so that people can easily notice you and you get more visitors. The clean and secure HTML codes of this theme make your website function smoothly on several platforms and as these are optimized codes, your website will have a faster page load time to load quickly. Live preview : https://demo.adorethemes.com/news-hub/
Version: 1.0.6
Requires at least: 5.0
Requires PHP: 5.6
Tested up to: 6.1
License: GNU General Public License v3 or later
License URI: http://www.gnu.org/licenses/gpl-3.0.html
Text Domain: news-hub
Tags: custom-background, custom-header, custom-logo, custom-menu, featured-images, footer-widgets, left-sidebar, right-sidebar, blog, one-column, portfolio, photography, theme-options, threaded-comments, translation-ready

This theme, like WordPress, is licensed under the GPL.
Use it to make something cool, have fun, and share what you've learned.

News Hub is based on Underscores https://underscores.me/, (C) 2012-2020 Automattic, Inc.
Underscores is distributed under the terms of the GNU GPL v2 or later.

Normalizing styles have been helped along thanks to the fine work of
Nicolas Gallagher and Jonathan Neal https://necolas.github.io/normalize.css/
*/

/*--------------------------------------------------------------
>>> TABLE OF CONTENTS:
----------------------------------------------------------------
# Generic
	- Normalize
	- Box sizing
# Base
	- Typography
	- Elements
	- Links
	- Forms
## Layouts
# Components
	- Navigation
	- Posts and pages
	- Comments
	- Widgets
	- Media
	- Captions
	- Galleries
# plugins
	- Jetpack infinite scroll
# Utilities
	- Accessibility
	- Alignments

--------------------------------------------------------------*/

/*--------------------------------------------------------------
# Generic
--------------------------------------------------------------*/

/* Normalize
--------------------------------------------- */

/*! normalize.css v8.0.1 | MIT License | github.com/necolas/normalize.css */

/* Document
	 ========================================================================== */

/**
 * 1. Correct the line height in all browsers.
 * 2. Prevent adjustments of font size after orientation changes in iOS.
 */
/* Root
	========================================================================== */
:root {
	--primary-color: #4b7bec;
	--color-text: #191B1D;
	--color-dark: #424242;
	--color-background: #fff;
	--color-text-rgb: 32, 33, 36;
	--shadow: 0 8px 20px rgba(0, 0, 0, 0.2);

	/* fonts size---------------------------------------------------- */
	--font-size-xs: clamp(0.7rem, 0.17vw + 0.76rem, 0.79rem);
	--font-size-sm: clamp(0.8rem, 0.17vw + 0.76rem, 0.89rem);
	--font-size-base: clamp(1rem, 0.34vw + 0.91rem, 1.19rem);
	--font-size-md: clamp(1.25rem, 0.61vw + 1.1rem, 1.58rem);
	--font-size-lg: clamp(1.56rem, 1vw + 1.31rem, 2.11rem);
	--font-size-xl: clamp(1.95rem, 1.56vw + 1.56rem, 2.81rem);
	--font-size-xxl: clamp(2.44rem, 2.38vw + 1.85rem, 3.75rem);
	--font-size-xxxl: clamp(2.95rem, 3.54vw + 2.17rem, 5rem);
	/* fonts size---------------------------------------------------- */

	/* font family */
	--font-head: 'Roboto', serif;
	--font-body: "Muli", sans-serif;
}

.light-mode {
	--color-text: #191B1D;
	--color-dark: #424242;
	--color-light: #f7f7f7;
	--color-background: #fff;
	--color-text-rgb: 32, 33, 36;
}

.dark-mode {
	--color-text: #fff;
	--color-dark: #111111;
	--color-light: #2a2a2a;
	--color-background: #191B1D;
	--color-text-rgb: 255, 255, 255;
}

body {
	background-color: var(--color-background);
}

body.custom-background.dark-mode {
	background-color: var(--color-background);
}

/* Root
	========================================================================== */

html {
	line-height: 1.15;
	-webkit-text-size-adjust: 100%;
}

/* Sections
	 ========================================================================== */

/**
 * Remove the margin in all browsers.
 */
body {
	margin: 0;
	font-size: 1rem;
}

/**
 * Render the `main` element consistently in IE.
 */
main {
	display: block;
}

/**
 * Correct the font size and margin on `h1` elements within `section` and
 * `article` contexts in Chrome, Firefox, and Safari.
 */
h1 {
	font-size: 2em;
	margin: 0.67em 0;
}

/* Grouping content
	 ========================================================================== */

/**
 * 1. Add the correct box sizing in Firefox.
 * 2. Show the overflow in Edge and IE.
 */
hr {
	box-sizing: content-box;
	height: 0;
	overflow: visible;
}

/**
 * 1. Correct the inheritance and scaling of font size in all browsers.
 * 2. Correct the odd `em` font sizing in all browsers.
 */
pre {
	font-family: monospace, monospace;
	font-size: 1em;
}

/* Text-level semantics
	 ========================================================================== */

/**
 * Remove the gray background on active links in IE 10.
 */
a {
	background-color: transparent;
}

/**
 * 1. Remove the bottom border in Chrome 57-
 * 2. Add the correct text decoration in Chrome, Edge, IE, Opera, and Safari.
 */
abbr[title] {
	border-bottom: none;
	text-decoration: underline;
	text-decoration: underline dotted;
}

/**
 * Add the correct font weight in Chrome, Edge, and Safari.
 */
b,
strong {
	font-weight: bolder;
}

/**
 * 1. Correct the inheritance and scaling of font size in all browsers.
 * 2. Correct the odd `em` font sizing in all browsers.
 */
code,
kbd,
samp {
	font-family: monospace, monospace;
	font-size: 1em;
}

/**
 * Add the correct font size in all browsers.
 */
small {
	font-size: 80%;
}

/**
 * Prevent `sub` and `sup` elements from affecting the line height in
 * all browsers.
 */
sub,
sup {
	font-size: 75%;
	line-height: 0;
	position: relative;
	vertical-align: baseline;
}

sub {
	bottom: -0.25em;
}

sup {
	top: -0.5em;
}

/* Embedded content
	 ========================================================================== */

/**
 * Remove the border on images inside links in IE 10.
 */
img {
	border-style: none;
}

/* Forms
	 ========================================================================== */

/**
 * 1. Change the font styles in all browsers.
 * 2. Remove the margin in Firefox and Safari.
 */
button,
input,
optgroup,
select,
textarea {
	font-family: inherit;
	font-size: 100%;
	line-height: 1.15;
	margin: 0;
}

/**
 * Show the overflow in IE.
 * 1. Show the overflow in Edge.
 */
button,
input {
	overflow: visible;
}

/**
 * Remove the inheritance of text transform in Edge, Firefox, and IE.
 * 1. Remove the inheritance of text transform in Firefox.
 */
button,
select {
	text-transform: none;
}

/**
 * Correct the inability to style clickable types in iOS and Safari.
 */
button,
[type="button"],
[type="reset"],
[type="submit"] {
	-webkit-appearance: button;
	font-size: var(--font-size-sm);
	border: 1px solid;
	border-color: var(--primary-color);
	background: var(--primary-color);
	border-radius: 3px;
	color: #fff;
	line-height: 1;
	padding: 0.6em 1em;
}

button:focus,
input[type="button"]:focus,
input[type="reset"]:focus,
input[type="submit"]:focus,
button:hover,
input[type="button"]:hover,
input[type="reset"]:hover,
input[type="submit"]:hover {
	opacity: 0.8;
}

/**
 * Remove the inner border and padding in Firefox.
 */
button::-moz-focus-inner,
[type="button"]::-moz-focus-inner,
[type="reset"]::-moz-focus-inner,
[type="submit"]::-moz-focus-inner {
	border-style: none;
	padding: 0;
}

/**
 * Restore the focus styles unset by the previous rule.
 */
button:-moz-focusring,
[type="button"]:-moz-focusring,
[type="reset"]:-moz-focusring,
[type="submit"]:-moz-focusring {
	outline: 1px dotted ButtonText;
}

/**
 * Correct the padding in Firefox.
 */
fieldset {
	padding: 0.35em 0.75em 0.625em;
}

/**
 * 1. Correct the text wrapping in Edge and IE.
 * 2. Correct the color inheritance from `fieldset` elements in IE.
 * 3. Remove the padding so developers are not caught out when they zero out
 *		`fieldset` elements in all browsers.
 */
legend {
	box-sizing: border-box;
	color: inherit;
	display: table;
	max-width: 100%;
	padding: 0;
	white-space: normal;
}

/**
 * Add the correct vertical alignment in Chrome, Firefox, and Opera.
 */
progress {
	vertical-align: baseline;
}

/**
 * Remove the default vertical scrollbar in IE 10+.
 */
textarea {
	overflow: auto;
}

/**
 * 1. Add the correct box sizing in IE 10.
 * 2. Remove the padding in IE 10.
 */
[type="checkbox"],
[type="radio"] {
	box-sizing: border-box;
	padding: 0;
}

/**
 * Correct the cursor style of increment and decrement buttons in Chrome.
 */
[type="number"]::-webkit-inner-spin-button,
[type="number"]::-webkit-outer-spin-button {
	height: auto;
}

/**
 * 1. Correct the odd appearance in Chrome and Safari.
 * 2. Correct the outline style in Safari.
 */
[type="search"] {
	-webkit-appearance: textfield;
	outline-offset: -2px;
}

/**
 * Remove the inner padding in Chrome and Safari on macOS.
 */
[type="search"]::-webkit-search-decoration {
	-webkit-appearance: none;
}

/**
 * 1. Correct the inability to style clickable types in iOS and Safari.
 * 2. Change font properties to `inherit` in Safari.
 */
::-webkit-file-upload-button {
	-webkit-appearance: button;
	font: inherit;
}

/* Interactive
	 ========================================================================== */

/*
 * Add the correct display in Edge, IE 10+, and Firefox.
 */
details {
	display: block;
}

/*
 * Add the correct display in all browsers.
 */
summary {
	display: list-item;
}

/* Misc
	 ========================================================================== */

/**
 * Add the correct display in IE 10+.
 */
template {
	display: none;
}

/**
 * Add the correct display in IE 10.
 */
[hidden] {
	display: none;
}

/* Box sizing
--------------------------------------------- */

/* Inherit box-sizing to more easily change it's value on a component level.
@link http://css-tricks.com/inheriting-box-sizing-probably-slightly-better-best-practice/ */
*,
*::before,
*::after {
	box-sizing: inherit;
}

html {
	box-sizing: border-box;
}

/*--------------------------------------------------------------
# Base
--------------------------------------------------------------*/

/* Typography
--------------------------------------------- */
body,
button,
input,
select,
optgroup,
textarea {
	color: var(--color-text);
	font-family: var(--font-body);
	font-size: 1rem;
	line-height: 1.5;
}

h1,
h2,
h3,
h4,
h5,
h6 {
	clear: both;
}

p {
	margin-bottom: 1.5em;
}

dfn,
cite,
em,
i {
	font-style: italic;
}

blockquote {
	margin: 0 1.5em;
}

address {
	margin: 0 0 1.5em;
}

pre {
	background: #eee;
	font-family: "Courier 10 Pitch", courier, monospace;
	line-height: 1.6;
	margin-bottom: 1.6em;
	max-width: 100%;
	overflow: auto;
	padding: 1.6em;
}

.dark-mode pre {
	background-color: var(--color-dark);
}

code,
kbd,
tt,
var {
	font-family: monaco, consolas, "Andale Mono", "DejaVu Sans Mono", monospace;
}

abbr,
acronym {
	border-bottom: 1px dotted #666;
	cursor: help;
}

mark,
ins {
	background: #fff9c0;
	text-decoration: none;
}

big {
	font-size: 125%;
}

/* Elements
--------------------------------------------- */

hr {
	background-color: #ccc;
	border: 0;
	height: 1px;
	margin-bottom: 1.5em;
}

ul,
ol {
	margin: 0 0 1.5em 3em;
}

ul {
	list-style: disc;
}

ol {
	list-style: decimal;
}

li>ul,
li>ol {
	margin-bottom: 0;
	margin-left: 1.5em;
}

dt {
	font-weight: 700;
}

dd {
	margin: 0 1.5em 1.5em;
}

/* Make sure embeds and iframes fit their containers. */
embed,
iframe,
object {
	max-width: 100%;
}

img {
	height: auto;
	max-width: 100%;
}

figure {
	margin: 1em 0;
}

table {
	margin: 0 0 1.5em;
	width: 100%;
}

/* Links
--------------------------------------------- */
a {
	color: #4169e1;
}

a:visited {
	color: #800080;
}

a:hover,
a:focus,
a:active {
	color: #191970;
}

a:focus {
	outline: thin dotted;
}

a:hover,
a:active {
	outline: 0;
}

ul.social-links {
	margin: 0;
	padding: 0;
	list-style: none;
	display: flex;
	gap: 10px;
}

.author-social-contacts a,
ul.social-links a {
	width: 20px;
	height: 20px;
	opacity: 0.8;
	display: flex;
	font-size: 16px;
	overflow: hidden;
	position: relative;
	align-items: center;
	text-decoration: none;
	justify-content: center;
	transition: all 0.3s ease;
	color: var(--color-text);
}

.author-social-contacts a:focus,
.author-social-contacts a:hover,
ul.social-links a:focus,
ul.social-links a:hover {
	color: var(--primary-color);
}

.author-social-contacts a::before,
ul.social-links a::before {
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	font-style: normal;
	font-variant: normal;
	font-weight: 400;
	line-height: 1;
	font-family: 'Font Awesome 5 brands';
	vertical-align: baseline;
	transition: all, ease, 0.3s;
}

.author-social-contacts a[href*='facebook.com']::before,
ul.social-links a[href*='facebook.com']::before {
	content: "\f39e";
}

.author-social-contacts a[href*='twitter.com']::before,
ul.social-links a[href*='twitter.com']::before {
	content: "\f099";
}

.author-social-contacts a[href*='instagram.com']::before,
ul.social-links a[href*='instagram.com']::before {
	content: "\f16d";
}

.author-social-contacts a[href*='youtube.com']::before,
ul.social-links a[href*='youtube.com']::before {
	content: "\f167";
}

.author-social-contacts a[href*='discord.com']::before,
ul.social-links a[href*='discord.com']::before {
	content: "\f392";
}

.author-social-contacts a[href*='dribbble.com']::before,
ul.social-links a[href*='dribbble.com']::before {
	content: "\f17d";
}

.author-social-contacts a[href*='google.com']::before,
ul.social-links a[href*='google.com']::before {
	content: "\f1a0";
}

.author-social-contacts a[href*='line.me']::before,
ul.social-links a[href*='line.me']::before {
	content: "\f3c0";
}

.author-social-contacts a[href*='linkedin.com']::before,
ul.social-links a[href*='linkedin.com']::before {
	content: "\f08c";
}

.author-social-contacts a[href*='medium.com']::before,
ul.social-links a[href*='medium.com']::before {
	content: "\f23a";
}

.author-social-contacts a[href*='messenger.com']::before,
ul.social-links a[href*='messenger.com']::before {
	content: "\f39f";
}

.author-social-contacts a[href*='paypal.com']::before,
ul.social-links a[href*='paypal.com']::before {
	content: "\f1ed";
}

.author-social-contacts a[href*='pinterest.com']::before,
ul.social-links a[href*='pinterest.com']::before {
	content: "\f0d2";
}

.author-social-contacts a[href*='reddit.com']::before,
ul.social-links a[href*='reddit.com']::before {
	content: "\f1a1";
}

.author-social-contacts a[href*='skype.com']::before,
ul.social-links a[href*='skype.com']::before {
	content: "\f17e";
}

.author-social-contacts a[href*='slack.com']::before,
ul.social-links a[href*='slack.com']::before {
	content: "\f198";
}

.author-social-contacts a[href*='snapchat.com']::before,
ul.social-links a[href*='snapchat.com']::before {
	content: "\f2ad";
}

.author-social-contacts a[href*='spotify.com']::before,
ul.social-links a[href*='spotify.com']::before {
	content: "\f1bc";
}

.author-social-contacts a[href*='stackoverflow.com']::before,
ul.social-links a[href*='stackoverflow.com']::before {
	content: "\f16c";
}

.author-social-contacts a[href*='telegram.org']::before,
ul.social-links a[href*='telegram.org']::before {
	content: "\f3fe";
}

.author-social-contacts a[href*='twitch.tv']::before,
ul.social-links a[href*='twitch.tv']::before {
	content: "\f1e8";
}

.author-social-contacts a[href*='vimeo.com']::before,
ul.social-links a[href*='vimeo.com']::before {
	content: "\f27d";
}

.author-social-contacts a[href*='whatsapp.com']::before,
ul.social-links a[href*='whatsapp.com']::before {
	content: "\f232";
}

.author-social-contacts a[href*='wordpress.org']::before,
ul.social-links a[href*='wordpress.org']::before {
	content: "\f19a";
}

.author-social-contacts a[href*='youtube.com']::before,
ul.social-links a[href*='youtube.com']::before {
	content: "\f167";
}

.author-social-contacts a:focus,
ul.social-links a:focus,
.author-social-contacts a:hover,
ul.social-links a:hover {
	opacity: 1;
}

/* social widget */
.adore-widget.social-widget .social-widgets-wrap a {
	font-size: var(--font-size-sm);
	padding: 12px;
	opacity: 1;
	width: auto;
	height: auto;
	color: #fff;
	line-height: 1;
	border-radius: 0;
	overflow: visible;
	display: flex;
	align-items: center;
	justify-content: center;
	gap: 5px;
	opacity: 0.8;
}

.top-header-wrap .right-side ul.social-links a[href*='facebook.com'],
.adore-widget.social-widget .social-widgets-wrap a[href*='facebook.com'] {
	background-color: #3b5999;
}

.top-header-wrap .right-side ul.social-links a[href*='twitter.com'],
.adore-widget.social-widget .social-widgets-wrap a[href*='twitter.com'] {
	background-color: #55acee;
}

.top-header-wrap .right-side ul.social-links a[href*='instagram.com'],
.adore-widget.social-widget .social-widgets-wrap a[href*='instagram.com'] {
	background-color: #3F729B;
}

.top-header-wrap .right-side ul.social-links a[href*='youtube.com'],
.adore-widget.social-widget .social-widgets-wrap a[href*='youtube.com'] {
	background-color: #cd201f;
}

.top-header-wrap .right-side ul.social-links a[href*='discord.com'],
.adore-widget.social-widget .social-widgets-wrap a[href*='discord.com'] {
	background-color: #5865F2;
}

.top-header-wrap .right-side ul.social-links a[href*='dribbble.com'],
.adore-widget.social-widget .social-widgets-wrap a[href*='dribbble.com'] {
	background-color: #ea4c89;
}

.top-header-wrap .right-side ul.social-links a[href*='google.com'],
.adore-widget.social-widget .social-widgets-wrap a[href*='google.com'] {
	background-color: #dd4b39;
}

.top-header-wrap .right-side ul.social-links a[href*='line.me'],
.adore-widget.social-widget .social-widgets-wrap a[href*='line.me'] {
	background-color: #00b900;
}

.top-header-wrap .right-side ul.social-links a[href*='linkedin.com'],
.adore-widget.social-widget .social-widgets-wrap a[href*='linkedin.com'] {
	background-color: #0e76a8;
}

.top-header-wrap .right-side ul.social-links a[href*='medium.com'],
.adore-widget.social-widget .social-widgets-wrap a[href*='medium.com'] {
	background-color: #66cdaa;
}

.top-header-wrap .right-side ul.social-links a[href*='messenger.com'],
.adore-widget.social-widget .social-widgets-wrap a[href*='messenger.com'] {
	background-color: #006AFF;
}

.top-header-wrap .right-side ul.social-links a[href*='paypal.com'],
.adore-widget.social-widget .social-widgets-wrap a[href*='paypal.com'] {
	background-color: #3b7bbf;
}

.top-header-wrap .right-side ul.social-links a[href*='pinterest.com'],
.adore-widget.social-widget .social-widgets-wrap a[href*='pinterest.com'] {
	background-color: #E60023;
}

.top-header-wrap .right-side ul.social-links a[href*='reddit.com'],
.adore-widget.social-widget .social-widgets-wrap a[href*='reddit.com'] {
	background-color: #ff5700;
}

.top-header-wrap .right-side ul.social-links a[href*='skype.com'],
.adore-widget.social-widget .social-widgets-wrap a[href*='skype.com'] {
	background-color: #00aff0;
}

.top-header-wrap .right-side ul.social-links a[href*='slack.com'],
.adore-widget.social-widget .social-widgets-wrap a[href*='slack.com'] {
	background-color: #ECB22E;
}

.top-header-wrap .right-side ul.social-links a[href*='snapchat.com'],
.adore-widget.social-widget .social-widgets-wrap a[href*='snapchat.com'] {
	background-color: #FFFC00;
}

.top-header-wrap .right-side ul.social-links a[href*='spotify.com'],
.adore-widget.social-widget .social-widgets-wrap a[href*='spotify.com'] {
	background-color: #1DB954;
}

.top-header-wrap .right-side ul.social-links a[href*='stackoverflow.com'],
.adore-widget.social-widget .social-widgets-wrap a[href*='stackoverflow.com'] {
	background-color: #F47F24;
}

.top-header-wrap .right-side ul.social-links a[href*='telegram.org'],
.adore-widget.social-widget .social-widgets-wrap a[href*='telegram.org'] {
	background-color: #229ED9;
}

.top-header-wrap .right-side ul.social-links a[href*='twitch.tv'],
.adore-widget.social-widget .social-widgets-wrap a[href*='twitch.tv'] {
	background-color: #6441a5;
}

.top-header-wrap .right-side ul.social-links a[href*='vimeo.com'],
.adore-widget.social-widget .social-widgets-wrap a[href*='vimeo.com'] {
	background-color: #86c9ef;
}

.top-header-wrap .right-side ul.social-links a[href*='whatsapp.com'],
.adore-widget.social-widget .social-widgets-wrap a[href*='whatsapp.com'] {
	background-color: #34B7F1;
}

.top-header-wrap .right-side ul.social-links a[href*='wordpress.org'],
.adore-widget.social-widget .social-widgets-wrap a[href*='wordpress.org'] {
	background-color: #21759b;
}

.top-header-wrap .right-side ul.social-links a[href*='youtube.com'],
.adore-widget.social-widget .social-widgets-wrap a[href*='youtube.com'] {
	background-color: #c4302b;
}

.adore-widget.social-widget .social-widgets-wrap a:focus,
.adore-widget.social-widget .social-widgets-wrap a:hover {
	opacity: 1;
}

/* social widget */

/* Forms
--------------------------------------------- */
button,
input[type="button"],
input[type="reset"],
input[type="submit"] {
	-webkit-appearance: button;
	font-size: var(--font-size-sm);
	border: 1px solid;
	border-color: var(--primary-color);
	background: var(--primary-color);
	border-radius: 3px;
	color: #fff;
	line-height: 1;
	padding: 0.6em 1em;
}

button:hover,
input[type="button"]:hover,
input[type="reset"]:hover,
input[type="submit"]:hover {
	opacity: 0.8;
}

button:active,
button:focus,
input[type="button"]:active,
input[type="button"]:focus,
input[type="reset"]:active,
input[type="reset"]:focus,
input[type="submit"]:active,
input[type="submit"]:focus {
	opacity: 0.8;
}

input[type="text"],
input[type="email"],
input[type="url"],
input[type="password"],
input[type="search"],
input[type="number"],
input[type="tel"],
input[type="range"],
input[type="date"],
input[type="month"],
input[type="week"],
input[type="time"],
input[type="datetime"],
input[type="datetime-local"],
input[type="color"],
textarea {
	color: #666;
	border: 1px solid #ccc;
	border-radius: 3px;
	padding: 3px;
	width: 100%;
}

input[type="text"]:focus,
input[type="email"]:focus,
input[type="url"]:focus,
input[type="password"]:focus,
input[type="search"]:focus,
input[type="number"]:focus,
input[type="tel"]:focus,
input[type="range"]:focus,
input[type="date"]:focus,
input[type="month"]:focus,
input[type="week"]:focus,
input[type="time"]:focus,
input[type="datetime"]:focus,
input[type="datetime-local"]:focus,
input[type="color"]:focus,
textarea:focus {
	color: #111;
}

select {
	border: 1px solid #ccc;
}

textarea {
	width: 100%;
}

/*--------------------------------------------------------------
# Layouts
--------------------------------------------------------------*/

/*--------------------------------------------------------------
# Components
--------------------------------------------------------------*/

/* Posts and pages
--------------------------------------------- */
.sticky {
	display: block;
}

.post,
.page {
	margin: 0 0 1.5em;
}

.home.page {
	margin-bottom: 0;
}

.updated:not(.published) {
	display: none;
}

.page-content,
.entry-content,
.entry-summary {
	margin: 1.5em 0 0;
}

.page-links {
	clear: both;
	margin: 0 0 1.5em;
}

/* Comments
--------------------------------------------- */
.comment-content a {
	word-wrap: break-word;
}

.bypostauthor {
	display: block;
}

/* Widgets
--------------------------------------------- */
.widget {
	margin: 0 0 30px;
}

.widget select {
	max-width: 100%;
}

.widget_block h1,
.widget_block h2,
.widget_block h3,
.widget_block h4,
.widget_block h5,
.widget_block h6 {
	margin-top: 0;
	margin-bottom: 10px;
	line-height: 1.2;
}

/*widget list==*/
.widget ol,
.widget ul {
	list-style: none;
	padding: 0;
	margin-inline: 0;
}

.widget:not(.adore-widget) ol li,
.widget:not(.adore-widget) ul li {
	margin-bottom: 7px;
	padding-bottom: 7px;
	font-size: var(--font-size-sm);
	border-bottom: 1px solid rgba(var(--color-text-rgb), 0.15);
}

.widget ol li a,
.widget ul li a {
	text-decoration: none;
	color: var(--color-text);
	transition: all 0.5s linear;
}

.widget ol li a:focus,
.widget ul li a:focus,
.widget ol li a:hover,
.widget ul li a:hover {
	color: var(--primary-color);
}

.widget ol ol,
.widget ul ol,
.widget ol ul,
.widget ul ul {
	padding-top: 7px;
	margin-left: 10px;
	padding-left: 10px;
}

.widget>ol>li,
.widget>ul>li {
	margin-bottom: 7px;
	padding-bottom: 7px;
	font-size: 14px;
	border-bottom: 1px solid rgba(0, 0, 0, 0.1);
}

.widget>ol>li a,
.widget>ul>li a {
	color: var(--color-text);
	transition: all 0.5s linear;
}

.widget>ol>li a:focus,
.widget>ul>li a:focus,
.widget>ol>li a:hover,
.widget>ul>li a:hover {
	color: var(--primary-color);
}

.widget ol>li:last-child,
.widget ul>li:last-child {
	margin-bottom: 0;
	padding-bottom: 0;
	border-bottom: none;
}

/*widget list==*/
/*widget tag cloud ==*/
.wp-block-tag-cloud a,
.tagcloud a {
	display: inline-block;
	text-decoration: none;
	font-size: var(--font-size-sm) !important;
	color: var(--color-text);
	border: 1px solid var(--color-text);
	padding: 3px 7px;
	margin-inline-end: 5px;
	margin-block-end: 5px;
	line-height: 1.2;
}

.wp-block-tag-cloud a:focus,
.tagcloud a:focus,
.wp-block-tag-cloud a:hover,
.tagcloud a:hover {
	color: var(--primary-color);
	border: 1px solid var(--primary-color);
}

.site-footer .wp-block-tag-cloud a,
.site-footer .tagcloud a {
	border: 1px solid #fff;
}

.site-footer .wp-block-tag-cloud a:focus,
.site-footer .tagcloud a:focus,
.site-footer .wp-block-tag-cloud a:hover,
.site-footer .tagcloud a:hover {
	color: var(--primary-color);
	border: 1px solid var(--primary-color);
}

/*widget tag cloud ==*/
/*widget search ==*/
.widget.widget_search .wp-block-search__inside-wrapper {
	display: flex;
}

.widget.widget_search .wp-block-search__inside-wrapper .wp-block-search__input {
	border: 1px solid #d3ced2;
	padding: 6px 16px;
	font-size: 0.9rem;
}

.widget.widget_search .wp-block-search__inside-wrapper .wp-block-search__input:focus-visible {
	outline: 0;
}

.widget.widget_search .wp-block-search__inside-wrapper .wp-block-search__button {
	cursor: pointer;
	color: #fff;
	background-color: var(--primary-color);
	margin: 0;
	padding: 10px 25px;
}

.search-form {
	display: flex;
}

.search-form label,
.search-form .search-field {
	width: 100%;
}

.search-form .search-field {
	border: 1px solid #d3ced2;
	padding: 6px 16px;
	font-size: 0.9rem;
	border-radius: 0;
}

.search-form .search-submit {
	border-radius: 0;
}

/*widget search ==*/
/*widget wp social links ==*/
.wp-block-social-links li {
	margin: 0 !important;
	padding: 0 !important;
}

/*widget wp social links ==*/
/*widget calendar ==*/
.wp-block-calendar table th {
	background-color: var(--color-dark);
	color: #fff;
}

.wp-block-calendar tbody td,
.wp-block-calendar th {
	border: 1px solid rgba(var(--color-text-rgb), 0.15);
}

.wp-block-calendar table caption,
.wp-block-calendar table tbody {
	color: var(--color-text);
}

.wp-block-calendar a {
	color: var(--primary-color);
}

/*widget calendar ==*/




/* Media
--------------------------------------------- */
.page-content .wp-smiley,
.entry-content .wp-smiley,
.comment-content .wp-smiley {
	border: none;
	margin-bottom: 0;
	margin-top: 0;
	padding: 0;
}

/* Make sure logo link wraps around logo image. */
.custom-logo-link {
	display: inline-block;
}

/* Captions
--------------------------------------------- */
.wp-caption {
	margin-bottom: 1.5em;
	max-width: 100%;
}

.wp-caption img[class*="wp-image-"] {
	display: block;
	margin-left: auto;
	margin-right: auto;
}

.wp-caption .wp-caption-text {
	margin: 0.8075em 0;
}

.wp-caption-text {
	text-align: center;
}

/* Galleries
--------------------------------------------- */
.gallery {
	margin-bottom: 1.5em;
	display: grid;
	grid-gap: 1.5em;
}

.gallery-item {
	display: inline-block;
	text-align: center;
	width: 100%;
}

.gallery-columns-2 {
	grid-template-columns: repeat(2, 1fr);
}

.gallery-columns-3 {
	grid-template-columns: repeat(3, 1fr);
}

.gallery-columns-4 {
	grid-template-columns: repeat(4, 1fr);
}

.gallery-columns-5 {
	grid-template-columns: repeat(5, 1fr);
}

.gallery-columns-6 {
	grid-template-columns: repeat(6, 1fr);
}

.gallery-columns-7 {
	grid-template-columns: repeat(7, 1fr);
}

.gallery-columns-8 {
	grid-template-columns: repeat(8, 1fr);
}

.gallery-columns-9 {
	grid-template-columns: repeat(9, 1fr);
}

.gallery-caption {
	display: block;
}

/*--------------------------------------------------------------
# Plugins
--------------------------------------------------------------*/

/* Jetpack infinite scroll
--------------------------------------------- */

/* Hide the Posts Navigation and the Footer when Infinite Scroll is in use. */
.infinite-scroll .posts-navigation,
.infinite-scroll.neverending .site-footer {
	display: none;
}

/* Re-display the Theme Footer when Infinite Scroll has reached its end. */
.infinity-end.neverending .site-footer {
	display: block;
}

/*--------------------------------------------------------------
# Utilities
--------------------------------------------------------------*/

/* Accessibility
--------------------------------------------- */

/* Text meant only for screen readers. */
.screen-reader-text {
	border: 0;
	clip: rect(1px, 1px, 1px, 1px);
	clip-path: inset(50%);
	height: 1px;
	margin: -1px;
	overflow: hidden;
	padding: 0;
	position: absolute !important;
	width: 1px;
	word-wrap: normal !important;
}

.screen-reader-text:focus {
	background-color: #f1f1f1;
	border-radius: 3px;
	box-shadow: 0 0 2px 2px rgba(0, 0, 0, 0.6);
	clip: auto !important;
	clip-path: none;
	color: #21759b;
	display: block;
	font-size: 0.875rem;
	font-weight: 700;
	height: auto;
	left: 5px;
	line-height: normal;
	padding: 15px 23px 14px;
	text-decoration: none;
	top: 5px;
	width: auto;
	z-index: 100000;
}

/* Do not show the outline on the skip link target. */
#primary[tabindex="-1"]:focus {
	outline: 0;
}

/* Alignments
--------------------------------------------- */
.alignleft {

	/*rtl:ignore*/
	float: left;

	/*rtl:ignore*/
	margin-right: 1.5em;
	margin-bottom: 1.5em;
}

.alignright {

	/*rtl:ignore*/
	float: right;

	/*rtl:ignore*/
	margin-left: 1.5em;
	margin-bottom: 1.5em;
}

.aligncenter {
	clear: both;
	display: block;
	margin-left: auto;
	margin-right: auto;
	margin-bottom: 1.5em;
}

/* Preloader
--------------------------------------------- */

#loader {
	overflow-x: hidden;
	overflow-y: hidden;
	vertical-align: middle;
	background-color: #fff;
	position: fixed;
	display: flex;
	align-items: center;
	justify-content: center;
	width: 100%;
	top: 0;
	left: 0;
	height: 100%;
	min-height: 100%;
	z-index: 99999;
}

.dark-mode #loader {
	background-color: var(--color-dark);
}

#loader .loader-container {
	position: relative;
	z-index: 12;
}

#loader #preloader {
	position: relative;
	margin: auto;
	width: 100px;
}

.dark-mode #preloader img {
	filter: invert(1);
}

/* Preloader
--------------------------------------------- */
/* Theme Wrapper
--------------------------------------------- */
body:not(.home):not(.home.blog) .site-content {
	margin-top: 50px;
}

.theme-wrapper {
	max-width: 1300px;
	margin-inline: auto;
	padding-left: 15px;
	padding-right: 15px;
}

.main-widget-section-wrap,
.theme-wrap {
	display: flex;
	flex-wrap: wrap;
	align-items: flex-start;
	gap: 30px;
}

.main-widget-section-wrap .secondary-widgets-area,
.main-widget-section-wrap .primary-widgets-area,
.theme-wrap #secondary,
.theme-wrap #primary {
	width: 100%;
}

.main-widget-section-wrap.secondary-left-position,
.left-sidebar .theme-wrap {
	flex-direction: row-reverse;
}

.main-widget-section-wrap.full-width,
.no-sidebar .theme-wrap {
	display: block;
}

@media (min-width: 992px) {

	.main-widget-section-wrap.secondary-right-position:not(.full-width) .primary-widgets-area,
	.main-widget-section-wrap.secondary-left-position:not(.full-width) .primary-widgets-area,
	.theme-wrap #primary {
		width: calc(70% - 15px);
		flex-grow: 1;
	}

	.main-widget-section-wrap.secondary-right-position:not(.full-width) .secondary-widgets-area,
	.main-widget-section-wrap.secondary-left-position:not(.full-width) .secondary-widgets-area,
	.theme-wrap #secondary {
		width: calc(30% - 15px);
		position: sticky;
		top: 40px;
		flex-shrink: 0;
	}

	.no-sidebar .theme-wrap #secondary,
	.no-sidebar .theme-wrap #primary {
		width: 100%;
	}
}

/* End Theme Wrapper
--------------------------------------------- */

.site-content {
	margin-top: 30px;
}

/* sections Start
--------------------------------------------- */
.main-widget-section,
.frontpage {
	margin-top: 30px;
}

.news-ticker-section:not(:first-child),
.main-banner-section:not(:first-child) {
	margin-top: 30px;
}

.news-ticker-section:first-child,
.main-banner-section:first-child {
	margin-top: 0;
}

.news-ticker-section+.main-banner-section {
	margin-top: 10px;
}

/* sections End
--------------------------------------------- */

/* header navigation start
--------------------------------------------- */
.site-header {
	margin-bottom: 10px;
}

.top-header {
	background-color: var(--color-dark);
	padding-block: 10px;
	position: relative;
	color: #fff;
}

.top-header .top-header-wrap {
	display: flex;
	align-items: center;
	justify-content: space-between;
}

.top-header-wrap .left-side .top-info {
	font-size: var(--font-size-sm);
	font-weight: bold;
	letter-spacing: 0.5px;
}

.top-header-wrap .right-side {
	margin-block: -10px;
}

.top-header-wrap .right-side ul.social-links {
	gap: 0;
}

.top-header-wrap .right-side ul.social-links a {
	color: #fff;
	padding: 20px;
}

.middle-header.adore-header-image {
	padding-block: 10px;
	position: relative;
}

.middle-header.adore-header-image>* {
	position: relative;
	z-index: 1;
}

.middle-header.adore-header-image::before {
	position: absolute;
	content: "";
	top: 0;
	left: 0;
	width: 100%;
	height: 100%;
	background-color: #000;
	opacity: 0.7;
}

.middle-header-wrap {
	display: flex;
	justify-content: space-between;
	align-items: center;
	padding-block: 15px;
	gap: 30px;
}

.middle-header-wrap.no-advertisement_image {
	justify-content: center;
	padding-block: 30px;
}

.middle-header-wrap.no-advertisement_image .site-branding {
	margin-right: 0;
	text-align: center;
}


.adore-adver {
	width: 100%;
}

@media (min-width: 992px) {
	.adore-adver {
		width: 60%;
	}
}

@media (max-width: 991px) {
	.middle-header-wrap {
		flex-direction: column;
		gap: 15px;
	}
}

.adore-adver a {
	display: block;
	line-height: 0;
}

.adore-adver a img {
	width: 100%;
}

.adore-adver a:focus {
	outline-color: var(--theme-color);
	outline-offset: 2px;
}

.adore-header {
	background-color: var(--color-background);
	border-bottom: 1px solid rgba(var(--color-text-rgb), 0.15);
	box-shadow: 0 0 4px 0 rgba(10, 10, 10, 0.06);
}

@media (min-width: 1024px) {
	body.admin-bar .adore-header.fix-header {
		top: 32px;
	}
}

@media (min-width: 601px) and (max-width: 768px) {
	body.admin-bar .adore-header.fix-header {
		top: 46px;
	}
}

@media (max-width: 600px) {
	.adore-header.fix-header .site-branding {
		display: none;
	}
}

.adore-header.fix-header {
	position: fixed;
	width: 100%;
	top: 0;
	z-index: 15;
}

.header-wrapper {
	padding-block: 10px;
}

.header-nav-search {
	display: flex;
	align-items: center;
	justify-content: space-between;
}

.site-branding {
	margin-right: auto;
}

.site-branding .site-identity .site-title {
	font-size: 30px;
	line-height: 1.1;
	font-weight: 700;
	margin: 0;
}

.site-branding .site-identity .site-title a {
	text-decoration: none;
}

.site-branding .site-identity .site-description {
	margin-bottom: 0;
	margin-top: 5px;
}

/* navigation search  */
.navigation-search {
	width: 30px;
	position: relative;
	display: inline-block;
	text-align: center;
}

.navigation-search .navigation-search-wrap .navigation-search-icon {
	color: var(--color-text);
	font-size: 14px;
	font-weight: 700;
	text-align: center;
	outline: 0;
	height: 30px;
	width: 30px;
	display: flex;
	align-items: center;
	justify-content: center;
	text-decoration: none;
}

.navigation-search .navigation-search-wrap .navigation-search-icon:focus,
.navigation-search .navigation-search-wrap .navigation-search-icon:hover {
	color: var(--primary-color);
}

.navigation-search .navigation-search-wrap .navigation-search-icon:focus-within {
	outline: 1px dashed;
}

.navigation-search .navigation-search-wrap .navigation-search-form {
	position: absolute;
	background: #fff;
	right: 0;
	opacity: 0;
	visibility: hidden;
	top: 100%;
	width: 325px;
	padding: 14px;
	z-index: 99;
	box-shadow: 0 2px 9px -7px #000;
}

.dark-mode .navigation-search .navigation-search-wrap .navigation-search-form {
	background-color: var(--color-dark);
}

.navigation-search .navigation-search-wrap .navigation-search-form .search-form {
	display: flex;
}

.navigation-search .navigation-search-wrap .navigation-search-form .search-form label {
	width: 75%;
}

.navigation-search .navigation-search-wrap .navigation-search-form .search-form label input {
	width: 100%;
	border-radius: 0px;
}

.navigation-search .navigation-search-wrap .navigation-search-form .search-form input.search-submit {
	border-radius: 0px;
	width: 25%;
	margin: 0;
	font-size: var(--font-size-sm);
	border: none;
	background: var(--primary-color);
	color: #fff;
	line-height: 1;
	padding: 0.6em 1em;
}

.navigation-search .navigation-search-wrap.show .navigation-search-form {
	margin: 0;
	opacity: 1;
	visibility: visible;
}

@media (max-width: 480px) {
	.navigation-search {
		position: unset;
	}

	.navigation-search .navigation-search-wrap .navigation-search-form {
		width: 100%;
	}
}

/* navigation search  */
/* desktop navigation */
.main-navigation ul {
	list-style: none;
	padding: 0;
	margin: 0;
}

.main-navigation ul a {
	text-decoration: none;
}

.main-navigation ul .current_page_item>a,
.main-navigation ul .current-menu-item>a,
.main-navigation ul .current_page_ancestor>a,
.main-navigation ul .current-menu-ancestor>a {
	color: var(--primary-color);
}


@media(min-width:992px) {
	.menu-toggle {
		display: none;
	}

	.header-nav-search {
		display: flex;
		align-items: center;
	}

	.main-navigation ul {
		display: flex;
		flex-wrap: wrap;
	}

	.main-navigation ul li.menu-item-has-children>a::after {
		font-style: normal;
		font-variant: normal;
		font-weight: 400;
		line-height: 1;
		font-family: Font Awesome\ 5 Free;
		font-weight: 900;
		line-height: inherit;
		vertical-align: baseline;
		content: "\f107";
		display: inline-block;
		margin-inline-start: 10px;
	}

	.main-navigation ul ul li.menu-item-has-children>a::after {
		content: "\f105";
	}

	.main-navigation ul a {
		padding: 15px;
		text-transform: uppercase;
		color: var(--color-text);
		display: inline-block;
	}

	.main-navigation ul li a:focus,
	.main-navigation ul li a:hover {
		color: var(--primary-color);
	}

	.main-navigation ul ul {
		width: 200px;
		display: block;
		position: absolute;
		text-align: left;
		visibility: hidden;
		filter: alpha(opacity=0);
		opacity: 0;
		margin: 0 auto;
		padding: 0;
		box-shadow: 0 5px 5px rgb(0 0 0 / 30%);
		transition: top 0.4s;
		top: 110%;
		left: 0px;
		background-color: #fff;
	}

	.dark-mode .main-navigation ul ul {
		background-color: var(--color-dark);
	}

	.main-navigation ul ul a {
		display: block;
		padding: 10px 15px;
		display: flex;
		justify-content: space-between;
	}

	.main-navigation ul ul li {
		border-bottom: 1px solid rgba(var(--color-text-rgb), 0.15);
	}

	.main-navigation ul ul li a {
		text-transform: capitalize;
	}

	.main-navigation .menu li {
		position: relative;
	}

	.main-navigation ul li:focus-within>ul,
	.main-navigation ul li:hover>ul {
		visibility: visible;
		filter: alpha(opacity=1);
		opacity: 1;
		z-index: 999;
	}

	.main-navigation ul ul li:focus-within>ul,
	.main-navigation ul ul li:hover>ul {
		top: 100%;
	}

	.main-navigation ul ul li ul {
		top: 0;
	}

	.main-navigation ul ul li:focus-within ul,
	.main-navigation ul ul li:hover ul {
		top: 0;
		left: 100%;
	}

	.main-navigation ul .current_page_item>a,
	.main-navigation ul .current-menu-item>a,
	.main-navigation ul .current_page_ancestor>a,
	.main-navigation ul .current-menu-ancestor>a {
		position: relative;
	}

	.main-navigation ul .current_page_item>a::before,
	.main-navigation ul .current-menu-item>a::before,
	.main-navigation ul .current_page_ancestor>a::before,
	.main-navigation ul .current-menu-ancestor>a::before {
		position: absolute;
		content: "";
		left: 0;
		bottom: -2px;
		width: 100%;
		height: 2px;
		background-color: var(--primary-color);
	}
}

@media(max-width:991px) {

	.menu-toggle {
		width: 35px;
		height: 35px;
		position: relative;
		transform: rotate(0deg);
		transition: 0.5s ease-in-out;
		cursor: pointer;
		padding: 0;
		background: none;
		border: none;
		margin: 5px;
	}

	.menu-toggle span {
		display: block;
		position: absolute;
		height: 3px;
		width: 100%;
		background-color: var(--color-text);
		border-radius: 3px;
		opacity: 1;
		left: 0;
		transform: rotate(0deg);
		transition: 0.25s ease-in-out;
	}

	.menu-toggle span:nth-child(1) {
		top: calc(50% - 15px);
	}

	.menu-toggle span:nth-child(2) {
		top: 50%;
		transform: translateY(-50%);
	}

	.menu-toggle span:nth-child(3) {
		bottom: calc(50% - 15px);
	}

	.main-navigation.toggled .menu-toggle span:nth-child(1) {
		top: 14px;
		width: 0%;
		left: 50%;
	}

	.main-navigation.toggled .menu-toggle span:nth-child(2) {
		transform: rotate(45deg);
	}

	.main-navigation.toggled .menu-toggle span:nth-child(3) {
		top: 50%;
		transform: translateY(-50%) rotate(-45deg);
	}

	.header-wrapper {
		flex-direction: column;
	}

	.header-nav-search,
	.site-branding {
		width: 100%;
	}

	.site-branding {
		text-align: center;
	}

	.header-nav-search {
		display: flex;
		align-items: center;
		justify-content: space-between;
		position: relative;
	}

	.main-navigation ul.nav-menu {
		margin: 0;
		padding: 0;
		list-style: none;
		text-align: left;
		position: absolute;
		top: 100%;
		width: 100%;
		z-index: 9999;
		display: none;
		background: #fff;
		box-shadow: var(--shadow);
	}

	.dark-mode .main-navigation ul.nav-menu {
		background-color: var(--color-dark);
	}

	.main-navigation ul li.menu-item-has-children>a::after {
		font-style: normal;
		font-variant: normal;
		font-weight: 400;
		line-height: 1;
		font-family: Font Awesome\ 5 Free;
		font-weight: 900;
		line-height: inherit;
		vertical-align: baseline;
		content: "\f107";
		display: inline-block;
		margin-inline-start: 10px;
	}


	.main-navigation ul a {
		padding: 15px;
		text-transform: uppercase;
		color: var(--color-text);
		display: block;
	}

	.main-navigation ul li:not(:last-child) {
		border-bottom: 1px solid rgba(var(--color-text-rgb), 0.15);
	}

	.main-navigation ul li:first-child {
		border-top: 1px solid rgba(var(--color-text-rgb), 0.15);
	}

	.main-navigation ul ul {
		height: 0;
		transform: scaleY(0);
		transform-origin: top left;
		overflow: hidden;
		transition: all 0.5s ease-in-out;
		margin-inline-start: 10px;
	}

	.main-navigation ul li.menu-item-has-children:hover>ul,
	.main-navigation ul li.menu-item-has-children.focus>ul {
		height: auto;
		transform: scaleY(1);
	}

	.main-navigation ul ul a {
		display: block;
		padding: 10px 15px;
	}

	.main-navigation ul ul li {
		border-bottom: 1px solid #f1f1f1;
	}

	.main-navigation ul ul li a {
		text-transform: capitalize;
	}

	.main-navigation ul ul li a:focus {
		outline-offset: -2px;
	}

	.main-navigation .menu li {
		position: relative;
	}

}

/* desktop navigation */
/* header navigation end
--------------------------------------------- */

/* Post Item Common
--------------------------------------------- */


.post-item {
	background-color: var(--color-light);
}

.site-footer .post-item {
	background-color: #2a2a2a;
}

.post-item .post-item-image {
	position: relative;
	overflow: hidden;
}

.post-item .post-item-image a {
	display: block;
	height: 100%;
	width: 100%;
	line-height: 0;
}

.post-item .post-item-image a:focus {
	outline-offset: -3px;
}

.post-item .post-item-image a img {
	width: 100%;
	height: 100%;
	aspect-ratio: 1;
	object-fit: cover;
	position: relative;
	z-index: 1;
	-webkit-transition: all 0.5s ease-in-out;
	transition: all 0.5s ease-in-out;
}

.post-item .post-item-image img {
	-webkit-transition: all 0.5s ease-in-out;
	transition: all 0.5s ease-in-out;
}

.post-item:focus-within .post-item-image img,
.post-item:hover .post-item-image img {
	-webkit-transform: scale(1.2);
	transform: scale(1.2);
}

.post-item .post-item-content {
	padding: 15px 0 0;
}

.post-item.post-grid .post-item-content {
	padding: 15px;
}

.post-item .post-item-content .entry-cat .post-categories {
	list-style: none;
	padding: 0;
	margin: 0;
	display: flex;
	flex-wrap: wrap;
}

.post-item .post-item-content .entry-cat .post-categories li {
	margin-inline-end: 5px;
	margin-block-start: 5px;
	display: flex;
}

.post-item .post-item-content .entry-cat .post-categories li a {
	color: #fff;
	display: block;
	background-color: var(--primary-color);
	font-size: var(--font-size-xs);
	text-decoration: none;
	line-height: 1;
	padding: 3px 7px;
	border-radius: 3px;
	transition: all 0.5s;
}

.post-item .post-item-content .entry-cat .post-categories li a:focus,
.post-item .post-item-content .entry-cat .post-categories li a:hover {
	opacity: 0.8;
}

.post-item .post-item-content .entry-cat.no-bg .post-categories li a {
	color: var(--primary-color);
	background-color: transparent;
	text-transform: uppercase;
	font-weight: bold;
	padding: 0;
}

.post-item .post-item-content .entry-cat.no-bg .post-categories li:not(:last-child) a:after {
	content: "\22C5";
	font-weight: bold;
	padding: 0 0 0 5px;
	opacity: 0.7;
	color: var(--color-text);
}

.post-item .post-item-content .entry-cat.no-bg .post-categories li a:focus,
.post-item .post-item-content .entry-cat.no-bg .post-categories li a:hover {
	opacity: 1;
	color: var(--color-text);
}

.post-item .post-item-content .entry-cat .post-categories li a:focus {
	outline-offset: 2px;
	outline-color: var(--color-text);
}

.post-item .post-item-content .entry-title {
	margin-block: 10px;
	line-height: 1.3;
	font-size: var(--font-size-base);
	font-family: var(--font-head);
}

.post-item .post-item-content .entry-title a {
	color: var(--color-text);
	display: inline;
	text-decoration-line: underline;
	text-decoration-color: transparent;
	transition: all 0.5s;
}

.post-item:focus-within .post-item-content .entry-title a,
.post-item:hover .post-item-content .entry-title a {
	color: var(--color-text);
	text-decoration-color: currentColor;
}

.post-item .post-item-content .entry-title a:focus,
.post-item .post-item-content .entry-title a:hover {
	color: var(--primary-color);
}


.post-item .post-item-content .entry-meta {
	margin: 0;
	margin-block-end: 10px;
	padding: 0;
	list-style: none;
	display: flex;
	flex-wrap: wrap;
	align-items: center;
	row-gap: 6px;
	column-gap: 12px;
}

.post-item .post-item-content .entry-meta:last-child {
	margin-block-end: 0;
}

.post-item .post-item-content .entry-meta li {
	margin-bottom: 0;
	font-size: var(--font-size-xs);
	text-transform: capitalize;
	font-weight: 500;
}

.post-item .post-item-content .entry-meta li a {
	text-decoration: none;
	color: var(--color-text);
}

.post-item .post-item-content .entry-meta li a:focus,
.post-item .post-item-content .entry-meta li a:hover {
	color: var(--primary-color);
}

.post-item .post-item-content .entry-meta li:last-child {
	display: flex;
	align-items: center;
}

.post-item .post-item-content .entry-meta li span {
	margin-inline-end: 5px;
}

.post-item .post-item-content .post-exerpt p {
	margin-block: 10px;
	margin-block-start: 0;
}

.post-item .post-item-content .post-btn a:focus,
.post-item .post-item-content .post-btn a:hover {
	color: var(--primary-color);
}

.btn-read-more {
	cursor: pointer;
	text-decoration: none;
	display: inline-flex;
	align-items: center;
	text-align: center;
	white-space: nowrap;
	vertical-align: middle;
	position: relative;
	color: var(--color-text);
	font-size: var(--font-size-sm);
	font-weight: 600;
	text-transform: capitalize;
	transition: all 0.3s ease-in-out;
}

.btn-read-more:visited {
	color: var(--color-text);
}

.btn-read-more:focus,
.btn-read-more:hover {
	color: var(--primary-color);
}

.btn-read-more i {
	position: relative;
	height: 15px;
	width: 20px;
	margin-left: 7px;
	margin-right: 5px;
	transition: all 0.5s ease-in-out;
}

.btn-read-more i::before {
	content: "";
	position: absolute;
	top: 50%;
	left: 0;
	transform: translateY(-50%);
	width: 100%;
	height: 1px;
	background: var(--color-text);
}

.site-footer .btn-read-more i::before {
	background-color: #fff;
}

.btn-read-more i::after {
	content: "";
	position: absolute;
	width: 7px;
	height: 7px;
	border: 1px solid var(--color-text);
	right: 0;
	top: 50%;
	transform: translateY(-50%) rotate(45deg);
	border-bottom: 0;
	border-left: 0;
}

.site-footer .btn-read-more i::after {
	border: 1px solid #fff;
	border-bottom: 0;
	border-left: 0;
}

.btn-read-more:hover i,
.btn-read-more:focus i {
	transform: translateX(5px);
}

.btn-read-more:hover i::before,
.btn-read-more:focus i::before {
	background: var(--primary-color);
}

.site-footer .btn-read-more:hover i::before,
.site-footer .btn-read-more:focus i::before {
	background-color: #fff;
}

.btn-read-more:hover i::after,
.btn-read-more:focus i::after {
	border: 1px solid var(--primary-color);
	border-bottom: 0;
	border-left: 0;
}

.site-footer .btn-read-more:hover i::after,
.site-footer .btn-read-more:focus i::after {
	border: 1px solid #fff;
	border-bottom: 0;
	border-left: 0;
}

/* Post Item Common
--------------------------------------------- */
/* Adore Slick Navigation css start
--------------------------------------------- */

.adore-navigation .adore-arrow {
	position: absolute;
	top: 5px;
	font-size: var(--font-size-sm);
	width: 40px;
	height: 40px;
	background: transparent;
	color: #fff;
	border: 1px solid #fff;
	text-align: center;
	line-height: 30px;
	z-index: 1;
	cursor: pointer;
	font-weight: 600;
	transition: 0.4s;
	padding: 0;
	border-radius: 0;
	display: flex;
	align-items: center;
	justify-content: center;
	background-color: rgba(255, 255, 255, 0.5);
	backdrop-filter: blur(15px);
	/* color: var(--color-text); */
}

.adore-navigation .adore-arrow:focus,
.adore-navigation .adore-arrow:hover {
	opacity: 1;
	backdrop-filter: blur(0);
	background: var(--primary-color);
	color: #fff;
}

.adore-navigation .adore-arrow.slide-prev {
	right: 50px;
}

.adore-navigation .adore-arrow.slide-next {
	right: 5px;
}

/* Adore Slick Navigation css end
--------------------------------------------- */

/* news ticker Section start
--------------------------------------------- */

.news-ticker-section .news-ticker-section-wrapper {
	background-color: #f1f1f1;
	position: relative;
	height: 45px;
	display: flex;
	overflow: hidden;
}

.dark-mode .news-ticker-section .news-ticker-section-wrapper {
	background-color: var(--color-dark);
}

@media (min-width: 768px) {
	.acme-news-ticker {}
}

.news-ticker-section-wrapper .acme-news-ticker-label {
	background: var(--primary-color);
	padding: 10px;
	width: auto;
	float: left;
	line-height: normal;
	height: 100%;
	color: #fff;
	position: relative;
	flex-shrink: 0;
	z-index: 9;
}

.news-ticker-section-wrapper .acme-news-ticker-label::after {
	content: "";
	width: 10px;
	height: 100%;
	position: absolute;
	z-index: 1;
	top: 0;
	right: -10px;
	-webkit-mask-image: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 553.5 553.5" preserveAspectRatio="none"><polygon points="0,553 553.5,553.5 0,0 "/></svg>');
	mask-image: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 553.5 553.5" preserveAspectRatio="none"><polygon points="0,553 553.5,553.5 0,0 "/></svg>');
	-webkit-mask-position: center center;
	mask-position: center center;
	-webkit-mask-repeat: no-repeat;
	mask-repeat: no-repeat;
	mask-size: 100% 100%;
	-webkit-mask-size: 100% 100%;
	background-color: var(--primary-color);
}

.news-ticker-section-wrapper .tickercontainer {
	font-size: 0;
	min-height: 45px;
	display: flex;
	align-items: center;
}

.news-ticker-section-wrapper ul.newsticker {
	width: 100%;
	list-style-type: none !important;
	padding: 0;
	margin: 0;
}

.news-ticker-section-wrapper ul.newsticker li {
	margin: 0;
	margin-inline-end: 20px;
}

.news-ticker-section-wrapper ul.newsticker li .newsticker-outer {
	display: flex;
	align-items: center;
	gap: 5px;
}

.news-ticker-section-wrapper ul.newsticker li .newsticker-outer .newsticker-image {
	width: 30px;
	min-width: 30px;
	height: 30px;
	min-height: 30px;
	border-radius: 50%;
	overflow: hidden;
	display: inline-block;
	line-height: 1;
	position: relative;
}

.dispay-number .news-ticker-section-wrapper ul.newsticker li .newsticker-outer .newsticker-image .ticker-no {
	position: absolute;
	top: 50%;
	left: 50%;
	z-index: 3;
	width: 100%;
	height: 100%;
	font-weight: 700;
	display: flex;
	color: #fff;
	align-items: center;
	justify-content: center;
	font-size: var(--font-size-sm);
	transform: translate(-50%, -50%);
	background-color: rgba(0, 0, 0, 0.25);
}

.news-ticker-section-wrapper ul.newsticker li .newsticker-outer .newsticker-image img {
	height: 30px;
	width: 30px;
	object-fit: cover;
	margin: 0;
}

.news-ticker-section-wrapper ul.newsticker li .newsticker-outer .newsticker-title a {
	text-decoration: none;
	font-size: var(--font-size-sm);
	line-height: 1.2;
	color: var(--color-text);
	font-weight: 600;
	display: block;
}

.news-ticker-section-wrapper ul.newsticker li .newsticker-outer .newsticker-title a:focus,
.news-ticker-section-wrapper ul.newsticker li .newsticker-outer .newsticker-title a:hover {
	color: var(--primary-color);
}

@media (max-width: 575px) {
	.news-ticker-section-wrapper ul.newsticker li a {
		font-size: calc(var(--font-size-xs) - 0.15px);
	}
}

/* news ticker Section end
--------------------------------------------- */
/* Banner Slider Section
--------------------------------------------- */

.main-banner-section .post-item.overlay-post.slider-item {
	height: auto;
	min-height: 220px;
	position: relative;
	background-size: cover;
	background-position: center center;
}

.main-banner-section .slider-item .blog-banner {
	position: absolute;
	bottom: 0px;
	padding: 20px;
	z-index: 2;
	left: 0;
}

.main-banner-section .post-item.slider-item .post-item-content .entry-meta {
	margin: 0;
}

/* banner style 1 */
.main-banner-section.style-1 .banner-slider {
	display: grid;
	grid-gap: 10px;
	grid-template-columns: repeat(4, 1fr);
}

.main-banner-section.style-1 .banner-slider .post-item:first-child {
	grid-column: span 2;
	grid-row: span 2;
}

.main-banner-section.style-1 .post-item.overlay-post.slider-item:first-child .entry-title {
	font-size: var(--font-size-md);
}

@media (max-width: 1023px) {
	.main-banner-section.style-1 .banner-slider {
		grid-template-columns: repeat(2, 1fr);
	}
}

@media (max-width: 767px) {
	.main-banner-section.style-1 .banner-slider {
		display: flex;
		flex-direction: column;
		gap: 10px;
	}

	.main-banner-section.style-1 .banner-slider .post-item-outer:first-child {
		grid-column: span 1;
		grid-row: span 1;
	}
}

/* banner style 1 */

/* banner style 2 */
.main-banner-section.style-2 .banner-slider {
	display: grid;
	grid-gap: 10px;
	grid-template-columns: repeat(4, 1fr);
}

.main-banner-section.style-2 .banner-slider .post-item:first-child {
	grid-column: span 2;
	grid-row: span 2;
}

.main-banner-section.style-2 .post-item.overlay-post.slider-item:first-child .entry-title {
	font-size: var(--font-size-md);
}

@media (min-width: 1024px) {
	.main-banner-section.style-2 .banner-slider .post-item:first-child {
		grid-column: 2/4;
	}

	.main-banner-section.style-2 .banner-slider .post-item:nth-child(2) {
		grid-column-start: 1;
		grid-row-start: 1;
	}
}

@media (max-width: 1023px) {
	.main-banner-section.style-2 .banner-slider {
		grid-template-columns: repeat(2, 1fr);
	}

	.main-banner-section.style-2 .banner-slider .post-item:first-child {
		min-height: 450px;
	}
}

@media (max-width: 767px) {
	.main-banner-section.style-2 .banner-slider {
		display: flex;
		flex-direction: column;
		gap: 10px;
	}

	.main-banner-section.style-2 .banner-slider .post-item-outer:first-child {
		grid-column: span 1;
		grid-row: span 1;
		min-height: 380px;
	}
}

/* banner style 2 */
/* banner style 3 */
.main-banner-section.style-3 .banner-slider {
	display: grid;
	grid-gap: 10px;
	grid-template-columns: repeat(4, 1fr);
}

.main-banner-section.style-3 .banner-slider .post-item:first-child {
	grid-column: span 2;
	grid-row: span 2;
}

.main-banner-section.style-3 .banner-slider .post-item:nth-child(2) {
	grid-column: span 2;
}

.main-banner-section.style-3 .banner-slider .post-item:nth-child(2) .entry-title,
.main-banner-section.style-3 .post-item.overlay-post.slider-item:first-child .entry-title {
	font-size: var(--font-size-md);
}

@media (max-width: 1023px) {
	.main-banner-section.style-3 .banner-slider {
		grid-template-columns: repeat(2, 1fr);
	}

	.main-banner-section.style-3 .banner-slider .post-item:first-child,
	.main-banner-section.style-3 .banner-slider .post-item:nth-child(2) {
		grid-column: span 1;
	}
}

@media (max-width: 767px) {
	.main-banner-section.style-3 .banner-slider {
		display: flex;
		flex-direction: column;
		gap: 10px;
	}
}

/* banner style 3 */
/* banner style 4 */
.main-banner-section.style-4 .banner-slider {
	display: grid;
	grid-gap: 10px;
	grid-template-columns: repeat(4, 1fr);
}

.main-banner-section.style-4 .banner-slider .post-item:first-child {
	grid-column: span 2;
	grid-row: span 2;
}

.main-banner-section.style-4 .banner-slider .post-item:nth-child(2) {
	grid-row: span 2;
}

.main-banner-section.style-4 .banner-slider .post-item:nth-child(2) .entry-title,
.main-banner-section.style-4 .post-item.overlay-post.slider-item:first-child .entry-title {
	font-size: var(--font-size-md);
}

@media (max-width: 1023px) {
	.main-banner-section.style-4 .banner-slider {
		grid-template-columns: repeat(2, 1fr);
	}

	.main-banner-section.style-4 .banner-slider .post-item:first-child,
	.main-banner-section.style-4 .banner-slider .post-item:nth-child(2) {
		grid-column: span 1;
	}
}

@media (max-width: 767px) {
	.main-banner-section.style-4 .banner-slider {
		display: flex;
		flex-direction: column;
		gap: 10px;
	}
}

/* banner style 4 */

/* End Banner Slider Section
--------------------------------------------- */


/* Start Grid Posts Section
--------------------------------------------- */
.post-grid-wrapper {
	display: grid;
	gap: 20px;
	grid-template-columns: repeat(3, 1fr);
}

@media (max-width: 768px) {
	.post-grid-wrapper {
		grid-template-columns: repeat(2, 1fr);
	}
}

@media (max-width: 480px) {
	.post-grid-wrapper {
		grid-template-columns: repeat(1, 1fr);
	}
}

.post-item.post-grid .post-item-image .post-thumbnail img,
.post-item.post-grid .post-item-image a img {
	aspect-ratio: 1/0.7;
}

/* End Grid Posts Section
--------------------------------------------- */

/* Start List Posts Section
--------------------------------------------- */

.post-item.post-list {
	padding: 0px 0px;
	border-bottom: 0;
	display: flex;
	align-items: center;
	transition: all 0.4s ease-in-out;
}

.post-item.post-list:nth-child(even) {
	flex-direction: row-reverse;
}

.post-item.post-list .post-item-image {
	flex: 0 0 50%;
	max-width: 50%;
}

.post-item.post-list .post-item-content {
	flex-grow: 1;
	padding: 20px;
}

/* popular post style2  */
.popularpost.style-2 .pupular-post-wrapper {
	display: grid;
	gap: 30px;
}

@media (min-width: 600px) {
	.popularpost.style-2 .pupular-post-wrapper {
		gap: 50px;
	}

	.popularpost.style-2 .pupular-post-wrapper .post-item.post-list {
		position: relative;
		display: flex;
		align-items: center;
		justify-content: flex-end;
		min-height: 450px;
		padding: 50px 0;
		background: transparent;
		border: none;
	}

	.popularpost.style-2 .pupular-post-wrapper .post-item.post-list .post-item-image {
		position: absolute;
		height: 100%;
		width: calc(60% - 50px);
		background-size: cover;
		background-position: 50%;
		left: 0;
		top: 0;
		max-width: none;
	}

	.popularpost.style-2 .pupular-post-wrapper .post-item.post-list .post-item-content {
		flex-grow: 0;
		position: relative;
		z-index: 2;
		width: 50%;
		padding: 50px;
		background-color: #fafafa;
	}

	.popularpost.style-2 .pupular-post-wrapper .post-item.post-list:nth-child(even) {
		flex-direction: row-reverse;
	}

	.popularpost.style-2 .pupular-post-wrapper .post-item.post-list:nth-child(even) .post-item-image {
		left: unset;
		right: 0;
	}
}

/* popular post style2  */
@media (max-width: 600px) {
	.pupular-post-wrapper {
		display: flex;
		gap: 30px;
		flex-direction: column;
	}

	.post-item.post-list:nth-child(even),
	.post-item.post-list {
		flex-direction: column;
		border: none;
	}

	.post-item.post-list .post-item-image {
		max-width: 100%;
	}

	.post-item.post-list .post-item-content {
		text-align: start;
		width: 100%;
		padding-inline: 0;
		padding-block-end: 0;
	}

	.post-item.post-list .post-item-content .entry-meta,
	.post-item.post-list .post-item-content .entry-cat .post-categories {
		justify-content: flex-start;
	}
}

/* End List Posts Section
--------------------------------------------- */

/* Start Posts Overlay Section
--------------------------------------------- */
.recentpost-wrapper {
	display: grid;
	gap: 20px;
	grid-template-columns: repeat(3, 1fr);
}

.post-item.overlay-post {
	min-height: 380px;
	padding: 20px;
	display: flex;
	flex-direction: column;
	justify-content: flex-end;
	position: relative;
	background-repeat: no-repeat;
	background-size: cover;
}

.post-item.overlay-post::after {
	content: "";
	position: absolute;
	left: 0;
	bottom: 0;
	width: 100%;
	height: 100%;
	background-image: -webkit-gradient(linear, left top, left bottom, from(rgba(17, 17, 17, 0)), color-stop(80%, rgba(17, 17, 17, 0.6)), to(#111111));
	background-image: linear-gradient(to bottom, rgba(17, 17, 17, 0) 0%, rgba(17, 17, 17, 0.6) 80%, #111111 100%);
	background-repeat: no-repeat;
	background-size: cover;
	background-position: center center;
}

.post-item.overlay-post .post-overlay {
	position: relative;
	z-index: 1;
}

.post-item.overlay-post .post-item-content .entry-cat .post-categories li a {
	display: block;
	text-decoration: none;
	font-weight: 500;
	text-transform: capitalize;
	color: #eee;
	background-color: transparent;
	border: 1px solid #d0d0d0;
	transition: all 0.4s ease-in-out;
	border-radius: 3px;
}

.post-item.overlay-post .post-item-content .entry-cat .post-categories li a:focus,
.post-item.overlay-post .post-item-content .entry-cat .post-categories li a:hover {
	background-color: var(--primary-color);
	border: 1px solid var(--primary-color);
	opacity: 1;
}

.post-item.overlay-post .post-item-content .entry-cat .post-categories li a:focus {
	outline-color: #fff;
}

.post-item.overlay-post .post-item-content .entry-title a:focus,
.post-item.overlay-post .post-item-content .entry-title a:hover,
.post-item.overlay-post .post-item-content .entry-title a {
	color: #fff;
}

.post-item.overlay-post .post-item-content .entry-meta li {
	color: #fff;
}

.post-item.overlay-post .post-item-content .entry-meta li a {
	color: #fff;
}

@media (max-width: 768px) {
	.recentpost-wrapper {
		grid-template-columns: repeat(2, 1fr);
	}

	.post-item.overlay-post {
		min-height: 380px;
	}
}

@media (max-width: 480px) {
	.recentpost-wrapper {
		grid-template-columns: repeat(1, 1fr);
	}
}


/* recent post style 2  */
.recentpost.style-2 .recentpost-wrapper .post-item.overlay-post {
	min-height: 280px;
}

@media (min-width: 600px) {
	.recentpost.style-2 .recentpost-wrapper .post-item.overlay-post:first-child {
		grid-column: span 2;
		grid-row: span 2;
	}
}

/* recent post style 2  */
/* End Posts Overlay Section
--------------------------------------------- */

/* Start archive layouts
--------------------------------------------- */

/* grid layout */
.theme-archive-layout.grid-layout {
	display: grid;
	gap: 10px;
}

/* one column */
.theme-archive-layout.grid-layout.grid-column-1 {
	grid-template-columns: repeat(1, 1fr);
}

/* one column */

/* two columns */
.theme-archive-layout.grid-layout.grid-column-2 {
	grid-template-columns: repeat(2, 1fr);
}

@media (max-width:600px) {
	.theme-archive-layout.grid-layout.grid-column-2 {
		grid-template-columns: repeat(1, 1fr);
	}
}

/* two columns */

/* three columns */
.theme-archive-layout.grid-layout.grid-column-3 {
	grid-template-columns: repeat(3, 1fr);
}

@media (max-width:768px) {
	.theme-archive-layout.grid-layout.grid-column-3 {
		grid-template-columns: repeat(2, 1fr);
	}
}

@media (max-width:600px) {
	.theme-archive-layout.grid-layout.grid-column-3 {
		grid-template-columns: repeat(1, 1fr);
	}
}

/* three columns */

/* four columns */
.theme-archive-layout.grid-layout.grid-column-4 {
	grid-template-columns: repeat(4, 1fr);
}

@media (max-width:1024px) {
	.theme-archive-layout.grid-layout.grid-column-4 {
		grid-template-columns: repeat(3, 1fr);
	}
}

@media (max-width:768px) {
	.theme-archive-layout.grid-layout.grid-column-4 {
		grid-template-columns: repeat(2, 1fr);
	}
}

@media (max-width:600px) {
	.theme-archive-layout.grid-layout.grid-column-4 {
		grid-template-columns: repeat(1, 1fr);
	}
}

/* four columns */

/* grid layout */
/* list layout */
.theme-archive-layout.list-layout {
	display: grid;
	gap: 10px;
	margin-bottom: 50px;
}

.theme-archive-layout.list-layout article {
	margin-bottom: 0;
}

.theme-archive-layout.list-layout article .post-item.post-list {
	border: none;
}

@media (min-width:991px) {
	.theme-archive-layout.list-layout.list-style-2 article .post-item.post-list {
		flex-direction: row-reverse;
	}

	.theme-archive-layout.list-layout.list-style-3 article:nth-child(even) .post-item.post-list {
		flex-direction: row-reverse;
	}
}

/* list-style-4   */
@media (min-width: 600px) {
	.theme-archive-layout.list-layout.list-style-4 {
		gap: 50px;
	}

	.theme-archive-layout.list-layout.list-style-4 article .post-item.post-list {
		position: relative;
		display: flex;
		align-items: center;
		justify-content: flex-end;
		min-height: 450px;
		padding: 50px 0;
		background: transparent;
		border: none;
	}

	.theme-archive-layout.list-layout.list-style-4 article .post-item.post-list .post-item-image {
		position: absolute;
		height: 100%;
		width: calc(60% - 50px);
		background-size: cover;
		background-position: 50%;
		left: 0;
		top: 0;
		max-width: none;
	}

	.theme-archive-layout.list-layout.list-style-4 article .post-item.post-list .post-item-content {
		flex-grow: 0;
		position: relative;
		z-index: 2;
		width: 50%;
		padding: 30px;
		background-color: #fafafa;
	}

	.theme-archive-layout.list-layout.list-style-4 article:nth-child(even) .post-item.post-list {
		flex-direction: row-reverse;
	}

	.theme-archive-layout.list-layout.list-style-4 article:nth-child(even) .post-item.post-list .post-item-image {
		left: unset;
		right: 0;
	}
}

/* list-style-4   */
/* list layout */

/* End archive layouts
--------------------------------------------- */
/* Start Post navigations
--------------------------------------------- */

.site-main .post-navigation,
.site-main .posts-navigation {
	padding: 20px 0;
	border-block: 1px solid rgba(var(--color-text-rgb), 0.15);
}

.post-navigation .nav-links,
.posts-navigation .nav-links {
	display: flex;
}

@media only screen and (max-width: 480px) {

	.post-navigation .nav-links,
	.posts-navigation .nav-links {
		flex-wrap: wrap;
	}
}

.post-navigation .nav-previous,
.posts-navigation .nav-previous {
	flex: 1 0 50%;
}

.post-navigation .nav-previous a,
.posts-navigation .nav-previous a {
	display: inline-flex;
	align-items: center;
	gap: 5px;
	color: var(--color-text);
	transition: all 1s cubic-bezier(0.25, 0.8, 0.25, 1);
	text-decoration: none;
}

.post-navigation .nav-previous a::before,
.posts-navigation .nav-previous a::before {
	font-style: normal;
	font-variant: normal;
	font-weight: 400;
	line-height: 1;
	font-family: Font Awesome\ 5 Free;
	font-weight: 900;
	line-height: inherit;
	vertical-align: baseline;
	content: "\f104";
	display: inline-block;
}

.post-navigation .nav-previous a:hover,
.posts-navigation .nav-previous a:hover {
	color: var(--primary-color);
}

@media only screen and (max-width: 480px) {

	.post-navigation .nav-previous a,
	.posts-navigation .nav-previous a {
		flex-direction: column;
		align-items: flex-start;
	}
}

.post-navigation .nav-next,
.posts-navigation .nav-next {
	text-align: end;
	flex: 1 0 50%;
}

.post-navigation .nav-next a,
.posts-navigation .nav-next a {
	display: inline-flex;
	align-items: center;
	gap: 5px;
	justify-content: flex-end;
	color: var(--color-text);
	transition: all 1s cubic-bezier(0.25, 0.8, 0.25, 1);
	text-decoration: none;
}

.post-navigation .nav-next a::after,
.posts-navigation .nav-next a::after {
	font-style: normal;
	font-variant: normal;
	font-weight: 400;
	line-height: 1;
	font-family: Font Awesome\ 5 Free;
	font-weight: 900;
	line-height: inherit;
	vertical-align: baseline;
	content: "\f105";
	display: inline-block;
}

.post-navigation .nav-next a:focus,
.post-navigation .nav-next a:hover,
.posts-navigation .nav-next a:focus,
.posts-navigation .nav-next a:hover {
	color: var(--primary-color);
}

@media only screen and (max-width: 480px) {

	.post-navigation .nav-next a,
	.posts-navigation .nav-next a {
		flex-direction: column;
		align-items: flex-end;
	}

	.post-navigation .nav-next a>*,
	.posts-navigation .nav-next a>* {
		order: 1;
	}

	.post-navigation .nav-next a::after,
	.posts-navigation .nav-next a::after {
		order: 0;
	}
}


/* numeric pagination     */
nav.navigation.pagination .nav-links {
	display: flex;
	gap: 5px;
	margin: 10px 0 20px;
	justify-content: center;
}

nav.navigation.pagination .nav-links span,
nav.navigation.pagination .nav-links a {
	text-decoration: none;
	width: 30px;
	height: 30px;
	display: flex;
	align-items: center;
	justify-content: center;
	transition: all 0.3s ease;
	color: var(--color-text);
	border: 1px solid var(--color-text);
}

nav.navigation.pagination .nav-links span.prev,
nav.navigation.pagination .nav-links a.prev,
nav.navigation.pagination .nav-links span.next,
nav.navigation.pagination .nav-links a.next {
	font-size: 0;
}

nav.navigation.pagination .nav-links span.prev::after,
nav.navigation.pagination .nav-links a.prev::after,
nav.navigation.pagination .nav-links span.next::after,
nav.navigation.pagination .nav-links a.next::after {
	content: "\f30a";
	font-size: 1rem;
	display: inline-block;
	font-style: normal;
	font-variant: normal;
	font-weight: 400;
	line-height: 1;
	font-weight: 900;
	line-height: inherit;
	vertical-align: baseline;
	font-family: Font Awesome\ 5 Free;
	-moz-osx-font-smoothing: grayscale;
	-webkit-font-smoothing: antialiased;
}

nav.navigation.pagination .nav-links span.next::after,
nav.navigation.pagination .nav-links a.next::after {
	content: "\f30b";
}

nav.navigation.pagination .nav-links span:hover,
nav.navigation.pagination .nav-links a:hover,
nav.navigation.pagination .nav-links span:focus,
nav.navigation.pagination .nav-links a:focus {
	color: var(--primary-color);
	border: 1px solid var(--primary-color);
}

nav.navigation.pagination .nav-links span.current {
	color: #fff;
	background-color: var(--primary-color);
	border: 1px solid var(--primary-color);
}

nav.navigation.pagination .nav-links span.dots {
	border: none;
}

nav.navigation.pagination .nav-links span.dots:hover,
nav.navigation.pagination .nav-links span.dots:focus {
	color: var(--color-text);
	border: none;
}

/* numeric pagination     */


/* End Post navigations
--------------------------------------------- */
/* Start Single Post/Page
--------------------------------------------- */

body.sticky {
	display: block;
}

.post,
.page {
	margin: 0 0 1.5em;
}

.updated:not(.published) {
	display: none;
}

.page-content,
.entry-content,
.entry-summary {
	margin: 1.5em 0 0;
}

/*--404 page--*/
section.error-404.not-found {
	margin-bottom: 50px;
	text-align: center;
	max-width: 991px;
	margin-inline: auto;
}

/*--404 page--*/
/*--single--*/
.page-links {
	clear: both;
	margin: 0 0 1.5em;
}

.site-main article .entry-header .entry-title {
	font-size: var(--font-size-lg);
	font-family: var(--font-body);
	margin-top: 0;
	margin-bottom: 1.3rem;
}

@media (min-width: 992px) {
	.site-main article .entry-header .entry-title {
		margin-bottom: 1.1rem;
	}
}

.site-main article .entry-header .entry-title a {
	text-decoration: none;
	color: var(--color-text);
}

.site-main article .entry-meta {
	padding-bottom: 10px;
}

.site-main article .entry-meta span {
	font-size: 16px;
	font-weight: normal;
}

.site-main article .entry-meta span a,
.site-main article .entry-meta span span {
	font-weight: normal;
}

.site-main article .entry-meta span a {
	text-decoration: none;
	color: var(--color-text);
}

.site-main article .entry-meta span a:hover {
	color: var(--primary-color);
}

.site-main article .entry-meta span a i {
	margin-inline-end: 5px;
}

.site-main article .entry-meta span.comments-link a {
	font-weight: bold;
}

.site-main article .post-thumbnail {
	display: block;
	line-height: 0;
}

.site-main article .post-thumbnail img {
	width: 100%;
	transition: all 0.3s linear;
}

@media (min-width: 992px) {
	.site-main article .entry-meta {
		padding: 10px 0 20px;
		padding-top: 0;
	}
}

.site-main article .entry-content {
	margin-top: 0;
}

.site-main article .entry-content p {
	margin-bottom: 10px;
}

.site-main article .entry-footer {
	display: flex;
	flex-direction: column;
	margin-top: 10px;
}

.site-main article .entry-footer span {
	margin-bottom: 6px;
	font-size: 16px;
	font-weight: bold;
}

.site-main article .entry-footer span a,
.site-main article .entry-footer span span {
	font-weight: normal;
}

.site-main article .entry-footer span a {
	text-decoration: none;
	color: var(--color-text);
}

.site-main article .entry-footer span a:hover {
	color: var(--primary-color);
}

.site-main article .entry-footer span.comments-link a {
	font-weight: bold;
}

/*--single--*/
body.single .site-main>article header {
	margin-bottom: 10px;
}

body.single .site-main>article header .entry-title {
	margin-bottom: 10px;
}

body.single .site-main>article header .entry-meta {
	padding-bottom: 0;
	margin-bottom: 10px;
}

.no-sidebar .entry-content {
	max-width: 750px;
	margin-left: auto;
	margin-right: auto;
}

/* End Single Post/Page
--------------------------------------------- */

/* Start breadcrumbs
--------------------------------------------- */

.breadcrumb-trail.breadcrumbs {
	padding: 20px 0px;
}

body.aft-single-full-header .breadcrumb-trail.breadcrumbs {
	padding-bottom: 20px;
}

ul.trail-items {
	font-size: 13px;
	margin: 0;
	padding: 0;
}

ul.trail-items li {
	display: inline-block;
	margin-right: 5px;
}

ul.trail-items li a {
	text-decoration: none;
	font-size: 13px;
	color: var(--color-text);
	opacity: 0.7;
}

ul.trail-items li a:hover {
	opacity: 1;
	color: var(--primary-color);
	transition: all 1200ms cubic-bezier(.215, .610, .355, 1);
}

ul.trail-items li:after {
	content: ' / ';
	padding: 0 2px;
	color: var(--color-text);
	font-size: 13px;
}

ul.trail-items li:last-child:after {
	display: none;
}

/* End breadcrumbs
--------------------------------------------- */
/* Start comments css
--------------------------------------------- */

.comment-content a {
	word-wrap: break-word;
}

.bypostauthor {
	display: block;
}

/** * Comments Wrapper */
.comments-area {
	padding-bottom: 30px;
}

.comments-area>* {
	margin-top: 30px;
	margin-bottom: 30px;
}

.comments-area>*:first-child {
	margin-top: 0;
}

.comments-area>*:last-child {
	margin-bottom: 0;
}

.comments-area.show-avatars .avatar {
	border-radius: 50%;
	position: absolute;
	top: 10px;
}

.comments-area.show-avatars .fn {
	display: inline-block;
	padding-left: 85px;
}

.comments-area.show-avatars .comment-metadata {
	padding: 8px 0 9px 85px;
}

/** * Comment Title */
.comment-reply-title {
	display: flex;
	justify-content: space-between;
}

.comment-reply-title small a {
	font-size: 15px;
	font-style: normal;
	font-weight: normal;
	letter-spacing: normal;
}

/* Nested comment reply title*/
.comment .comment-respond .comment-reply-title {
	font-size: 30px;
}

/** * Comment Lists */
.comments-area [type="checkbox"],
.comments-area [type="radio"] {
	margin-bottom: 7px;
	margin-right: 10px;
}

.comment-list {
	padding-left: 0;
	list-style: none;
	margin-left: 0;
}

.comment-list ol {
	margin-left: 0;
}

.comment-list>li {
	margin-top: 30px;
	margin-bottom: 30px;
}

.comment-list .children {
	list-style: none;
	padding-left: 0;
}

.comment-list .children>li {
	margin-top: 30px;
	margin-bottom: 30px;
}

@media only screen and (min-width: 482px) {

	.comment-list .depth-2,
	.comment-list .depth-3 {
		padding-left: calc(4 * 20px);
	}
}

/** * Comment Meta */
.comment-meta .comment-author {
	margin-bottom: calc(0.25 *20px);
}

@media only screen and (min-width: 482px) {
	.comment-meta .comment-author {
		margin-bottom: 0;
		padding-right: 0;
	}
}

.comment-meta .comment-author .fn {
	font-weight: normal;
	hyphens: auto;
	word-wrap: break-word;
	word-break: break-word;
}

.comment-meta .comment-metadata {
	color: var(--text-color-normal);
	padding: 8px 0 9px 0;
	font-size: 15px;
	display: flex;
	justify-content: space-between;
}

.comment-meta .comment-metadata .edit-link {
	margin-left: 20px;
}

@media only screen and (min-width: 482px) {
	.comment-meta {
		margin-right: inherit;
	}

	.comment-meta .comment-author {
		max-width: inherit;
	}
}

.bypostauthor {
	display: block;
}

.says {
	display: none;
}

.comment-meta {
	margin-bottom: 10px;
}

.comment-body {
	position: relative;
	margin-bottom: 40px;
	padding: 30px;
	background-color: #f9f9f9;
	border: 1px solid #eee;
}

.dark-mode .comment-body {
	background-color: var(--color-dark);
	border: 1px solid rgba(var(--color-text-rgb), 0.15);
}

.comment-body .reply {
	margin: 0;
}

.comment-content {
	word-wrap: break-word;
	font-size: 16px;
	padding-bottom: 15px;
	color: var(--color-text);
}

.pingback .comment-body,
.trackback .comment-body {
	margin-top: 30px;
	margin-bottom: 30px;
}

.comment-respond {
	margin-top: 30px;
}

.comment-respond>* {
	margin-top: 20px;
	margin-bottom: 20px;
}

.comment-respond>*:first-child {
	margin-top: 0;
}

.comment-respond>*:last-child {
	margin-bottom: 0;
}

.comment-respond>*:last-child.comment-form {
	margin-bottom: 30px;
}

.comment-author {
	padding-top: 3px;
}

.reply a,
.comment-content a,
.comment-meta .comment-metadata a,
.comment-author .url {
	color: currentColor;
}

.reply a:focus,
.comment-content a:focus,
.comment-meta .comment-metadata a:focus,
.comment-author .url:focus,
.reply a:hover,
.comment-content a:hover,
.comment-meta .comment-metadata a:hover,
.comment-author .url:hover {
	color: var(--theme-color);
}

.comment-form {
	display: flex;
	flex-wrap: wrap;
}

.comment-form>* {
	flex-basis: 100%;
}

.comment-form .comment-form-url,
.comment-form .comment-form-comment {
	width: 100%;
}

.comment-form .comment-form-author,
.comment-form .comment-form-email {
	flex-basis: 0;
	flex-grow: 1;
}

@media only screen and (max-width: 481px) {

	.comment-form .comment-form-author,
	.comment-form .comment-form-email {
		flex-basis: 100%;
	}
}

.comment-form .comment-form-cookies-consent>label,
.comment-form .comment-notes {
	font-size: 1rem;
	font-weight: normal;
}

.comment-form>p {
	margin-bottom: 10px;
}

.comment-form>p a {
	color: var(--text-color-normal);
	transition: all 1s cubic-bezier(0.25, 0.8, 0.25, 1);
	text-decoration: none;
}

.comment-form>p a:focus,
.comment-form>p a:hover {
	color: var(--theme-color);
}

.comment-form>p:first-of-type {
	margin-top: 0;
}

.comment-form>p:last-of-type {
	margin-bottom: 0;
}

.comment-form>p label,
.comment-form>p input[type=email],
.comment-form>p input[type=text],
.comment-form>p input[type=url],
.comment-form>p textarea {
	display: block;
	font-size: var(--global--font-size-sm);
	margin-bottom: calc(.5 *20px);
	width: 100%;
	font-weight: var(--form--label-weight);
}

.comment-form>p.comment-form-cookies-consent {
	display: flex;
	align-items: center;
}

@media only screen and (min-width: 482px) {

	.comment-form>p.comment-form-author,
	.woocommerce #review_form #respond p {
		margin-right: calc(1.5 * 20px);
	}

	.comment-form>p.comment-notes,
	.comment-form>p.logged-in-as {
		display: block;
	}
}

nav.breadcrumb-trail ul.trail-items {
	list-style: none;
	padding: 0;
	margin: 0;
	color: var(--text-color-normal);
}

nav.breadcrumb-trail ul.trail-items li {
	display: inline-block;
}

nav.breadcrumb-trail ul.trail-items li a {
	text-decoration: none;
	color: var(--text-color-normal);
}

nav.breadcrumb-trail ul.trail-items li a:hover {
	color: var(--theme-color);
}

nav.breadcrumb-trail ul.trail-items li::after {
	margin: 0 0.3rem;
}

nav.breadcrumb-trail ul.trail-items li:last-child::after {
	display: none;
}

/*comments section====*/
#comments.comments-area {
	margin-block: 20px;
}

#comments.comments-area .comments-title {
	font-size: var(--font-size-lg);
	font-family: var(--font-body);
	line-height: 1.2;
}

#comments.comments-area .comment-list .comment .comment-author img {
	float: left;
	margin-right: 20px;
	margin-bottom: 20px;
	width: 50px;
}

#comments.comments-area .comment-list .comment .comment-content p {
	margin-bottom: 5px;
}

#comments.comments-area div#respond {
	margin-top: 20px;
}

#comments.comments-area div#respond #reply-title {
	margin-top: 0;
	font-weight: 700;
	font-size: 18px;
}

#comments.comments-area div#respond p {
	margin-bottom: 5px;
}

#comments.comments-area div#respond label {
	font-weight: normal;
}

#comments.comments-area div#respond textarea {
	width: 100%;
	background: #fafafa;
}

#comments.comments-area div#respond p.comment-form-url,
#comments.comments-area div#respond p.comment-form-email,
#comments.comments-area div#respond p.comment-form-author {
	display: inline-block;
	width: 100%;
}

#comments.comments-area div#respond p.comment-form-url label,
#comments.comments-area div#respond p.comment-form-email label,
#comments.comments-area div#respond p.comment-form-author label {
	display: block;
}

#comments.comments-area div#respond p.comment-form-url input,
#comments.comments-area div#respond p.comment-form-email input,
#comments.comments-area div#respond p.comment-form-author input {
	width: 100%;
}

#comments.comments-area div#respond p.comment-form-cookies-consent label {
	margin-left: 8px;
	position: relative;
	top: -1px;
}

#comments.comments-area div#respond input[type="submit"] {
	display: inline-block;
	margin-top: 10px;
}

#comments.comments-area div#respond #reply-title small a {
	display: inline-block;
	margin-left: 10px;
}

.comment div#respond,
.comment-content {
	margin-left: 70px;
}

.comment-content a {
	word-wrap: break-word;
}

.bypostauthor {
	display: block;
}

/* End comments css
--------------------------------------------- */

/* Newsletter css start
--------------------------------------------- */

.newsletter-section {
	position: relative;
	padding: 60px 0;
}

.newsletter-section .section-background-img {
	position: absolute;
	width: 100%;
	height: 100%;
	top: 0;
	left: 0;
	z-index: 0;
	opacity: 0.4;
}

.newsletter-section .section-background-img img {
	width: 100%;
	height: 100%;
	object-fit: cover;
}

.newsletter-section .newsletter-section-wrapper {
	position: relative;
	display: flex;
	flex-wrap: wrap;
	align-items: center;
	justify-content: space-between;
}

@media (max-width: 992px) {
	.newsletter-section .newsletter-section-wrapper {
		flex-direction: column;
	}
}

.newsletter-section .newsletter-section-wrapper .text-section {
	color: #fff;
}

.newsletter-section .newsletter-section-wrapper .text-section .newsletter-title {
	font-size: var(--font-size-md);
	line-height: normal;
	margin-top: 0;
	margin-bottom: 10px;
}

.newsletter-section .newsletter-section-wrapper .text-section p {
	margin: 0;
}

@media (max-width: 992px) {
	.newsletter-section .newsletter-section-wrapper .text-section p {
		margin-bottom: 20px;
		text-align: center;
	}
}

.newsletter-section .newsletter-section-wrapper .newsletter-form .jetpack_subscription_widget .widgettitle {
	display: none;
}

.newsletter-section .newsletter-section-wrapper .newsletter-form .jetpack_subscription_widget form {
	display: flex;
}

.newsletter-section .newsletter-section-wrapper .newsletter-form .jetpack_subscription_widget form p {
	display: flex;
	margin: 0;
}

.newsletter-section .newsletter-section-wrapper .newsletter-form .jetpack_subscription_widget form p input {
	padding: 12px 30px;
	border: 1px solid #fff;
	background-color: transparent;
	border-radius: 0;
	color: #fff;
}

.newsletter-section .newsletter-section-wrapper .newsletter-form .jetpack_subscription_widget form p input:focus,
.newsletter-section .newsletter-section-wrapper .newsletter-form .jetpack_subscription_widget form p input:focus-visible {
	outline: none;
}

.newsletter-section .newsletter-section-wrapper .newsletter-form .jetpack_subscription_widget form p input::placeholder {
	color: #fff;
}

.newsletter-section .newsletter-section-wrapper .newsletter-form .jetpack_subscription_widget form p#subscribe-email input {
	width: 100%;
}

@media (max-width: 480px) {
	.newsletter-section .newsletter-section-wrapper .newsletter-form .jetpack_subscription_widget form p#subscribe-email input {
		width: 200px;
	}
}

@media (max-width: 320px) {
	.newsletter-section .newsletter-section-wrapper .newsletter-form .jetpack_subscription_widget form p#subscribe-email input {
		width: 150px;
	}
}

.newsletter-section .newsletter-section-wrapper .newsletter-form button[type="submit"] {
	cursor: pointer;
	border: none;
	border-radius: 0;
	color: #fff;
	background-color: var(--primary-color);
	font-size: var(--font-size-sm);
	text-decoration: none;
	text-transform: capitalize;
	font-weight: bold;
	display: flex;
	align-items: center;
	padding: 15px 25px;
	transition: all 0.3s ease;
	position: relative;
}

/* Newsletter css end
--------------------------------------------- */

/* Custom widgets start
--------------------------------------------- */
.widget-header {
	position: relative;
}

.section-header-1 .widget-title {
	padding-block-end: 10px;
	border-bottom: 1px solid rgba(var(--color-text-rgb), 0.15);
	text-align: left;
	background: none;
	position: relative;
	margin: 0;
	line-height: 1.2;
	margin-bottom: 15px;
	color: var(--color-text);
	font-size: var(--font-size-base);
}

.section-header-1 .site-footer .widget-title {
	border-bottom: 1px double rgba(255, 255, 255, 0.15);
}

.section-header-1 .widget-title::after {
	position: absolute;
	bottom: -2px;
	left: 0;
	content: "";
	width: 60px;
	height: 3px;
	background: var(--primary-color);
}

.section-header-1 .widget-header>a {
	position: absolute;
	top: 0;
	right: 0;
	padding-block: 5px;
}

.section-header-3 .widget-header,
.section-header-2 .widget-header {
	display: flex;
	justify-content: space-between;
	align-items: center;
	gap: 15px;
}

.section-header-3 .site-footer .tab-filter-widget .widget-header,
.section-header-2 .site-footer .tab-filter-widget .widget-header,
.section-header-3 .secondary-widgets-area .tab-filter-widget .widget-header,
.section-header-2 .secondary-widgets-area .tab-filter-widget .widget-header {
	flex-direction: column;
	align-items: stretch;
	gap: 0;
}

.section-header-3 .site-footer .widget-header .tab-filter-widget .widget-title,
.section-header-2 .site-footer .widget-header .tab-filter-widget .widget-title,
.section-header-3 .secondary-widgets-area .widget-header .tab-filter-widget .widget-title,
.section-header-2 .secondary-widgets-area .widget-header .tab-filter-widget .widget-title {
	margin-bottom: 5px;
}

.section-header-3 .widget-title,
.section-header-2 .widget-title {
	flex-grow: 1;
	text-align: start;
	background: none;
	position: relative;
	margin: 0;
	line-height: 1.2;
	margin-bottom: 15px;
	color: var(--color-text);
	font-size: var(--font-size-base);
	display: flex;
	align-items: center;
	gap: 10px;
}

@media (max-width: 600px) {

	.section-header-3 .tab-filter-widget .widget-header,
	.section-header-2 .tab-filter-widget .widget-header {
		flex-direction: column;
		align-items: stretch;
		gap: 0;
	}

	.section-header-3 .tab-filter-widget .widget-title,
	.section-header-2 .tab-filter-widget .widget-title {
		margin-bottom: 5px;
	}
}

.section-header-3 .widget-title::before,
.section-header-2 .widget-title::before {
	display: inline-block;
	content: "";
	width: 10px;
	height: 10px;
	border-radius: 50%;
	background: var(--primary-color);
	order: 2;
}

.section-header-3 .widget-title::before {
	width: 30px;
	height: 3px;
	order: 0;
	border-radius: 0;
}

.section-header-3 .widget-title::after,
.section-header-2 .widget-title::after {
	display: inline-block;
	content: "";
	width: 10px;
	flex-grow: 1;
	height: 6px;
	border: 1px double rgba(var(--color-text-rgb), 0.15);
	border-width: 1px 0 1px 0;
	order: 3;
}

.section-header-3 .widget-title::after {
	border-radius: 0;
	height: 3px;
	border: none;
	background-color: rgba(var(--color-text-rgb), 0.15);
}

.section-header-2 .site-footer .widget-title::after {
	border: 1px double rgba(255, 255, 255, 0.15);
	border-width: 1px 0 1px 0;
}

.section-header-3 .site-footer .widget-title::after {
	background-color: rgba(255, 255, 255, 0.15);
}

.section-header-3 .widget-header>a,
.section-header-2 .widget-header>a {
	margin-bottom: 15px;
}

.widget-header>a {
	text-decoration: none;
	font-size: var(--font-size-xs);
	color: var(--color-text);
	transition: all 0.5s;
	font-weight: bold;
	letter-spacing: 0.5px;
}

.widget-header>a::after {
	font-style: normal;
	font-variant: normal;
	font-weight: 400;
	line-height: 1;
	font-family: Font Awesome\ 5 Free;
	font-weight: 900;
	line-height: inherit;
	vertical-align: baseline;
	content: "\f101";
	display: inline-block;
	margin-inline-start: 10px;
}

.widget-header>a:focus,
.widget-header>a:hover {
	color: var(--primary-color);
}

/* social widget start*/
.social-widget .social-widgets-wrap {
	display: flex;
	flex-wrap: wrap;
	gap: 10px;
}

.social-widget.style-2 .social-widgets-wrap {
	gap: 5px;
}

.social-widget.style-2 .social-widgets-wrap a {
	padding: 12px 20px;
	padding-inline-start: 12px;
}

.social-widget.style-2 .social-widgets-wrap a .screen-reader-text {
	clip: unset;
	clip-path: unset;
	height: auto;
	width: auto;
	margin: 0;
	position: relative !important;
	overflow: visible;
	color: #fff;
	top: inherit;
	margin-inline-start: 5px;
}


/* social widget end*/
/* author widget start*/
.author-widget {
	padding: 15px;
	text-align: center;
	color: var(--color-text);
}

.site-footer .author-widget {
	color: #fff;
}

.author-widget .author-img img {
	width: 250px;
	height: 250px;
	object-fit: cover;
	margin: 15px 0;
	border-radius: 50%;
}

.author-widget .author-details .author-name {
	margin: 0 0 10px;
	font-size: var(--font-size-base);
	font-weight: 700;
	line-height: 1.3;
}

.author-widget .author-details .author-social-contacts {
	display: inline-flex;
	gap: 10px;
}

/* author widget end */

/* featured widget start */
.featured-widget .post-item.post-list {
	border: none;
	align-items: center;
	margin-bottom: 20px;
}

.featured-widget .post-item.post-list:nth-child(even) {
	flex-direction: row;
}

.featured-widget .post-item.post-list .post-item-image {
	flex: 0 0 25%;
	max-width: 25%;
	align-self: start;
}

.featured-widget .post-item.post-list .post-item-content {
	flex-grow: 1;
	padding-inline-start: 10px;
	text-align: start;
}

#secondary .featured-widget .post-item .post-item-content,
.site-footer .featured-widget .post-item .post-item-content,
.secondary-widgets-area .featured-widget .post-item .post-item-content {
	padding-block: 0;
	padding-inline-end: 0;
}

.featured-widget .post-item .post-item-content .entry-title {
	margin-block: 10px;
	margin-block-start: 0;
	line-height: 1.3;
}


#secondary .featured-widget .post-item .post-item-content .entry-title,
.site-footer .featured-widget .post-item .post-item-content .entry-title,
.secondary-widgets-area .featured-widget .post-item .post-item-content .entry-title {
	font-size: var(--font-size-sm);
}

.featured-widget .post-item.post-list .post-item-content .entry-meta,
.featured-widget .post-item.post-list .post-item-content .entry-cat .post-categories {
	justify-content: flex-start;
}

.featured-widget .post-item.post-list .post-item-content .entry-meta {
	margin: 0;
}

#secondary .featured-widget .post-item .post-item-content .post-exerpt,
.site-footer .featured-widget .post-item .post-item-content .post-exerpt,
.secondary-widgets-area .featured-widget .post-item .post-item-content .post-exerpt {
	display: none;
}

.featured-widget .entry-meta li {
	border: none;
	padding: 0;
}

@media (max-width: 600px) {

	.featured-widget .post-item.post-list:nth-child(even),
	.featured-widget .post-item.post-list {
		flex-direction: row;
	}

	.featured-widget .post-item.post-list:nth-child(even) .post-item-content .post-exerpt,
	.featured-widget .post-item.post-list .post-item-content .post-exerpt {
		display: none;
	}
}

/* featured style 2 */
.featured-widget.style-2 .post-item.post-list {
	flex-direction: row-reverse;
}

#secondary .featured-widget.style-2 .post-item .post-item-content,
.site-footer .featured-widget.style-2 .post-item .post-item-content,
.secondary-widgets-area .featured-widget.style-2 .post-item .post-item-content,
.featured-widget.style-2 .post-item.post-list .post-item-content {
	text-align: end;
	padding-inline-end: 10px;
	padding-inline-start: 10px;
}

.featured-widget.style-2 .post-item.post-list .post-item-content .entry-meta {
	justify-content: flex-end;
}

/* featured style 2 */
/* featured style 3 */
.featured-widget.style-3 .post-item.post-list {
	position: relative;
	min-height: 150px;
}

.site-footer .featured-widget.style-3 .post-item.post-list,
.secondary-widgets-area .featured-widget.style-3 .post-item.post-list,
#secondary .featured-widget.style-3 .post-item.post-list {
	min-height: unset;
}

.featured-widget.style-3 .post-item.post-list .post-item-image {
	position: absolute;
	left: 0;
	top: 0;
	width: 100%;
	height: 100%;
	max-width: none;
}

.featured-widget.style-3 .post-item.post-list .post-item-image a {
	position: relative;
}

.featured-widget.style-3 .post-item.post-list .post-item-image a::before {
	content: "";
	position: absolute;
	left: 0;
	bottom: 0;
	width: 100%;
	height: 100%;
	z-index: 2;
	background-image: linear-gradient(to bottom, rgba(17, 17, 17, 0) 0%, rgba(17, 17, 17, 0.6) 40%, #111111 100%);
	background-repeat: no-repeat;
	background-size: cover;
	background-position: center center;
}

.featured-widget.style-3 .post-item.post-list .post-item-image a img {
	max-width: none;
	aspect-ratio: unset;
}

.featured-widget.style-3 .post-item.post-list .post-item-content {
	padding: 20px;
	position: relative;
	z-index: 2;
}

.featured-widget.style-3 .post-item.post-list .post-item-content .entry-title a:focus,
.featured-widget.style-3 .post-item.post-list .post-item-content .entry-title a:hover,
.featured-widget.style-3 .post-item.post-list .post-item-content .entry-title a {
	color: #fff;
}

.featured-widget.style-3 .post-item.post-list .post-item-content .entry-meta li,
.featured-widget.style-3 .post-item.post-list .post-item-content .entry-meta li a {
	color: #fff;
}

.featured-widget.style-3 .post-item.post-list .post-item-content .entry-meta li span.line {
	background-color: #fff;
}

.featured-widget.style-3 .post-item.post-list .post-item-content .post-exerpt {
	display: none;
}

/* featured style 3 */
/* featured widget end */
/* grid widget start */
.grid-widget .adore-widget-body {
	display: grid;
	gap: 20px;
	grid-template-columns: repeat(2, 1fr);
}

.above-footer-widget-section-wrap .grid-widget .adore-widget-body {
	grid-template-columns: repeat(3, 1fr);
}

@media (max-width: 768px) {
	.above-footer-widget-section-wrap .grid-widget .adore-widget-body {
		grid-template-columns: repeat(2, 1fr);
	}
}

@media (max-width: 600px) {

	.above-footer-widget-section-wrap .grid-widget .adore-widget-body,
	.grid-widget .adore-widget-body {
		grid-template-columns: repeat(1, 1fr);
	}
}

#secondary .grid-widget .adore-widget-body,
.site-footer .grid-widget .adore-widget-body,
.secondary-widgets-area .grid-widget .adore-widget-body {
	grid-template-columns: repeat(2, 1fr);
}

.site-footer .grid-widget .post-item .post-item-image a img,
.primary-widgets-area .grid-widget .post-item .post-item-image a img {
	aspect-ratio: 1/0.7;
}

#secondary .grid-widget .post-item .post-item-content,
.site-footer .grid-widget .post-item .post-item-content,
.secondary-widgets-area .grid-widget .post-item .post-item-content {
	padding: 10px;
}

#secondary .grid-widget .post-item .post-item-content .entry-title,
.site-footer .grid-widget .post-item .post-item-content .entry-title,
.secondary-widgets-area .grid-widget .post-item .post-item-content .entry-title {
	margin-block: 10px;
	margin-block-start: 0;
	line-height: 1.3;
	font-size: var(--font-size-sm);
}

#secondary .grid-widget .post-item.post-grid .post-item-content .entry-meta,
.secondary-widgets-area .grid-widget .post-item.post-grid .post-item-content .entry-meta {
	margin: 0;
}

.site-footer .grid-widget .post-item.post-grid .post-item-content .entry-meta {
	display: none;
}

#secondary .grid-widget .post-item .post-item-content .post-categories,
#secondary .grid-widget .post-item .post-item-content .post-exerpt,
#secondary .grid-widget .post-item .post-item-content .post-btn,
.site-footer .grid-widget .post-item .post-item-content .post-categories,
.site-footer .grid-widget .post-item .post-item-content .post-exerpt,
.site-footer .grid-widget .post-item .post-item-content .post-btn,
.secondary-widgets-area .grid-widget .post-item .post-item-content .post-categories,
.secondary-widgets-area .grid-widget .post-item .post-item-content .post-exerpt,
.secondary-widgets-area .grid-widget .post-item .post-item-content .post-btn {
	display: none;
}

.grid-widget .entry-meta li {
	border: none;
	padding: 0;
}

@media (max-width: 320px) {

	.grid-widget .adore-widget-body {
		grid-template-columns: repeat(1, 1fr);
	}
}

/* grid widget end */

/* most read widget widget start */

.latest-widget .post-latest-widget-wrapper {
	display: grid;
	grid-gap: 20px;
	grid-template-columns: repeat(3, 1fr);
}

.above-footer-widget-section-wrap .latest-widget .post-latest-widget-wrapper,
.full-width .latest-widget .post-latest-widget-wrapper {
	grid-template-columns: repeat(4, 1fr);
}

#secondary .latest-widget .post-latest-widget-wrapper,
.site-footer .latest-widget .post-latest-widget-wrapper,
.secondary-widgets-area .latest-widget .post-latest-widget-wrapper {
	grid-template-columns: repeat(2, 1fr);
}

.site-footer .latest-widget .post-latest-widget-wrapper {
	grid-template-columns: repeat(1, 1fr);
}

@media (max-width: 768px) {

	.latest-widget .post-latest-widget-wrapper,
	.above-footer-widget-section-wrap .latest-widget .post-latest-widget-wrapper,
	.full-width .latest-widget .post-latest-widget-wrapper {
		grid-template-columns: repeat(3, 1fr);
	}
}

@media (max-width: 600px) {

	.latest-widget .post-latest-widget-wrapper,
	.above-footer-widget-section-wrap .latest-widget .post-latest-widget-wrapper,
	.full-width .latest-widget .post-latest-widget-wrapper {
		grid-template-columns: repeat(1, 1fr);
	}
}

/* most read widget widget end */

/* list widget start */

.posts-tabs-widget .post-item.post-list,
.posts-tabs-widget .post-item.post-list:nth-child(even),
.list-widget .post-item.post-list,
.list-widget .post-item.post-list:nth-child(even) {
	flex-direction: row;
	margin-bottom: 20px;
}

.primary-widgets-area .list-widget .post-item.post-list .post-item-image a img {
	aspect-ratio: 1/0.7;
}

#secondary .posts-tabs-widget .post-item.post-list .post-item-content,
.site-footer .posts-tabs-widget .post-item.post-list .post-item-content,
.secondary-widgets-area .posts-tabs-widget .post-item.post-list .post-item-content,
.primary-widgets-area .posts-tabs-widget .post-item.post-list .post-item-content,
#secondary .list-widget .post-list-widget-wrapper .post-item.post-list .post-item-content,
.site-footer .list-widget .post-list-widget-wrapper .post-item.post-list .post-item-content,
.secondary-widgets-area .list-widget .post-list-widget-wrapper .post-item.post-list .post-item-content,
.primary-widgets-area .list-widget .post-list-widget-wrapper .post-item.post-list .post-item-content {
	text-align: start;
	width: 100%;
}

#secondary .posts-tabs-widget .post-item.post-list .post-item-content .entry-meta,
.site-footer .posts-tabs-widget .post-item.post-list .post-item-content .entry-meta,
.secondary-widgets-area .posts-tabs-widget .post-item.post-list .post-item-content .entry-meta,
.primary-widgets-area .posts-tabs-widget .post-item.post-list .post-item-content .entry-meta,
#secondary .list-widget .post-item.post-list .post-item-content .entry-meta,
.site-footer .list-widget .post-item.post-list .post-item-content .entry-meta,
.secondary-widgets-area .list-widget .post-item.post-list .post-item-content .entry-meta,
.primary-widgets-area .list-widget .post-item.post-list .post-item-content .entry-meta {
	justify-content: flex-start;
}

#secondary .posts-tabs-widget .post-item.post-list .post-item-content .entry-cat .post-categories,
.site-footer .posts-tabs-widget .post-item.post-list .post-item-content .entry-cat .post-categories,
.secondary-widgets-area .posts-tabs-widget .post-item.post-list .post-item-content .entry-cat .post-categories,
.primary-widgets-area .posts-tabs-widget .post-item.post-list .post-item-content .entry-cat .post-categories,
#secondary .list-widget .post-item.post-list .post-item-content .entry-cat .post-categories,
.site-footer .list-widget .post-item.post-list .post-item-content .entry-cat .post-categories,
.secondary-widgets-area .list-widget .post-item.post-list .post-item-content .entry-cat .post-categories,
.primary-widgets-area .list-widget .post-item.post-list .post-item-content .entry-cat .post-categories {
	justify-content: flex-start;
}

@media (min-width: 601px) {
	.primary-widgets-area .list-widget .post-list-widget-wrapper {
		display: grid;
		gap: 20px;
	}
}

@media (max-width: 600px) {

	.list-widget .post-item.post-list,
	.list-widget .post-item.post-list:nth-child(even),
	.primary-widgets-area .list-widget .post-list-widget-wrapper {
		display: flex;
		flex-direction: column;
		gap: 0;
	}

	.primary-widgets-area .list-widget .post-item.post-list .post-item-image a img {
		aspect-ratio: 1/0.7;
	}

	.primary-widgets-area .list-widget .post-item.post-list,
	.primary-widgets-area .list-widget .post-item.post-list:nth-child(even) {
		flex-direction: column;
	}

	.primary-widgets-area .post-item.post-list .post-item-image {
		max-width: 100%;
		width: 100%;
	}
}

/* for secondary and footer  */
#secondary .list-widget .post-list-widget-wrapper,
.site-footer .list-widget .post-list-widget-wrapper,
.secondary-widgets-area .list-widget .post-list-widget-wrapper {
	display: flex;
	flex-direction: column;
	gap: 30px;
}

#secondary .list-widget .post-item.post-list .post-item-image a img,
.site-footer .list-widget .post-item.post-list .post-item-image a img,
.secondary-widgets-area .list-widget .post-item.post-list .post-item-image a img {
	aspect-ratio: 1/0.7;
}

#secondary .list-widget .post-item.post-list,
#secondary .list-widget .post-item.post-list:nth-child(even),
.site-footer .list-widget .post-item.post-list,
.site-footer .list-widget .post-item.post-list:nth-child(even),
.secondary-widgets-area .list-widget .post-item.post-list,
.secondary-widgets-area .list-widget .post-item.post-list:nth-child(even) {
	flex-direction: column;
}

#secondary .post-item.post-list .post-item-image,
.site-footer .post-item.post-list .post-item-image,
.secondary-widgets-area .post-item.post-list .post-item-image {
	max-width: 100%;
	width: 100%;
}

/* for secondary and footer  */
/* list-widget style-2  */
@media (min-width: 600px) {
	.primary-widgets-area .list-widget.style-2 .post-list-widget-wrapper {
		gap: 10px;
	}

	.primary-widgets-area .list-widget.style-2 .post-list-widget-wrapper .post-item.post-list {
		position: relative;
		display: flex;
		align-items: center;
		justify-content: flex-end;
		min-height: 450px;
		padding: 50px 0;
		background: transparent;
		border: none;
	}

	.primary-widgets-area .list-widget.style-2 .post-list-widget-wrapper .post-item.post-list .post-item-image {
		position: absolute;
		height: 100%;
		width: calc(60% - 50px);
		background-size: cover;
		background-position: 50%;
		left: 0;
		top: 0;
		max-width: none;
	}

	.primary-widgets-area .list-widget.style-2 .post-list-widget-wrapper .post-item.post-list .post-item-content {
		flex-grow: 0;
		position: relative;
		z-index: 2;
		width: 50%;
		padding: 30px;
		background-color: #fafafa;
	}

	.dark-mode .primary-widgets-area .list-widget.style-2 .post-list-widget-wrapper .post-item.post-list .post-item-content {
		background-color: var(--color-dark);
	}

	.primary-widgets-area .list-widget.style-2 .post-list-widget-wrapper .post-item.post-list:nth-child(even) {
		flex-direction: row-reverse;
	}

	.primary-widgets-area .list-widget.style-2 .post-list-widget-wrapper .post-item.post-list:nth-child(even) .post-item-image {
		left: unset;
		right: 0;
	}
}

/* list-widget style-2  */
/* list widget end */

/* list widget latest-widget start */
.most-read-widget .most-read-widget-wrapper {
	display: grid;
	grid-gap: 20px;
	grid-template-columns: repeat(3, 1fr);
}

.above-footer-widget-section-wrap .most-read-widget .most-read-widget-wrapper,
.full-width .most-read-widget .most-read-widget-wrapper {
	grid-template-columns: repeat(4, 1fr);
}

#secondary .most-read-widget .most-read-widget-wrapper,
.site-footer .most-read-widget .most-read-widget-wrapper,
.secondary-widgets-area .most-read-widget .most-read-widget-wrapper {
	grid-template-columns: repeat(1, 1fr);
}

.most-read-widget .post-item.post-list,
.most-read-widget .post-item.post-list:nth-child(even) {
	flex-direction: row;
}

.most-read-widget .post-item.post-list .post-item-image {
	flex: 0 0 25%;
	max-width: 25%;
	flex-shrink: 0;
}

.most-read-widget .post-item.post-list .post-item-content {
	flex-grow: 1;
	padding: 0;
	padding-inline-end: 10px;
	padding-inline-start: 10px;
	text-align: start;
}

.most-read-widget .post-item.post-list .post-item-content .entry-title {
	font-size: var(--font-size-sm);
	margin-top: 0;
}

.site-footer .most-read-widget .post-item.post-list .post-item-content .entry-title,
.above-footer-widget-section-wrap .most-read-widget .post-item.post-list .post-item-content .entry-title,
.primary-widgets-area .most-read-widget .post-item.post-list .post-item-content .entry-title {
	margin-bottom: 0;
}

.site-footer .most-read-widget .post-item.post-list .post-item-content .entry-meta,
.above-footer-widget-section-wrap .most-read-widget .post-item.post-list .post-item-content .entry-meta,
.primary-widgets-area .most-read-widget .post-item.post-list .post-item-content .entry-meta {
	display: none;
}

.most-read-widget .post-item.post-list .post-item-content .entry-meta,
.most-read-widget .post-item.post-list .post-item-content .entry-cat .post-categories {
	justify-content: flex-start;
}

@media (max-width: 768px) {

	.above-footer-widget-section-wrap .most-read-widget .most-read-widget-wrapper,
	.full-width .most-read-widget .most-read-widget-wrapper,
	.most-read-widget .most-read-widget-wrapper {
		grid-template-columns: repeat(2, 1fr);
	}
}

@media (max-width: 600px) {

	.above-footer-widget-section-wrap .most-read-widget .most-read-widget-wrapper,
	.full-width .most-read-widget .most-read-widget-wrapper,
	.most-read-widget .most-read-widget-wrapper {
		grid-template-columns: repeat(1, 1fr);
	}
}

/* list widget latest-widget end */

/* express list widget start */
.express-list-widget .express-list-widget-wrapper {
	display: grid;
	gap: 20px;
	grid-template-columns: repeat(2, 1fr);
}

.express-list-widget .express-list-widget-wrapper .post-item:first-child {
	grid-column: span 2;
}

#secondary .express-list-widget .post-item.post-list:first-child .post-item-content,
.site-footer .express-list-widget .post-item.post-list:first-child .post-item-content,
.secondary-widgets-area .express-list-widget .post-item.post-list:first-child .post-item-content {
	padding-inline: 0;
	padding-block-end: 0;
}

#secondary .posts-tabs-widget .post-item .post-item-image,
.site-footer .posts-tabs-widget .post-item .post-item-image,
.secondary-widgets-area .posts-tabs-widget .post-item .post-item-image,
.express-list-widget .post-item:not(:first-child) .post-item-image {
	flex: 0 0 25%;
	max-width: 25%;
}

#secondary .posts-tabs-widget .post-item .post-item-content,
.site-footer .posts-tabs-widget .post-item .post-item-content,
.secondary-widgets-area .posts-tabs-widget .post-item .post-item-content,
.express-list-widget .post-item:not(:first-child) .post-item-content {
	padding-block: 0;
	padding-inline-end: 10px;
	padding-inline-start: 10px;
}

#secondary .posts-tabs-widget .post-item .post-item-content .entry-title,
.site-footer .posts-tabs-widget .post-item .post-item-content .entry-title,
.secondary-widgets-area .posts-tabs-widget .post-item .post-item-content .entry-title,
.express-list-widget .post-item:not(:first-child) .post-item-content .entry-title {
	margin-top: 0;
	margin-bottom: 10px;
	font-size: var(--font-size-sm);
}

#secondary .posts-tabs-widget .post-item .post-item-content .entry-meta,
.site-footer .posts-tabs-widget .post-item .post-item-content .entry-meta,
.secondary-widgets-area .posts-tabs-widget .post-item .post-item-content .entry-meta,
.express-list-widget .post-item:not(:first-child) .post-item-content .entry-meta {
	margin: 0;
}

#secondary .posts-tabs-widget .post-item .post-item-content .post-categories,
#secondary .posts-tabs-widget .post-item .post-item-content .post-exerpt,
#secondary .posts-tabs-widget .post-item .post-item-content .post-btn,
.site-footer .posts-tabs-widget .post-item .post-item-content .post-categories,
.site-footer .posts-tabs-widget .post-item .post-item-content .post-exerpt,
.site-footer .posts-tabs-widget .post-item .post-item-content .post-btn,
.secondary-widgets-area .posts-tabs-widget .post-item .post-item-content .post-categories,
.secondary-widgets-area .posts-tabs-widget .post-item .post-item-content .post-exerpt,
.secondary-widgets-area .posts-tabs-widget .post-item .post-item-content .post-btn,
.express-list-widget .post-item:not(:first-child) .post-item-content .post-categories,
.express-list-widget .post-item:not(:first-child) .post-item-content .post-exerpt {
	display: none;
}

.express-list-widget .post-item:not(:first-child) .post-item-content .post-btn {
	display: none;
}

.express-list-widget .post-item.post-list,
.express-list-widget .post-item.post-list:nth-child(even) {
	flex-direction: row;
}

#secondary .express-list-widget .post-item.post-list .post-item-content,
.site-footer .express-list-widget .post-item.post-list .post-item-content,
.secondary-widgets-area .express-list-widget .post-item.post-list .post-item-content,
.primary-widgets-area .express-list-widget .post-item.post-list .post-item-content {
	text-align: start;
	width: 100%;
}


#secondary .express-list-widget .post-item.post-list .post-item-content .post-exerpt:last-child p,
.site-footer .express-list-widget .post-item.post-list .post-item-content .post-exerpt:last-child p,
.secondary-widgets-area .express-list-widget .post-item.post-list .post-item-content .post-exerpt:last-child p,
.primary-widgets-area .express-list-widget .post-item.post-list .post-item-content .post-exerpt:last-child p {
	margin-bottom: 0;
}

#secondary .express-list-widget .post-item.post-list .post-item-content .entry-meta,
.site-footer .express-list-widget .post-item.post-list .post-item-content .entry-meta,
.secondary-widgets-area .express-list-widget .post-item.post-list .post-item-content .entry-meta,
.primary-widgets-area .express-list-widget .post-item.post-list .post-item-content .entry-meta {
	justify-content: flex-start;
}

#secondary .express-list-widget .post-item.post-list .post-item-content .entry-cat .post-categories,
.site-footer .express-list-widget .post-item.post-list .post-item-content .entry-cat .post-categories,
.secondary-widgets-area .express-list-widget .post-item.post-list .post-item-content .entry-cat .post-categories,
.primary-widgets-area .express-list-widget .post-item.post-list .post-item-content .entry-cat .post-categories {
	justify-content: flex-start;
}

#secondary .express-list-widget .express-list-widget-wrapper,
.site-footer .express-list-widget .express-list-widget-wrapper,
.secondary-widgets-area .express-list-widget .express-list-widget-wrapper {
	display: flex;
	flex-direction: column;
	gap: 10px;
}

#secondary .express-list-widget .express-list-widget-wrapper .post-item:first-child,
.site-footer .express-list-widget .express-list-widget-wrapper .post-item:first-child,
.secondary-widgets-area .express-list-widget .express-list-widget-wrapper .post-item:first-child {
	grid-column: span 1;
	flex-direction: column;
}

#secondary .express-list-widget .express-list-widget-wrapper .post-item:first-child .post-item-image a img,
.site-footer .express-list-widget .express-list-widget-wrapper .post-item:first-child .post-item-image a img,
.secondary-widgets-area .express-list-widget .express-list-widget-wrapper .post-item:first-child .post-item-image a img {
	aspect-ratio: 1/0.7;
}

@media (max-width: 600px) {
	.express-list-widget .express-list-widget-wrapper {
		display: flex;
		flex-direction: column;
		gap: 10px;
	}

	.express-list-widget .express-list-widget-wrapper .post-item:first-child {
		grid-column: span 1;
		flex-direction: column;
	}

	.express-list-widget .express-list-widget-wrapper .post-item:first-child .post-item-image a img {
		aspect-ratio: 1/0.7;
	}
}

/* express-list-widget style-2 */
.express-list-widget.style-2 .post-item.overlay-post {
	padding: 0;
}

#secondary .express-list-widget.style-2 .post-item.overlay-post,
.site-footer .express-list-widget.style-2 .post-item.overlay-post,
.secondary-widgets-area .express-list-widget.style-2 .post-item.overlay-post {
	min-height: 280px;
}

.express-list-widget.style-2 .post-item.overlay-post .post-item-image {
	position: absolute;
	width: 100%;
	height: 100%;
}

.express-list-widget.style-2 .post-item.overlay-post .post-item-image::before {
	content: "";
	position: absolute;
	left: 0;
	bottom: 0;
	width: 100%;
	height: 100%;
	background-image: -webkit-gradient(linear, left top, left bottom, from(rgba(17, 17, 17, 0)), color-stop(80%, rgba(17, 17, 17, 0.6)), to(#111111));
	background-image: linear-gradient(to bottom, rgba(17, 17, 17, 0) 0%, rgba(17, 17, 17, 0.6) 80%, #111111 100%);
	background-repeat: no-repeat;
	background-size: cover;
	background-position: center center;
	z-index: 2;
}

.express-list-widget.style-2 .post-item.overlay-post .post-item-content {
	position: relative;
	z-index: 3;
	padding: 20px;
}

.express-list-widget.style-2 .post-item.overlay-post .post-item-content .post-btn a,
.express-list-widget.style-2 .post-item.overlay-post .post-item-content .post-exerpt p {
	color: #fff;
}

#secondary .express-list-widget.style-2 .post-item.overlay-post .post-item-content .post-btn,
.site-footer .express-list-widget.style-2 .post-item.overlay-post .post-item-content .post-btn,
.secondary-widgets-area .express-list-widget.style-2 .post-item.overlay-post .post-item-content .post-btn,
#secondary .express-list-widget.style-2 .post-item.overlay-post .post-item-content .post-exerpt,
.site-footer .express-list-widget.style-2 .post-item.overlay-post .post-item-content .post-exerpt,
.secondary-widgets-area .express-list-widget.style-2 .post-item.overlay-post .post-item-content .post-exerpt {
	display: none;
}

.express-list-widget.style-2 .post-item.overlay-post .post-item-content .post-btn a i::before {
	background-color: #fff;
}

.express-list-widget.style-2 .post-item.overlay-post .post-item-content .post-btn a i::after {
	border: 1px solid #fff;
	border-bottom: 0;
	border-left: 0;
}

/* express-list-widget style-2 */

/* express list widget end */
/* slider widget start */
.slider-widget .slider-wrapper .post-item {
	height: 600px;
}

@media (max-width: 600px) {
	.slider-widget .slider-wrapper .post-item {
		height: 400px;
	}
}

.slider-widget .slider-wrapper .post-item .post-overlay-wrapper {
	position: absolute;
	bottom: 0px;
	padding: 50px;
	z-index: 2;
	left: 0;
}

@media (max-width: 768px) {
	.slider-widget .slider-wrapper .post-item .post-overlay-wrapper {
		padding: 20px;
	}
}

.slider-widget .slider-wrapper .post-item .entry-title {
	font-size: var(--font-size-lg);
}

#secondary .slider-widget .slider-wrapper .post-item,
.site-footer .slider-widget .slider-wrapper .post-item,
.secondary-widgets-area .slider-widget .slider-wrapper .post-item {
	height: 400px;
}

#secondary .slider-widget .slider-wrapper .post-item .post-overlay-wrapper,
.site-footer .slider-widget .slider-wrapper .post-item .post-overlay-wrapper,
.secondary-widgets-area .slider-widget .slider-wrapper .post-item .post-overlay-wrapper {
	padding: 20px;
}

#secondary .slider-widget .slider-wrapper .post-item .entry-title,
.site-footer .slider-widget .slider-wrapper .post-item .entry-title,
.secondary-widgets-area .slider-widget .slider-wrapper .post-item .entry-title {
	font-size: var(--font-size-base);
}

/* slider widget end */
/* post carousel widget start */

.posts-carousel-widget .carousel-wrapper {
	overflow: hidden;
}

.posts-carousel-widget .carousel-wrapper .slick-list {
	margin: 0 -10px;
}

.posts-carousel-widget .carousel-wrapper .slick-list .slick-track .slick-slide {
	padding: 0 10px;
}

/* post carousel widget end */
/* post tab widget start */

.posts-tabs-widget .post-tabs-wrapper .post-tabs-head {
	position: relative;
	margin-bottom: 20px;
}

.posts-tabs-widget .post-tabs-wrapper .post-tabs-head::before {
	position: absolute;
	content: '';
	height: 1px;
	width: 100%;
	background-color: #999;
	opacity: 0.5;
	left: 0;
	bottom: 0;
}

.dark-mode .posts-tabs-widget .post-tabs-wrapper .post-tabs-head::before {
	background-color: #fff;
}

.site-footer .posts-tabs-widget .post-tabs-wrapper .post-tabs-head::before {
	background-color: #fff;
}

.posts-tabs-widget .post-tabs-wrapper .post-tabs-head .post-tabs {
	list-style: none;
	margin: 0;
	padding: 0;
	border: none;
	display: flex;
	position: relative;
}

.posts-tabs-widget .post-tabs-wrapper .post-tabs-head .post-tabs li {
	outline: none;
	flex: 1;
}

.posts-tabs-widget .post-tabs-wrapper .post-tabs-head .post-tabs li a {
	font-size: var(--font-size-sm);
	font-weight: bold;
	color: #fff;
	background-color: var(--primary-color);
	padding: 8px 12px;
	text-decoration: none;
	outline: none;
	display: flex;
	align-items: center;
	gap: 10px;
}

.posts-tabs-widget .post-tabs-wrapper .post-tabs-head .post-tabs li a.inactive {
	color: var(--color-text);
	background-color: transparent;
}

.posts-tabs-widget .post-tabs-wrapper .post-tabs-head .post-tabs li a:not(.inactive):focus,
.posts-tabs-widget .post-tabs-wrapper .post-tabs-head .post-tabs li a:not(.inactive):hover {
	color: #fff;
	background-color: var(--primary-color);
}

.posts-tabs-widget .post-tabs-wrapper .post-tabs-head .post-tabs li a:hover,
.posts-tabs-widget .post-tabs-wrapper .post-tabs-head .post-tabs li a.inactive:hover {
	color: var(--primary-color);
	outline: none;
}

#secondary .posts-tabs-widget .post-tabs-wrapper .post-tab-content-wrapper .post-tab-container .post-item,
.site-footer .posts-tabs-widget .post-tabs-wrapper .post-tab-content-wrapper .post-tab-container .post-item,
.secondary-widgets-area .posts-tabs-widget .post-tabs-wrapper .post-tab-content-wrapper .post-tab-container .post-item {
	margin-bottom: 10px;
}

@media (max-width: 600px) {

	.posts-tabs-widget .post-item .post-item-image {
		flex: 0 0 25%;
		max-width: 25%;
	}

	.posts-tabs-widget .post-item .post-item-content {
		padding-block: 0;
		padding-inline-end: 0;
		padding-inline-start: 10px;
	}

	.posts-tabs-widget .post-tabs-wrapper .post-tab-content-wrapper .post-tab-container .post-item .post-categories,
	.posts-tabs-widget .post-tabs-wrapper .post-tab-content-wrapper .post-tab-container .post-item .post-exerpt,
	.posts-tabs-widget .post-tabs-wrapper .post-tab-content-wrapper .post-tab-container .post-item .post-btn {
		display: none;
	}
}


/* post tab widget end */

/* category tab widget start */
.tab-filter-widget .tab-filter-widget-tabs {}

.tab-filter-widget .widget-header {
	position: relative;
}

.tab-filter-widget .widget-header.no-title {
	min-height: 33px;
	padding-block-end: 10px;
	margin-bottom: 15px;
	border-bottom: 1px solid rgba(var(--color-text-rgb), 0.15);
}

.tab-filter-widget ul.tabs-nav-filter {
	list-style: none;
	margin: 0;
	display: flex;
	flex-wrap: wrap;
	gap: 5px;
	background-color: var(--color-background);
}

.tab-filter-widget .widget-header ul.tabs-nav-filter {
	position: absolute;
	right: 0;
	top: 0;
}

.tab-filter-widget .widget-header.no-title ul.tabs-nav-filter {
	right: unset;
	left: 0;
}

#secondary .tab-filter-widget .widget-header ul.tabs-nav-filter,
.site-footer .tab-filter-widget .widget-header ul.tabs-nav-filter,
.secondary-widgets-area .tab-filter-widget .widget-header ul.tabs-nav-filter {
	position: unset;
	margin-bottom: 10px;
	margin-inline-start: -7px;
}

.tab-filter-widget ul.tabs-nav-filter a {
	padding: 10px 7px;
	font-weight: bold;
	font-size: var(--font-size-sm);
}

.tab-filter-widget ul.tabs-nav-filter a.inactive {
	color: var(--color-text);
}

.tab-filter-widget ul.tabs-nav-filter a.inactive:focus,
.tab-filter-widget ul.tabs-nav-filter a.inactive:hover,
.tab-filter-widget ul.tabs-nav-filter li a:not(.inactive) {
	color: var(--primary-color);
}

.tab-filter-widget .express-list-widget-wrapper {
	display: grid;
	grid-gap: 20px;
	grid-template-columns: repeat(4, 1fr);
}

.tab-filter-widget .express-list-widget-wrapper .post-item:first-child {
	grid-row: span 3;
	grid-column: span 2;
}

.tab-filter-widget .express-list-widget-wrapper .post-item.overlay-post {
	padding: 0;
}

#secondary .tab-filter-widget .express-list-widget-wrapper .post-item.overlay-post,
.site-footer .tab-filter-widget .express-list-widget-wrapper .post-item.overlay-post,
.secondary-widgets-area .tab-filter-widget .express-list-widget-wrapper .post-item.overlay-post {
	min-height: 280px;
}

.tab-filter-widget .express-list-widget-wrapper .post-item.overlay-post .post-item-image {
	position: absolute;
	width: 100%;
	height: 100%;
}

.tab-filter-widget .express-list-widget-wrapper .post-item.overlay-post .post-item-image::before {
	content: "";
	position: absolute;
	left: 0;
	bottom: 0;
	width: 100%;
	height: 100%;
	background-image: -webkit-gradient(linear, left top, left bottom, from(rgba(17, 17, 17, 0)), color-stop(80%, rgba(17, 17, 17, 0.6)), to(#111111));
	background-image: linear-gradient(to bottom, rgba(17, 17, 17, 0) 0%, rgba(17, 17, 17, 0.6) 80%, #111111 100%);
	background-repeat: no-repeat;
	background-size: cover;
	background-position: center center;
	z-index: 2;
}

.tab-filter-widget .express-list-widget-wrapper .post-item.overlay-post .post-item-content {
	position: relative;
	z-index: 3;
	padding: 20px;
}

.tab-filter-widget .express-list-widget-wrapper .post-item.post-list {
	grid-column: span 2;
}

.tab-filter-widget .express-list-widget-wrapper .post-item.post-list,
.tab-filter-widget .express-list-widget-wrapper .post-item.post-list:nth-child(even) {
	flex-direction: row;
}

#secondary .tab-filter-widget .express-list-widget-wrapper .post-item.post-list .post-item-image,
.site-footer .tab-filter-widget .express-list-widget-wrapper .post-item.post-list .post-item-image,
.secondary-widgets-area .tab-filter-widget .express-list-widget-wrapper .post-item.post-list .post-item-image,
.tab-filter-widget .express-list-widget-wrapper .post-item.post-list .post-item-image {
	flex: 0 0 25%;
	max-width: 25%;
	height: 100%;
}

#secondary .tab-filter-widget .express-list-widget-wrapper .post-item.post-list .post-item-content,
.site-footer .tab-filter-widget .express-list-widget-wrapper .post-item.post-list .post-item-content,
.secondary-widgets-area .tab-filter-widget .express-list-widget-wrapper .post-item.post-list .post-item-content,
.primary-widgets-area .tab-filter-widget .express-list-widget-wrapper .post-item.post-list .post-item-content {
	text-align: start;
	width: 100%;
	padding-block: 0;
	padding-inline-end: 10px;
	padding-inline-start: 10px;
}

#secondary .tab-filter-widget .express-list-widget-wrapper .post-item.post-list .post-item-content .entry-title,
.site-footer .tab-filter-widget .express-list-widget-wrapper .post-item.post-list .post-item-content .entry-title,
.secondary-widgets-area .tab-filter-widget .express-list-widget-wrapper .post-item.post-list .post-item-content .entry-title,
.tab-filter-widget .express-list-widget-wrapper .post-item.post-list .post-item-content .entry-title {
	margin-top: 0;
	margin-bottom: 10px;
	font-size: var(--font-size-sm);
}

#secondary .tab-filter-widget .express-list-widget-wrapper .post-item.post-list .post-item-content .entry-meta,
.site-footer .tab-filter-widget .express-list-widget-wrapper .post-item.post-list .post-item-content .entry-meta,
.secondary-widgets-area .tab-filter-widget .express-list-widget-wrapper .post-item.post-list .post-item-content .entry-meta,
.primary-widgets-area .tab-filter-widget .express-list-widget-wrapper .post-item.post-list .post-item-content .entry-meta {
	justify-content: flex-start;
}

#secondary .tab-filter-widget .express-list-widget-wrapper,
.site-footer .tab-filter-widget .express-list-widget-wrapper,
.secondary-widgets-area .tab-filter-widget .express-list-widget-wrapper {
	grid-template-columns: repeat(2, 1fr);
}

@media (max-width: 600px) {
	.tab-filter-widget .express-list-widget-wrapper {
		grid-template-columns: repeat(2, 1fr);
	}

	.tab-filter-widget .widget-header.no-title {
		min-height: 0;
		padding-block-end: 0;
	}

	.tab-filter-widget .widget-header ul.tabs-nav-filter {
		position: unset;
		margin-bottom: 10px;
		margin-inline-start: -7px;
	}
}

/* category tab widget end */
/* Custom widgets end
--------------------------------------------- */

/* Start footer css
--------------------------------------------- */
.site-footer {
	margin-top: 50px;
	background-color: #1c1c1c;
}

.dark-mode .site-footer {
	background-color: #101010;
}

.newsletter-section+.site-footer {
	margin-top: 0;
}

.site-footer .top-footer {
	padding-top: 50px;
}

.site-footer .top-footer .top-footer-widgets {
	display: flex;
	flex-wrap: wrap;
	margin-inline: -15px;
}

.site-footer .top-footer .top-footer-widgets .footer-widget {
	width: 25%;
	padding-inline: 15px;
	flex-shrink: 0;
	color: #fff;
}

@media (max-width: 768px) {
	.site-footer .top-footer .top-footer-widgets .footer-widget {
		width: 50%;
	}
}

@media (max-width: 480px) {
	.site-footer .top-footer .top-footer-widgets .footer-widget {
		width: 100%;
	}
}

.site-footer .top-footer .top-footer-widgets .footer-widget h1,
.site-footer .top-footer .top-footer-widgets .footer-widget h2,
.site-footer .top-footer .top-footer-widgets .footer-widget h3,
.site-footer .top-footer .top-footer-widgets .footer-widget h4,
.site-footer .top-footer .top-footer-widgets .footer-widget h5,
.site-footer .top-footer .top-footer-widgets .footer-widget h6 {
	margin-top: 0;
}

.site-footer .top-footer .top-footer-widgets .footer-widget a {
	color: #fff;
	opacity: 0.8;
	transition: all 0.3s ease;
}

.site-footer .post-item .post-item-content .entry-meta li span.line {
	background-color: #fff;
}

.site-footer .top-footer .top-footer-widgets .footer-widget a:focus,
.site-footer .top-footer .top-footer-widgets .footer-widget a:hover {
	color: #fff;
	opacity: 1;
}

.site-footer .top-footer .top-footer-widgets .footer-widget .post-item.post-list .mag-post-img>a {
	opacity: 1;
}

.site-footer .top-footer .top-footer-widgets .footer-widget .widget .widget-title {
	color: #fff;
}

.site-footer .top-footer .top-footer-widgets .footer-widget .widget ul li a,
.site-footer .top-footer .top-footer-widgets .footer-widget .widget ol li a {
	color: #fff;
	opacity: 0.8;
	transition: all 0.3s ease;
}

.site-footer .top-footer .top-footer-widgets .footer-widget .widget ul li a:focus,
.site-footer .top-footer .top-footer-widgets .footer-widget .widget ol li a:focus,
.site-footer .top-footer .top-footer-widgets .footer-widget .widget ul li a:hover,
.site-footer .top-footer .top-footer-widgets .footer-widget .widget ol li a:hover {
	opacity: 1;
}

.site-footer .top-footer .top-footer-widgets .footer-widget .mag-post-excerpt {
	color: #fff;
}

.site-footer .bottom-footer {
	position: relative;
	padding: 15px 0;
	z-index: 1;
}

.site-footer .bottom-footer .bottom-footer-info {
	display: flex;
	flex-wrap: wrap;
	align-items: center;
	justify-content: center;
	color: #fff;
	position: relative;
}

.site-footer .bottom-footer .bottom-footer-info .site-info a {
	text-decoration: none;
	color: #fff;
	opacity: 0.8;
	transition: all 0.3s ease;
}

.site-footer .bottom-footer .bottom-footer-info .site-info a:focus,
.site-footer .bottom-footer .bottom-footer-info .site-info a:hover {
	opacity: 1;
}

.site-footer .bottom-footer .bottom-footer-info .social-icons ul.social-links {
	margin: 0;
	padding: 0;
	list-style: none;
}

.site-footer .bottom-footer::before {
	position: absolute;
	content: '';
	top: 0;
	left: 0;
	height: 100%;
	width: 100%;
	background-color: #d9d9d9;
	opacity: 0.1;
}

.dark-mode .site-footer .bottom-footer::before {
	background-color: #000;
	opacity: 0.5;
}

@media (min-width: 1200px) {
	.footer-sticky .site-footer {
		position: sticky;
		bottom: 0;
		top: 0;
		z-index: 0;
	}
}


/* End footer css
--------------------------------------------- */
/* Start Scroll to top css
--------------------------------------------- */
a.news-hub-scroll-to-top {
	position: fixed;
	bottom: 53px;
	right: 30px;
	height: 40px;
	width: 40px;
	opacity: 0;
	visibility: hidden;
	z-index: 17;
	display: flex;
	align-items: center;
	justify-content: center;
	text-decoration: none;
	color: #fff;
	background-color: var(--primary-color);
	border: 1px solid #fff;
	transition: all 1s cubic-bezier(0.25, 0.8, 0.25, 1);
	font-size: var(--font-size-sm);
}

a.news-hub-scroll-to-top:hover,
a.news-hub-scroll-to-top:focus {
	box-shadow: 0 0.2rem 1rem rgba(0, 0, 0, 0.15);
	transform: translateY(-10px);
}

a.news-hub-scroll-to-top.show {
	opacity: 1;
	visibility: visible;
}

/* End Scroll to top css
--------------------------------------------- */
