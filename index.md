## James' first experiment with making GitHub Pages

You can use the [editor on GitHub](https://github.com/jameswaters/Project-001/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Why would we want to use this?
 - Share experiment results
 - Organize materials for a workshop
 - Sharing R code


```markdown
Example R code
This is the first few lines of our mavenR script

# Load the packages`
library(tidyverse)
library(mavenR)

# Set directory
data.location <- "~/Desktop/R/brachy-sicb-2022/20-July"
data.file <- "20July_Maven_a.csv"
data.label <- "Brachyponera chinensis (20-July-2021)"

setwd(data.location)
```

### Things that would be nice to learn how to do 

 - Can we add photos/images?
 - Can we publish R Markdown code? (R scripts with graphs embedded)
 - Can we link to files in our github directory?

### Attempt to attach a file!
Trying to show an image of our poster from SICB. If this works, it's because I dragged this `.png` from the desktop of my computer into the editing window. 

[FlyPoster-SICB-2022_sm](https://user-images.githubusercontent.com/6729255/150399734-16f911d8-6bd6-4460-baa7-8a0cb54baae3.png)

Okay turns out that didn't really work. It added a link so you can click on it to see the poster. But can we embed it on the page? 

Trying using the same code as above but with an exclamation point `!` first ...
![FlyPoster-SICB-2022_sm](https://user-images.githubusercontent.com/6729255/150399734-16f911d8-6bd6-4460-baa7-8a0cb54baae3.png)

That worked!?


