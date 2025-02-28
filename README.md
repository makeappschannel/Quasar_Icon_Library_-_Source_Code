# Quasar Icon Library (quasar-icon-library)

A Quasar Framework app

## Install the dependencies
```bash
npm install
```

### Start the app in development mode (hot-code reloading, error reporting, etc.)
```bash
quasar dev
```


### Build the app for production
```bash
quasar build
```


### Generate Icon Library
This will generate the icon library files at `public/icon-font` based on the SVG files in `src/svg-icons`
```bash
npm run icon-font
```

### Watch for Changes & Generate Icon Library
First install the watch package:
```bash
npm install watch -g
```
Then run this to watch for changes in the `src/svg-icons` folder & regenerate the icon library automatically:
```bash
npm run icon-font:watch
```

