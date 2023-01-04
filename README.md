Theme—GravCms

Implementation of A,[Aoics](https://github.com/eotun) for [GravCMS](https://github.com/getgrav/grav)

> **Warning**
> WiP—TbR

# instal

`
cd ~~/Grav/user/themes/
git clone ~ agrvoi
`

« /user/config/system.yaml
```
+ pages: {theme: agrvoi}
+ home: {alias: /a}
```

« /user/config/site.yaml
```
+ taxonomies: [q,c]
```

« /user/pages
`mkdir a && touch a/a.md`

# authoring

> Pages should be named `a.md` (fallback for `default.md`)—call for base layout `~/user/themes/aoi/templates/a.html.twig`.

Use standard fields `title` & `menu`; customs `d` for description, `m` for metainfo, `e` for errors, `t` for tips.