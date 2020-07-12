# blog

Hi Taylor, ok so here's the steps to get your website up to tayleenam.com

make sure terminal is open
```
cd ~/Documents/blog
jekyll build
git add -A
git commit -m "insert your commit message here"
git push origin master
```

And then it should be live in a few minutes

### Running locally
To get localhost:4000 running you need to have terminal open and run these lines

```
cd ~/Documents/blog
jekyll serve
```

And then localhost:4000 will render your local site. Keep in mind this is a running server so you can't perform any other commands in the terminal window. To stop it, run `ctrl + c`. You can also open another tab in terminal to run other commands.
