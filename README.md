# puppilot-docs
Documentation for Puppilot API

# Mintlify Starter Kit

Click on `Use this template` to copy the Mintlify starter kit. The starter kit contains examples including

- Guide pages
- Navigation
- Customizations
- API Reference pages
- Use of popular components

### Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview the documentation changes locally. To install, use the following command

```
npm i -g mintlify
```

Run the following command at the root of your documentation (where mint.json is)

```
mintlify dev
```

#### Option 2: Local Installation (Alternative Approach)
If you encounter issues with the global installation (e.g., dependency conflicts), you can use `npx` to run Mintlify locally:

1. Install Mintlify as a local dependency:
   ```
   npm install --save-dev mintlify
   ```
2. Run the development server using npx:
    ```
    npx mintlify dev
    ```


### Publishing Changes

Install our Github App to auto propagate changes from your repo to your deployment. Changes will be deployed to production automatically after pushing to the default branch. Find the link to install on your dashboard. 

Installation of Github App has already been done for this project. Follow steps below to deploy new changes: 
1. Once new code is merged to 'main' branch, it should automatically deploy live to the following url: https://puppilot-5365ecb4.mintlify.app
2. Sometimes it lags so to manually deploy, log into https://dashboard.mintlify.com/puppilot-5365ecb4
3. On the Overview page, click the 'manual update' button on the upper right if you don't see your deployment in Activity History. 
4. Once status of deployment is 'successful' you should see those changes reflected in the live url: https://puppilot-5365ecb4.mintlify.app



#### Troubleshooting

- Mintlify dev isn't running - Run `mintlify install` it'll re-install dependencies.
- Page loads as a 404 - Make sure you are running in a folder with `mint.json`
