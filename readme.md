# config-site-layout

A simple layout foundation for frontend and editor, based on the core style variables.

---

Version: 1.1.9

Author: Ben & Matze @ https://modularity.group

License: MIT

---

Custom variables:

```
--site-layout-columns-gap: 1rem;
```

Suggestion for your theme.json:

```
  "layout": {
    "contentSize": "var(--base-content-width)",
    "wideSize": "var(--base-layout-width)",
    "units": [ "px", "em", "rem", "%", "vw", "vh" ]
  }
```

---

1.1.9 | tweak editor layout full and resusable

1.1.8
- improve handling of aligned images in editor-wp-groups
- improve display of editor title

1.1.7 | fix editor title display

1.1.6 | improve layouts inside groups, columns, inside covers, iframes and editor title

1.1.5 | fix in columns layout

1.1.4 | switch vertical spacing to new --base-offset-vertical

1.1.3 | tweak custom columns gap

1.1.2 | extend custom columns gap

1.1.1 | fix editor layout over-width

1.1.0 | rename .container to .site-layout-container

1.0.5 | no last child margin in background columns

1.0.4 | root --site-layout-offset-vertical

1.0.3 | fix vertical padding and wide offset

1.0.2 | loading fixes

1.0.1 | add possibiliy to setup vertical offset

1.0.0 | release as starter module
