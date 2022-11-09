GitHub Pages
GitHub Pages is a GitHub service that makes it easy to deploy any static website in 10 seconds (static == same content for all users). It is based on a “magic” branch, called gh-pages. When GitHub detects this branch, it puts your website online. Awesome right? Let’s create this magic branch and push it. ✨🌿✨

git co -b gh-pages
git push origin gh-pages # we push the gh-pages branch, not master!
Now you can visit the URL http://jean852.github.io/profile/ (this is the URL built automatically by GitHub) and have a look at your masterpiece online! Share the link on Slack with your buddies.

From now and until the end of the day, you can keep working in your ~/code/jean852/profile directory AND on the gh-pages branch. This means any updates of your profile can be pushed on http://jean852.github.io/profile/ through usual git commands:

git add .
git commit -m "make my profile prettier"
git push origin gh-pages
