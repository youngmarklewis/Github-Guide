# Using GitHub pages

1. Create a new repository and name it. Add a description, make it public and initialize with a readme.
1. Once created select the master branch and change this by typing `'gh-pages'`
1. Branch is now `'gh-pages'` rather than master but to make this permanent select `'settings > branches'`. Change the default branch to `'gh-pages'`
1. Now click on `'branches'` in the header and hot the trash can next to the master branch to completely delete from this repository
1. Now go to `'settings'` and scroll down to Github pages and your site is published to that url:
`https://youngmarklewis.github.io/TestWebsite/`
You can change this url to a custom url - search the internet on how to do this!

# Adding a file to the webpage:

`'Create new file'` a text file e.g. `'testfile.txt'`
Add text for the webpage
Add `'testfile.txt'` to the url in the browser `https://youngmarklewis.github.io/TestWebsite/testfile.txt`
Hit enter and the page (page is a plain text file) is displayed on the web!

# To make a HTML testfile:

1. `'Create new file'` a text file index.html
1. Add some HTML content
1. In the browswer strip away `'testfile.txt'` to `leave https://youngmarklewis.github.io/TestWebsite/`
1. Hit enter
1. HTML page is displayed on the internet!

# Clone to a local PC

To clone to a local pc using command line:
1. Navigate to the correct directory - `/Users/Young/Documents/JavaScript`
1. Double check using `pwd`
1. Type `git clone https://github.com/youngmarklewis/TestWebsite.git`
1. Type `open .` to open in Finder and see that the TestWebsite repository has been cloned
1. Back in terminal type `git status` Observe that the branch is gh-pages
1. So... any commands have to use gh-pages e.g. `git pull origin gh-pages`