## &lt;chuck-norris-joke&gt;
> http://www.icndb.com/

Put some Chuck Norris in your page!

```js
bower install chuck-norris-joke --save
```

```html
<head>
  <link rel="import" href="bower_components/chuck-norris-joke/chuck-norris-joke.html">
</head>
<body>
  <chuck-norris-joke></chuck-norris-joke>
</body>
```

#### Choose a joke by it's ID
```html
<chuck-norris-joke joke-id="80"></chuck-norris-joke>
```

#### Change Chuck's name
```html
<chuck-norris-joke firstName="Tim" lastName="Berners-Lee"></chuck-norris-joke>
```

#### Limit to 1 or more categories
```html
<chuck-norris-joke categories="nerdy,explicit"></chuck-norris-joke>
```
