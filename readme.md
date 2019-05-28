#Fuse-FontAwesome-Icon

Simple component to display an FontAwesome Icon on **Fuse Open**

##Usage

```xml
    <FAIcon Size="48" Margin="7" Icon="adn" FontColor="#000" />
```

With this component you will be able to set icon from observables


```xml
    <JavaScript>
        var Observable = require("FuseJS/Observable");
        var icon = Observable('euro');
        module.exports = {
            icon: icon
        }
    </JavaScript>

    <FAIcon Size="64" Margin="7" Icon="{icon}" FontColor="#000" />
```


