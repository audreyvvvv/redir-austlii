# redir-austlii
09/05/17

## to install
1. create a new bookmark (on any page) with an applicable name (e.g. redir_austlii).
2. right click to 'edit' the new bookmark.
3. paste contents of 01_bookmarklet/below into the URL field.

```
javascript:(function()%7B%7Bif(window.location.href.indexOf('cgi-bin%2Fsinodisp%2F') > -1) %7Bwindow.location %3D 
window.location.href.replace('cgi-bin%2Fsinodisp%2F'%2C '')%3B%7Delse%7B(window.location.search %2B%3D 
'%3Fstem%3D0')%3B%7D%7D%7D)()
```

## to use 
1. load a broken austlii page.
2. click bookmark.
3. (hopefully get to a working page.)
