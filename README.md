# wittymax-blog

Blog for blog.wittymax.com

## Build Blog


This blog site is powered by [Hugo](https://gohugo.io/).

You need Hugo to be able to build the site.

To install Hugo:

```
sudo apt-get install hugo
```

Get Blog source code:
```
sudo apt install git 
git clone https://github.com/wittymax/wittymax-blog.git
```

Install submodules:

```
cd wittymax-blog
git submodule init
git submodule update
```

Serve as a website:

```
hugo server
```

Then visit http://localhost:1313