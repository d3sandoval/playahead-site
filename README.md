# Playahead Games Site

## Development

Install the dependencies...

```bash
cd playahead-site
npm install
```

...then start the server:

```bash
npm run dev
```

Navigate to [localhost:8080](http://localhost:8080). You should see your app running. Edit a component file in `src`, save it, and reload the page to see your changes.

### Building and hosting

To create an optimised version of the app:

```bash
npm run build
```

You can upload the updated `public` folder wherever you'd like to host the treasure tracker.

---

To test that the production build is working locally, you can run a local `sirv` using the following command:

```bash
npm start
```

This will start up a server pointing to the `public` directory on `localhost:5000`