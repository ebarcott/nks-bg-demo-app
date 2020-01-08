# NKS BG Demo App

You can use this app to test the NKS app managment feature. Clone or download this app into your own GitHub repo, so that you can customize and update it for demonstration purposes.

To demonstrate the `git push` workflow, update the background color of the index page as explained below. Then push the changes to your repo.

## Update the Background Color

Edit `views/pages/index.ejs` and find the section which reads:

```
<!--
  For customizing the "body" bg class.
  Preview colors at https://tailwindcss.com/docs/background-color/

  allowed color values:
    red, orange, yellow,
    green, teal, blue,
    pink
  allowed saturation values:
  100 to 700
-->

<body class="bg-pink-600">
```

Change the body class color, e.g.:

```
<body class="bg-teal-600">
```

Save and exit the file.


