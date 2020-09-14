Minimal Next.js app using `yarn@2` in “zero-install” mode.

```
# Build dependencies
yarn

# Run a dev server
yarn dev

# Build the project locally
yarn build

# Run a local server
yarn start

# Set up and develop with Vercel
# Override Build Command with `yarn build`
# Override Development Command with `yarn dev --port $PORT`
vercel dev

# Deploy to Vercel Platform
vercel
```

As of Vercel CLI 20.1.0 the final step fails with this error:

> No Next.js version could be detected in your project. Make sure `"next"` is installed in "dependencies" or "devDependencies"
