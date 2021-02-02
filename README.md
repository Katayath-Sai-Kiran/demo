# Demo   (Main heading)
## github demo     (sub heading upto 5#'s )

.md stands for "mark down"

## old and italic formats
**sai kiran** (bold)

__sai kiran__ (italic)

_sai kiran_ (italic)

_*sai kiran*_ (bold and italic)

## markdownguide.org  
for markdown tutorials andreference

## usage of urls in markdown file
# https://github.com/

## blockquotes
> The blockquote element is used to indicate the quotation of a large section of text from another source. ... Using the default HTML styling of most web browsers, it will indent the right and left margins both on the display and in printed form, but this may be overridden by Cascading Style Sheets (CSS).
>> sai kiran

## ordered list
1. python
2. java script
3. flutter

    1. _widgets_ (italic)
    2. _components_
    3. _state management_
4. dart

    1. oops
    2. classes
    3. objects
5. java

## unoredred list

- data strutures
- algorithms
    * searching
    * sorting
        - bubble sort
        - quick sort
- oops concepts
- critical thinking

# inserting code
```python 
array = input().split()
for num in array:
    if (array.count(num) == int(num):
        print(num)
```
```python
input : 1 2 2 3 4 5 4 4 6 4 

output: 4
```

# inserting urls in markdown
Follow Me on 

[Facebook](www.facebook.com/search/20%sai20%kiran)

[Instagram](www.instagram.com)


Contact me at

[Gmail](www.gmail.com)

[Github](www.Github.com/login)

## inserting images

![Skills](https://github.com/Katayath-Sai-Kiran/demo/blob/master/3.jpg?raw=true)


# initialization

## git init -initialize git

## git status -view uncommited or stagged new files

## git add [filename]

```
$ git commit -m "added skills image"
[master (root-commit) dde6f4a] added skills image
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 3.jpg

```

## git log -commited history


```
$ git log
commit dde6f4a2584a1e4a563c2abf278bd23d5cbee787 (HEAD -> master)
Author: unknown <sai-kiran-the-programmer>
Date:   Tue Feb 2 11:53:45 2021 +0530

added skills image
```
## git remote add [remote name] [repo link]

```
$ git remote add pushInstance "https://github.com/sai-kiran-the-programmer/demo.git"
```
## git remote -v -all remotes

```
$ git remote -v
pushInstance    https://github.com/sai-kiran-the-programmer/demo.git (fetch)
pushInstance    https://github.com/sai-kiran-the-programmer/demo.git (push)

```
## git push [remoter name] [master name]

```
$ git push pushInstance master
GitEnumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 39.38 KiB | 13.13 MiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/sai-kiran-the-programmer/demo/pull/new/master
remote:
To https://github.com/sai-kiran-the-programmer/demo.git
 * [new branch]      master -> master

```

## inserting videos

[![30 days of flutter](https://img.youtube.com/vi/-feG_q_0j3Y/0.jpg)](https://www.youtube.com/watch?v=-feG_q_0j3Y)
