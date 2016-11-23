Oc-old-menu-stylish
===================

Stylish style to bring back old menu in ownCloud

## Requirements

* ownCloud 7+ (before, it's... useless)
* Stylish (for [Firefox](https://addons.mozilla.org/en-US/firefox/addon/stylish/))

## Behavior

When screen width is larger than 1100px, menu is placed to the left (like old oc menu). Below 1100px, menu bring back
to the top.

## How to use

* install it [via UserStyles.ORG](https://userstyles.org/styles/131444/oc-old-menu-stylish) or
* install it manually:
 * create new style with stylish
 * copy / paste code
 * save
* if it doesn't work out-of-the-box (rare cases, e.g. if your installation doesn't reside in the server's `DOCUMENT_ROOT` as `/owncloud`):
  * uncomment the `@-moz-document url-prefix("YOUR OC URL"){` line
  * replace [your oc url] by... your oc url :)
  * comment-out the `@-moz-document regexp("https?://[^/]+(:[0-9]+)?/owncloud/.*") {` line
  * save and check again

## Screenshots

Before :

[![new menu](https://i.imgur.com/3qOGHN9m.png)](https://i.imgur.com/3qOGHN9.png)

After :

[![old menu](https://i.imgur.com/9GLgOtrm.png)](https://i.imgur.com/9GLgOtr.png)

## Notes:
This UserStyle was optimized for owncloud 8.2+ and nextcloud 9+. In case you run
an owncloud version older than 8.2 for some reason, please use the [stylesheet
version from 8/2016](https://github.com/IzzySoft/Oc-old-menu-stylish/blob/025dd055f3c13b2b6493912986a153c00051bb6d/oc-old-menu-stylish.css).