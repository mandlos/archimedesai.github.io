# archimedesai.github.io
Domain to upload all ArchimedesAI-related content

/archimedesai.github.io
├── _config.yml
├── README.md
├── index.md
├── CNAME
├── .gitignore
├── Gemfile
├── 404.html
├── /_layouts
│ ├── default.html
│ └── post.html
├── /_includes
│ ├── header.html
│ └── footer.html
├── /_posts
│ └── 2023-01-01-my-first-post.md
├── /_data
│ └── navigation.yml
├── /_sass
│ ├── _variables.scss
│ └── _layout.scss
└── /assets
├── /css
│ └── main.scss
├── /js
│ └── script.js
├── /img
│ └── logo.png
└── /fonts
└── custom-font.woff

**_layouts**: Templates for different page types (e.g., default.html, post.html). Basic HTML templates for site's content.

**_includes**: Store reusable components like header, footer and navigation bar. Files in this directory can be included in layout and post files.

**_posts**: If there is a blog or news section, individual markdown files for each post go here. The file names follow a YEAR-MONTH-DAY-title.md format.

**_data**: Store data files like navigation bars, easily managed in YAML, JSON, or CSV formats.

**_sass**: Contains Sass partials (e.g., _variables.scss, _layout.scss) that can be imported into main stylesheet for easier management of CSS.

**_assets**: Contains static files like CSS, JavaScript, images, and fonts. Can be further organized into subdirectories (css, js, img, fonts).

**_pages**: For additional pages like About, Contact, etc., separate from blog posts. Each page can be a markdown file with a layout defined in the front matter.

