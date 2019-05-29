# osgridfolio

A dead simple grid portfolio to display your GitHub projects. 

See an example at <https://colinfay.me/open-source/>

To add this grid porfolio, add a div with an id that will receive the portfolio, then call `add_repos(repos, "ID")` to fill it.

You'll need to add the `osgridfolio.css` and `osgridfolio.js` files to your page. 

```
git clone https://github.com/ColinFay/osgridfolio.git
```


```
<head>
  <meta charset="utf-8">
  <title></title>
  <meta name="author" content="">
  <meta name="description" content="">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" type="text/css" href="osgridfolio.css">
</head>

<body>

  <p>Hello, world!</p>
  
  <div id = "colinthings"></div>

  <script src="osgridfolio.js"></script>
  <script>
    var repos = ["ColinFay/attempt", 
    "ColinFay/r-ci", 
    "ColinFay/r-online", 
    "ColinFay/backyard", 
    "ColinFay/dockerfiler", 
    "ColinFay/nessy", 
    "ColinFay/craneur", 
    "ColinFay/wtfismyip"]
    
    add_repos(repos, "colinthings")
  </script>
</body>

</html>
```

## Contribute

Feel free to open a PR. 

The supported language list (i.e. the one getting a font-awesome icon) is non-exhaustive and were manually computed, so please do open a PR to add a language.

## Under MIT Licence