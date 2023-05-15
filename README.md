# Git exercise 1

In this project i practice Git and Github in a series from bundle 1 to bundle 6

## In exercise 1, these are the commands used:

- To initialize git:

```
    git init
```

- To rename main branch from master to main:

```
    git branch -m master main
```

- Stash save change in about.html:

``` 
    touch home.html
```

- To stage changes and commit:

```
    git add .
    git commit -m "Add home.html file"
```

- To connect github to the project:

``` 
    git remote add origin https://github.com/SamTush/git-practice.git
```

- To push to github:

``` 
    git push -u origin main
```

- To create a new branch:

```
    git checkout -b dev
```

- To create another branch from dev:

```
    git checkout dev
    git checkout -b test
```

- To delete the test branch:

```
    git branch -d test
```

### Thank you for reviewing my exercise 