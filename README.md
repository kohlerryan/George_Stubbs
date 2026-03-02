# Samsung TV Art Collection — Data Format Guide

Each artist collection folder contains an `artwork_data.csv` file that holds the metadata for all artworks in that collection.

## Required File Name

The data file **must** be named exactly:

```
artwork_data.csv
```

## CSV Column Reference

| Column | Description |
|---|---|
| `artwork_dir` | The folder/directory name containing the artwork image files. Should match the artist folder name exactly. |
| `artwork_file` | The filename of the artwork image (e.g., `Claude Monet_1881_Flower Beds at Vétheuil.jpg`). |
| `artwork_title` | The display title of the artwork. |
| `artwork_year` | The year or date range the artwork was created (e.g., `1881` or `1917-1919`). |
| `artist_name` | The full name of the artist as it should appear in the UI. |
| `artist_lifespan` | The artist's birth and death years, separated by an em dash (e.g., `1840–1926`). |
| `artwork_medium` | The medium or technique used (e.g., `Oil on canvas`). |
| `artwork_description` | A longer text description of the artwork. Supports inline formatting (see below). Wrap in double quotes if the text contains commas. |

## Text Formatting in Fields

The `artwork_description` field (and other text fields) support the following inline formatting syntax:

| Syntax | Result |
|---|---|
| `**bold**` | **bold** |
| `*italic*` | *italic* |
| `_italic_` | *italic* |
| `***bold and italic***` | ***bold and italic*** |
| `` `code` `` | `code` |
| `line one\nline two` | line break (in multiline fields) |


## Support

If you find this collection useful, consider supporting the project:

[![Buy Me A Coffee](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/kohlerryan)
