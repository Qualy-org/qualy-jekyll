An Boilerplate for start my projects

## Getting Starter

**Requires:**
- [Node](https://nodejs.org/en/)
- [Gulp](http://gulpjs.com/)
- [Jekyll](http://jekyllrb.com)

#### Using
```sh
# Clone repository
$ git@github.com:andersonweb/soon-generator.git name_project
$ cd name_project

# Install dependencies
$ npm install

# Run
$ gulp
```

#### Structure
```
name_project
├── _data
│   └── categories.yml
├── _includes
│   ├── footer.html
│   ├── header.html
│   └── head.html
├── _layouts
│   ├── blog_categories.html
│   ├── compress.html
│   ├── default.html
│   ├── page.html
│   └── post.html
├── _sass
│   ├── mixins
│   │   └── _breakpoint.scss
│   ├── modules
│   │   ├── _buttons.scss
│   │   ├── _clearfix.scss
│   │   ├── _components.scss
│   │   ├── _defaults.scss
│   │   ├── _reset.scss
│   │   ├── _typography.scss
│   │   └── _vars.scss
│   ├── partials
│   │   ├── _footer.scss
│   │   ├── _header.scss
│   │   ├── _main.scss
│   │   └── _nav.scss
│   │── vendor
│   │    └── _external.scss
│   └── main.scss
├── categories
│   └── categories.md
├── pages
│   └── page.md
│── src
│    ├── css
│    │   └── main.css
│    ├── fonts
│    ├── image
│    └── js
├── _config.yml
├── feed.xml
├── gulpfile.js
├── index.html
├── LICENSE
├── package.json
├── _posts
└── README.md

	
```

#### Plugins
- BrowserSync
- AutoPrefefixer
- Concat
- Sass
- Uglify

## License
[MIT](https://github.com/andersonweb/soon-generator/blob/master/LICENSE) © Anderson Menezes
