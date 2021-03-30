

We use Wowchemy template (https://github.com/wowchemy/starter-academic) for our website.

Look at the document at (https://wowchemy.com/docs/)



## Quick Preview

```bash
$ sh view.sh
```

Then, look at http://localhost:1313/labpage/en/



## Updating Theme

To update the theme, type

```bash
$ sh update_wowchemy.sh
```



## Updating Publication

To add publication, make a new folder under `labpage/content/en/publication` and put a markdown document `index.md`.





## Updating Members

To add members, make new folders under `labpage/content/en/authors` and `labpage/content/jp/authors`and put markdown a document `_index.md` in each folder. 






## Upload the Webpage

first render the HTML files under `labpage/docs`

```bash
$ hugo 
```

The Japanese page is broken because the link to the css is not correct. This is due to the bug of the Wowchemy framework. Copy `wowchemy.cdffdbf2ee9d5c1efbe52ccc952d7dbf.css` under `\docs\labpage\labpage\` to get around this issue.  
A more accurate solution is to match the files in `docs\labpage\css` with the files in `docs\css`.  



Upload the webpage by pushing to the github remote repository

```bash
$ git add .
$ git commit -m "explain about the update here"
$ git push
```





## Notes	 

- Please don't put a large file in the repository (e.g., PDF and video of the paper). It will significantly slow the git down. Also GitHub doesn't allow large files in the repository (Don't use "Git Large File"). 