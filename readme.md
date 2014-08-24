# Bower search server

> Aggregated list of packages from the [Bower registry](https://github.com/bower/registry), GitHub metadata, bower.json/package.json keywords.

**This is a temporary solution while the [new registry](https://github.com/bower/registry) is being built. No new features will implemented**

Currently used as the back-end for the [Bower search](https://github.com/bower/search).

The registry can also be filtered on a keyword to only get a subset of it. Useful if you for example want to embed a list of plugins for your framework on a website. Example: https://bower-component-list.herokuapp.com/keyword/web-components

### Getting Started

- [Register a new OAuth app](https://github.com/settings/applications/new) on GitHub. This is needed since GitHub allows more API usage for registered apps.

- Set the environment variables from your newly created app (alternatively use foreman `.env` file)

- Install dependencies `npm install`

- Run `npm start` (alternatively run `foreman start`)

Environmental variables:
- `GITHUB_CLIENT_ID`
- `GITHUB_CLIENT_SECRET`
- `NODE_ENV` `development` | `production` (remember to set this!)
- `PORT` - optional to change `connect` server's port
 
## License

MIT © [Sindre Sorhus](http://sindresorhus.com)
