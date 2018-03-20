# cookiebar 🍪

A really simple cookiebar plugin. The plugin detects the browser language via navigator.language.


## Install

You can put the script tag into the body, or import it via CommonJS or AMD.

## Usage

``` javascript

  cookiebar.init();

```

## Language Support

Currently support languages. 

- englisch
- germany
- polish

If you want to help then fork this repo and add your language to
the langData array in cookiebar-src.js like this.

``` javascript
{
  name: 'english',
  lang: ['en', 'en-US', 'en-EG', 'en-AU', 'en-GB', 'en-CA', 'en-NZ', 'en-IE', 'en-ZA', 'en-JM', 'en-BZ', 'en-TT'],
  template: '<p>This Site uses Cookies.</p><button data-cookiebar-close>Accept!</button>'
}
```

## mount

By default the cookiebar appends to the document.body

With

``` javascript
Cookiebar.mount = document.querySelector('.renderCookiebarHere')
```

you can append the cookiebar where you want to.

## Thanks to

- karolsw2

for the constribution
