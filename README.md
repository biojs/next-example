# Next components

<img src="http://i.imgur.com/I9HurIz.png"></img>

Type following:

```bash
mkdir next && cd next
bower i --save daviddao/x-bio-pv
bower i --save webcomponents/webcomponents-lite #polyfill for all browsers
```

Create a minimal index.html inside the folder:

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>BioJS Next Example</title>
    <script src="bower_components/webcomponents-lite/webcomponents-lite.js"></script>
    <link rel="import" href="bower_components/x-bio-pv/x-bio-pv.html">
</head>

<body>
    <x-bio-pv></x-bio-pv>
</body>

</html>

```
You are done.
A slightly more advanced Data Binding Example: http://biojs.github.io/next-example/
