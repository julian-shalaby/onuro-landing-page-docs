# Onuro Documentation

This repository contains the documentation for Onuro's AI-powered development tools. The documentation covers:

- IDE Extensions
- Web & Mobile Apps
- Chrome Extension
- AI Capabilities
- Context Management
- Advanced Features

### Development

To preview the documentation locally, first install the [Mintlify CLI](https://www.npmjs.com/package/mintlify):

```bash
npm i -g mintlify
```

Then run the following command at the root of the documentation (where docs.json is):

```bash
mintlify dev
```

### Publishing Changes

Changes will be automatically deployed when pushed to the main branch. To enable automatic deployments:

1. Install the Onuro GitHub App from your dashboard
2. Connect it to your documentation repository
3. Push changes to your default branch

### Troubleshooting

- If Mintlify dev isn't running - Run `mintlify install` to re-install dependencies
- If page loads as a 404 - Make sure you are running in a folder with `docs.json`
- For other issues, please contact the Onuro team