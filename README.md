# My Music

Simple static music list.

## Structure

* `index.html` — edit album names and links here.
* `style.css` — basic styling.
* `covers/` — put your album cover images here.

## Adding an album

Copy an existing `<a class="album">...</a>` block in `index.html`.

Change:

1. The `href` to the album URL.
2. The image filename inside `src`.
3. The text inside `<span>`.

For example:

```html
<a class="album" href="https://open.spotify.com/" target="\\\_blank" rel="noopener">
  <img src="covers/my-album.jpg" alt="My Album">
  <span>My Album</span>
</a>
```

You can add as many albums as you want to `current rotation`.

For the five albums under `fav albums`, just replace the five placeholders with your own albums.

