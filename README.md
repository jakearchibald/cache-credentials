```
npm install
npm run serve
```

Visit `localhost:3000`, the friendly site. Refresh, and it'll echo back an HTTP-only cookie.

Visit `localhost:3001` in a way that it'll allow fetching from the browser cache (as in, not a refresh which forces revalidation). It may show credentials.
