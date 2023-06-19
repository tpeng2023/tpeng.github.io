# My website

Built using the [Minimal Mistakes Jekyll theme](https://github.com/mmistakes/minimal-mistakes). Hat tip to [Grant McDermott](https://grantmcdermott.com/), from whom I learned a lot.

These are some changes I've made. They are more for my own reference later. Most questions of the configuration can be solved from reading the [quick-start guides of Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/) and searching the discussion [here](https://github.com/mmistakes/minimal-mistakes/discussions).

1. Added `font-size: $type-size-5-5;` to the file `_scss/minimal-mistakes/_base.scss`. This is to change the default font size when using `.md` pages.
2. Commented out `follow_label : # "Follow:"` in the file `_data/ui-text.yml`. This is to remove the "Follow: " text in the footer. 
3. Followed the README of [Grant McDermott](https://github.com/grantmcdermott/grantmcdermott.github.io/tree/master) and changed the landing page and pagination.
4. Added the following code into the file `_includes/head/custom.html`. This is to change the favicon of the website:
    ```html
    <link rel="apple-touch-icon" sizes="180x180" href="{{ base_path }}/assets/images/favicon_sc/apple-touch-icon.png">
    <link rel="icon" type="image/png" sizes="32x32" href="{{ base_path }}/assets/images/favicon_sc/favicon-32x32.png">
    <link rel="icon" type="image/png" sizes="16x16" href="{{ base_path }}/assets/images/favicon_sc/favicon-16x16.png">
    <link rel="manifest" href="{{ base_path }}/assets/images/favicon_sc/site.webmanifest">
    <link rel="mask-icon" href="{{ base_path }}/assets/images/favicon_sc/safari-pinned-tab.svg" color="#5bbad5">
    <meta name="msapplication-TileColor" content="#da532c">
    <meta name="theme-color" content="#ffffff">
    ```
5. Changed the footer height in the file `_sass/minimal-mistakes/_footer.scss`.
6. Defined a new button style for link to papers, in `_sass/minimal-mistakes/_buttons.scss`.

