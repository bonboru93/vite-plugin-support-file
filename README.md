# Introduction
Open your website by double-clicking the index.html locally without a file server.

# Usage

```
npm install vite-plugin-support-file
```

Add to your Vite config:
```javascript
// vite.config.js
import { defineConfig } from 'vite';
import supportFile from 'vite-plugin-support-file';

export default defineConfig({
  plugins: [
    supportFile()
  ]
});
```
```
npm run build
```
Enjoy~

# How it works ?
1. change Rollup output format to ```systemjs```
2. inject ```s.min.js``` into index.html