Implementation of A,[Acosi](https://github.com/eotun/cs) for [GravCMS](https://github.com/getgrav/grav). 

> Represent `~/user/pages/`-folder in nested-hierarchial folder-structure; Gather relative information, navigation & custom appearance based on taxonomy `q: []`.

# instal

> **Warning**
> WiP—TbR

```
cd ~~/Grav/user/themes/
git clone ~ agroiv
```

« /user/config/system.yaml
```
+ pages: {theme: agroiv}
+ home: {alias: /a}
+ assets: {css_pipeline: true}
```

« /user/config/site.yaml
```
+ taxonomies: [q]
```

« /user/pages
`mkdir a && touch a/a.md`

# authoring

> Pages should be named `a.md` (fallback for `default.md`)—call for base layout `~/user/themes/aoi/templates/a.html.twig`.

fields: standard `title`&`menu`;+ customs `d`—description, `m`—metainfo, `e`—errors, `t`—tips.