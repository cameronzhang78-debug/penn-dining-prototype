# Penn Dining prototype

An interactive HTML prototype of a Penn Dining app redesign (Android frame), with light and dark modes.

## Run it

Open `penn-dining.html` in a browser, or serve the folder locally:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
# then open http://localhost:8000/
```

`index.html` is the same page without the `<html>/<head>/<body>` wrapper.

## What's in it

- Home: dining halls list and Dining Insights (balances, budgeting, analytics chart)
- Dining hall page: menu by section, Brunch/Dinner, weekly hours sheet, in-place search and filters
- Search Menus: on-screen keyboard, results by hall, filter sheet, nutrition details
- Light/dark toggle (left of the phone)

Designs from Figma; hall photos in `assets/`.
