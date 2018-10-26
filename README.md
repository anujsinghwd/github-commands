### Create a new repository on the command line
```jsx
  echo "# Repo Name" >> README.md
```
```jsx
  git init
```
```jsx
  git add README.md // if you want to add
```
```jsx
  git commit -m "first commit"
```
```jsx
  git remote add origin https://github.com/username/repo-name.git
```
```jsx
  git push -u origin master
```

### Push an existing repository from the command line
```jsx
  git remote add origin https://github.com/username/repo-name.git
```
```jsx
  git push -u origin master
```

### Updating a clone repo
```jsx
  git add .
```
```jsx
  git commit -m "updating repo"
```
```jsx
  git push origin master
```
