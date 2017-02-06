# Blog O Monge, o Artista e o Executivo

### Deploy the blog

```
$ npm i -S hexo-deployer-git
$ hexo deploy
```

### Deploy new post

#### Adding a new post

```
$ hexo new {postname}
```

#### Edit the new post file

```
$ vi source/_posts/{postname}.md
```

#### Regenerate files and deploy at once

```
$ hexo generate -d
```