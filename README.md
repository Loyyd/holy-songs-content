# holy-songs-content

Source ChordPro files for the `holy-songs` app live here.

## Layout

```text
songs/
  *.pro
```

The app repository expects this repo to sit beside it:

```text
GitHub/
  holy-songs/
  holy-songs-content/
```

When the app runs locally or in Docker, it reads song files from `songs/` in this repo and generates runtime JSON data in the app repo.
