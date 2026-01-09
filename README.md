# mozilla-website

This is just an empty repository containing a README and a picture of a fox. It also contains a HTML file that has a website with just a title.



## Assignment Part 1 -- HTML
### 1. Make a branch called `learn-html`

How? 

`cd` into your `mozilla-website` project directory. 

List all of the branches in the repo:
```
git branch
```
You should only see a `main` branch right now. To create a new branch named `learn-html` run
```
git branch learn-html
```
Now list all the repository branches again
```
git branch
```
Do you see the new `learn-html` branch? Notice that the `main` branch is starred, which means that we're currently working within it. Creating a new branch with `git branch` will not automatically switch you into it. 

To switch into the `learn-html` branch, run
```
git checkout learn-html
```
Try listing the repository branches again. You should see that `learn-html` branch is now starred. 



### 2.  Follow this HTML Tutorial
https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics). 

**Make sure you make a handful of commits to the `learn-html` branch while working through the tutorial**.
### 3. Push the branch to GitHub and merge it into `main`
To push the `learn-html` branch, run `git branch` to make sure you're working on the right branch. Then run
```
git push origin learn-html
```
This will push the current local branch (`learn-html`) to the remote repository on Github. 

Now create a pull request from the `learn-html` branch to `main`. 

### 4. Switch to the main branch on your computer locally and pull the `main` branch. 
You learned how to switch branches above. To pull the `main` branch down, run 
```
git pull origin main
````

## Assignment Part 2 -- CSS 
1. Make a branch called `learn-css`
2. Follow this [CSS Tutorial](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics). Make sure you make a handful of commits along the way inside the `learn-css` branch.
3. Push the branch to GitHub and merge it into `main`
4. Switch to the main branch on your computer locally and pull the `main` branch
