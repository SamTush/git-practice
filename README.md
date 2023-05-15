# Git exercise 2 [module 1]

In this project i practice Git and Github in a series from bundle 1 to bundle 6

## In exercise 1, these are the commands used:

- Create home.html

```
    touch home.html
```

- Stash save change in home.html:

```
    git stash save
```

- Create about.html:

``` 
    touch about.html
```

- Stash save change in about.html:

``` 
    git stash save
```
- Create team.html:

``` 
    touch team.html
```

- Restore changes of the about page:

``` 
    git stash pop stash@{1}
```

- With the help of an index use stash pop bring back the home page changes:

``` 
    git stash pop stash@{0}
```

- Commit the current changes and push them:

``` 
    git add .
    git commit -m "Add home.html about.html and team.html"
    git push --up-steam origin feature/exercise-two
```

- Using stash pop restore the changes of the team page index:

``` 
    git stash pop stash@{2}
```

- Reset the current changes using git reset and go back to the changes without the team page:

``` 
    git reset HEAD~
```


### Thank you for reviewing my exercise 
