

We use Wowchemy template (https://github.com/wowchemy/starter-academic) for our website.

Look at the document at (https://wowchemy.com/docs/)


### Updating Theme

To update the theme, type

```bash
$> sh update_wowchemy.sh
```

### Updating Publication

To add publication, make a new folder under `labpage/content/en/publication` and put a markdown document `index.md`.


### Upload the Webpage

first render the HTML files under `labpage/docs`

```bash
$> hugo 
```


The Japanese page is broken since the link to the css is not correct. This is due to the bug of the Wowchemy framework.

modify the link of the css as

```html
  <link rel="stylesheet" href="https://cgenglab.github.io/labpage/css/wowchemy.cdffdbf2ee9d5c1efbe52ccc952d7dbf.css" />
```

Upload the webpage by pushing to the github remote repository
```bash
$> git add .
$> git commit -m "explain about the update here"
$> git push
```

