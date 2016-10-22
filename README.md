# SASS and CSS for Arrrows

A simple sass and css library for the arrrows fonts, http://www.arrrows.com/

## Usage
Decorate your classes
```
<div class="arrrow thin-gt-arrow-right"></div>
<div class="arrrow-bold thin-gt-arrow-left"></div>
```

## Implement with sass
 - **Download** the font bundle from http://www.arrrows.com/
 - Get the **scss files** from this library, https://github.com/EricHerlitz/arrrows-sass-and-css/archive/master.zip
 - Setup the **$local-font-path** parameter in the **arrrows.scss** file
 - **Configuration** in the bottom of **arrrows.scss**

### Render css for all possible arrrows
```
// get all arrows
@include get-arrrows();
```

```
// get all bold arrows
@include get-arrrows(true);
```

### Render css for specific arrrows
```
// get the normal thin-gt-arrow-right
@include get-arrow(thin-gt-arrow-right);
```
```
// get the bold thin-gt-arrow-right
@include get-arrow(thin-gt-arrow-right, true);
```

## Implement with css
 - **Download** the font bundle from http://www.arrrows.com/
 - Get the **css file** from this library, https://github.com/EricHerlitz/arrrows-sass-and-css/blob/master/arrrows.css
 - Setup the **path** parameter *(/Webfonts/ in the committed file)* in the **arrrows.scss** file
