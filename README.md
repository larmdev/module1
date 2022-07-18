### git submodule

*** git submodule add ***
```
git submodule add <URL "submodule"> <PATH>
```
*** example ***
```
git submodule add git@github.com:larmdev/module2.git lib/module2
```


### git clone project submodule 

```
git clone git@github.com:larmdev/module1.git
```
```
cd module1
```
```
git submodule init
```
```
git submodule update
```


### update submodu remote

```
cd module1
```
```
git submodule update --remote
```