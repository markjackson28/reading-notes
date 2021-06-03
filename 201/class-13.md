
# Class 13

[Home](https://markjackson28.github.io/reading-notes/)

## Summary/Notes of readings

[The Past, Present, and Future of Local Storage for Web Applications](http://diveinto.html5doctor.com/storage.html)

- Local storage allows you to save key/value pairs in a web browser.
- Local storage and cookies are similar.

*Downsides of cookies:*

- “Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over”.
- “Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)”.
- “Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful”.

- Almost every browser supports HTML5 Storage.
- Two ways to check HTML5 storage compatibility:

(As a function)

```
function supports_html5_storage() {
  try {
    return 'localStorage' in window && window['localStorage'] !== null;
  } catch (e) {
    return false;
  }
}
```
(Or the Modernizr method)
```
if (Modernizr.localstorage) {
  // window.localStorage is available!
} else {
  // no native support for HTML5 storage :(
  // maybe try dojox.storage or a third-party solution
}
```
