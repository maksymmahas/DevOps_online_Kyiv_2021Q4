# DevOps_online_Kyiv_2021Q4

# Workflow
1. Created a new private repository with the name: DevOps_online_Kyiv_2021Q4
2. Created hierarchy of folders on my workstation:
```
m1/
  task1.1/
```
3. Cloned repository to my workstation:
```
git clone https://github.com/maksymmahas/DevOps_online_Kyiv_2021Q4.git
```
5. Created a new empty _readme.txt_ file:
```
touch readme.txt
```
6. Made initial commit:
```
git add .
git commit -m "initial commit"
```
7. Created **develop** branch and checkouted on it:
```
git checkout -b "develop"
```
8. Created empty _index.html_ file:
```
touch index.html
```
9. Made commit:
```
git add .
git commit -m "created empty index.html"
```
10. Created a new **images** branch and checkouted on it and created _images_ folder and added photos in it:
```
git checkout -b "images"
mkdir images
cd images
git add .
git commit -m "added photos"
```
11. Changed _index.html_ and added images into _images_ folder and added images sources to _index.html_:


Added 3 images into _images_ folder:

![photo](https://user-images.githubusercontent.com/86875795/124360648-a08d7500-dc33-11eb-98fe-446491f8184d.jpg)
![photo2](https://user-images.githubusercontent.com/86875795/124360676-be5ada00-dc33-11eb-8391-c8fc3892f223.jpg)
![photo3](https://user-images.githubusercontent.com/86875795/124360684-c6b31500-dc33-11eb-861f-a8089354e0b1.jpg)
```
<!DOCTYPE html>
<html>
<head>
<title>Images</title>
</head>
<body>
<img src="images/photo.jpg">
<img src="images/photo2.jpg">
<img src="images/photo3.jpg">
</p>
</body>
</html>
```
12. Returned to **develop** branch:
```
git checkout develop
```
13. Created **styles** branch and checkouted on it, also added _styles_ folder with _styles.css_ file in it, also linked _styles.css_ with _index.html_:
```
git checkout -b "styles"
mkdir styles
cd styles
touch styles.css
nano styles.css
git add .
git commit -m "added styles.css"
nano index.html
git add .
git commit -m "linked styles.css to index.html"
```


_styles.css_ file contains:
```
body {
  background-color: powderblue;
}
h1 {
  color: blue;
}
p {
  color: red;
}
```


_index.html_ file contains:
```
<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="styles/styles.css">
<title>Images</title>
</head>
<body>
<h1>Hello EPAM!</h1>
<p>Hello World!
</p>
</body>
</html>
```

14. Merged to new branches into **develop** and resolved merge conflict:
```
git checkout develop
git merge images
git merge styles 
git status 
nano index.html 
git add .
git commit -m "resolved merge conflict"
```

15. Merged **develop** into **master**:
```
git checkout master
git merge develop
```

16. Pushed all my local changes to remote repository:
```
git push origin --all
```





In my opinion, DevOps is a specialist who takes part not only in the development but also in the deployment process in order to reduce the company's costs and reduce the workload.
