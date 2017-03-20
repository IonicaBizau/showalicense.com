
[![showalicense.com](http://i.imgur.com/DEYIE8P.png)](http://showalicense.com/)

# showalicense.com

 [![Support me on Patreon][badge_patreon]][patreon] [![Buy me a book][badge_amazon]][amazon] [![PayPal][badge_paypal_donate]][paypal-donations] [![Version](https://img.shields.io/npm/v/showalicense.com.svg)](https://www.npmjs.com/package/showalicense.com) [![Downloads](https://img.shields.io/npm/dt/showalicense.com.svg)](https://www.npmjs.com/package/showalicense.com)

> A site to provide an easy way to show licenses and their human-readable explanations.

## Your help is needed! :heart:

Contribute by explaining licenses. Check out [this issue](https://github.com/IonicaBizau/showalicense.com/issues/1). :memo: :book:

## Usage

Whether you just want to show a license or see its human-readable explanation, you can use this website. It provides a nice querystring API documented below:


 - `#license-<license>` (hash): set the license to display
 - `fullname=<name>`: set the copyright holder name
 - `year=<name>`: set the starting copyright yea
 - `hide_explanations=<true|false>` (default: `false`): hide the explanations column

[![showalicense.com](http://i.imgur.com/AB42LJo.png)](http://showalicense.com/)

## Examples

 - To see the MIT license access this url: http://showalicense.com/#license-mit
 - To set the copyright holder name, use the `fullname=<name>` querystring parameter: http://showalicense.com/?fullname=Alice#license-mit
 - To set the starting copyright year use the `year` parameter: http://showalicense.com/?year=2013&fullname=Alice#license-mit
 - To hide the explanations column, you have to use `hide_explanations=true`: http://showalicense.com/?hide_explanations=true&year=2013&fullname=Alice#license-mit

## :yum: How to contribute
Have an idea? Found a bug? See [how to contribute][contributing].


## :sparkling_heart: Support my projects

I open-source almost everything I can, and I try to reply everyone needing help using these projects. Obviously,
this takes time. You can integrate and use these projects in your applications *for free*! You can even change the source code and redistribute (even resell it).

However, if you get some profit from this or just want to encourage me to continue creating stuff, there are few ways you can do it:

 - Starring and sharing the projects you like :rocket:
 - [![PayPal][badge_paypal]][paypal-donations]—You can make one-time donations via PayPal. I'll probably buy a ~~coffee~~ tea. :tea:
 - [![Support me on Patreon][badge_patreon]][patreon]—Set up a recurring monthly donation and you will get interesting news about what I'm doing (things that I don't share with everyone).
 - **Bitcoin**—You can send me bitcoins at this address (or scanning the code below): `1P9BRsmazNQcuyTxEqveUsnf5CERdq35V6`

    ![](https://i.imgur.com/z6OQI95.png)

Thanks! :heart:


### Explaining a license

Explanations are kept in `txt` files in the [`explanations`](/explanations) directory, having the license names (e.g. `mit.txt`).


Contributions in this directions are really appreciated.


 1. Fork this repository.
 2. Edit the `explanations/<license>.txt` file (you can follow [`explanations/mit.txt`](/explanations/mit.txt) as example).
 3. Add yourself as contributor in [`package.json`](/package.json).
 4. Raise a pull request! :tada:
### Adding a new license

If the license you're searching for is missing, make sure you add it.


 1. Fork this repository.
 2. Add a new file in the [`licenses`](/licenses) directory, named `<license>.txt` (replace `<license>` with the license name) and then do the same in the [`explanations`](/explanations) directory (you can follow the MIT license example: see [`explanations/mit.txt`](/explanations/mit.txt) and [`licenses/mit.txt`](/licenses/mit.txt)).
 3. Give nice, funny and useful explanation in the `explanations/<license>.txt` file you added.
 4. Add yourself as contributor in [`package.json`](/package.json).
 5. Raise a pull request! :tada:

## :cake: Thanks

 - [github/choosealicense.com](https://github.com/github/choosealicense.com)–a good inspiration source (some ideas and CSS were taken from here) :sparkle:
 - [**@Cerberus-tm**](https://github.com/Cerberus-tm)–who had the idea for the site name :cake:


## :scroll: License

[MIT][license] © [Ionică Bizău][website]

[badge_patreon]: http://ionicabizau.github.io/badges/patreon.svg
[badge_amazon]: http://ionicabizau.github.io/badges/amazon.svg
[badge_paypal]: http://ionicabizau.github.io/badges/paypal.svg
[badge_paypal_donate]: http://ionicabizau.github.io/badges/paypal_donate.svg
[patreon]: https://www.patreon.com/ionicabizau
[amazon]: http://amzn.eu/hRo9sIZ
[paypal-donations]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=RVXDDLKKLQRJW
[donate-now]: http://i.imgur.com/6cMbHOC.png

[license]: http://showalicense.com/?fullname=Ionic%C4%83%20Biz%C4%83u%20%3Cbizauionica%40gmail.com%3E%20(https%3A%2F%2Fionicabizau.net)&year=2015#license-mit
[website]: https://ionicabizau.net
[contributing]: /CONTRIBUTING.md
[docs]: /DOCUMENTATION.md
