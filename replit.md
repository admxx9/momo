# Find My Heart

A static HTML interactive game where the user finds 3 hidden hearts among emoji icons.

## Project Structure

- `index.html` — The entire application (single-file static HTML, CSS, and JavaScript)

## Running the App

The app is served via Python's built-in HTTP server on port 5000:

```
python3 -m http.server 5000 --bind 0.0.0.0
```

## Deployment

Configured as a static site deployment with `publicDir: "."`.
