# \<my-project\>



## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.

```
Custom CSS Properties

https://www.smashingmagazine.com/2017/04/start-using-css-custom-properties/

https://www.sitepoint.com/practical-guide-css-variables-custom-properties/
```
```
https://www.webcomponents.org/element/PolymerElements/paper-card
```


```
What is CSS preprocessors?
- LESS and SASS are the CSS prepocessors
- They make use of variables and mixins to define style
- Avoid copy pasting of css code
- They store color, font preferences and layout related properties
```

```
Limitations of Preprocessors
- Cannot be change dynamically
- They not aware of DOM structure
- They cannot be changed from javascript
- LESS uses @ and SASS uses $ as prefixes
- They have their code language which has to be learned before implemented
- Different declaration method
```

```
These limiations make a base to invent CSS Custom Properties by a community
```

```
CSS Custom Properties uses simple -- (two hypens)
- learn once and implement through all browsers
- CSS variables is written as var()

.box {
    --box-color: #ff5678;
    --box-padding: 10px;
}

- CSS mixin
--my-box: {
    --box-color: #ff5678;
    --box-padding: 10px;
}

- apply mixin
.your-box {
    @apply --my-box;
}
```

```
Browser Support
- All modern browsers support
- But IE Edge fully support, older version does not have full support 
```

```
```




