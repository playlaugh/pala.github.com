Source code of [http://ztpala.com](http://ztpala.com)，powered by [Jekyll](http://jekyllrb.com/)。

## How to use my theme
```sh
# Replace USERNAME with your GitHub id
$ git clone git@github.com:pala/pala.github.com.git USERNAME.github.io
$ cd USERNAME.github.io
$ ./cleanup #will delete all my posts and pages
$ git remote set-url origin git@github.com:USERNAME/USERNAME.github.io.git
```

You also need to edit these files:

1. _config.yml

2. CNAME (Delete it if you don't have a custom domain to set)

3. _layouts/default.html (edit site name and navigation menu)

Finally, push to GitHub

```
$ git push origin master
```

## License
Files in `_posts` are my own stuff, please don's use them without my permission. Everything else is MIT Licensed(check LICENSE file).

`_posts`下所有文件版权所有，未经授权请勿使用，其他文件请看`LICENSE`。
