Material-Design-Colors-For-Beginners
====================================
Initial Code taken from Materialize https://github.com/Dogfalo/materialize

A simple CSS for easy use of Material Design colors **no matter what framework you are using**, Bootstrap, Foundation etc.
#New feature v1.0.0
Text with Alpha Values as suggested by the Google Material Design Specifications

##White text
>blue has just been used as the background for contrast, You can use the text on any background
```html
        <div class="blue whitetext-main">
        <p style="font-size:50px">whitetext-main</p>
        </div>
        
        <div class="blue whitetext-secondary">
            <p style="font-size:50px">whitetext-secondary</p>
        </div>
        
        <div class="blue whitetext-disabled">
            <p style="font-size:50px">whitetext-disabled</p>
        </div>
        
        <div class="blue whitetext-divider">
            <p style="font-size:50px">whitetext-divider</p>
        </div>
```
##Black text
```html
        <div class="blue blacktext-main">
            <p style="font-size:50px">using whitetext-main</p>
        </div>
        
        <div class="blue blacktext-secondary">
            <p style="font-size:50px">whitetext-secondary</p>
        </div>
        
        <div class="blue blacktext-disabled">
            <p style="font-size:50px">whitetext-disabled</p>
        </div>
        
        <div class="blue blacktext-divider">
            <p style="font-size:50px">whitetext-divider</p>
        </div>
```



#full list of colors and classes from materialize

http://materializecss.com/sass.html  go to colors section

##To apply a background color, just add the color name and light/darkness as a class to the element.
```html
<div class="teal lighten-2">This is a card panel with a teal lighten-2 class</div>
```

##To apply a text color, just append -text to the color  and lighten/darken class like this:

```html
<div>
  <span class="blue-text text-darken-2">This is a card panel with dark blue text</span>
</div>
```


