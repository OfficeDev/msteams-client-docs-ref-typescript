---
title: Microsoft Teams client SDK
description: Reference documentation for the Microsoft Teams client SDK
keywords: msteams teams client sdk javascript reference
---
# Microsoft Teams JavaScript client SDK

The Microsoft Teams JavaScript client SDK is part of the Microsoft Teams developer platform. It makes it easy to integrate your own services with Teams, whether you develop custom apps for your enterprise or SaaS applications for teams around the world. See [The Microsoft Teams developer platform](https://docs.microsoft.com/en-us/microsoftteams/platform/overview) for full documentation on the platform and on the SDK.

## Finding the SDK

The Teams client SDK is distributed as an npm package. The latest version can be found here:
https://www.npmjs.com/package/@microsoft/teams-js.

## Installing the SDK

You can install the package using npm or yarn:

* `npm install --save @microsoft/teams-js`
* `yarn add @microsoft/teams-js`

## Using the SDK

If you are using any dependency loader or module bundler such as [RequireJS](http://requirejs.org/), [SystemJS](https://github.com/systemjs/systemjs), [browserify](http://browserify.org/), or [webpack](https://webpack.github.io/), you can use `import` syntax to import specific modules. For example:

```typescript
import * as microsoftTeams from "@microsoft/teams-js";
```

You can also reference the entire library in html pages using a script tag.  There are three ways to do this:

```html
<!-- Microsoft Teams JavaScript API (via CDN) -->
<script src="https://statics.teams.microsoft.com/sdk/v1.4.2/js/MicrosoftTeams.min.js" crossorigin="anonymous"></script>
 
<!-- Microsoft Teams JavaScript API (via npm) -->
<script src="node_modules/@microsoft/teams-js@1.4.2/dist/MicrosoftTeams.min.js"></script>

<!-- Microsoft Teams JavaScript API (copied local) -->
<script src="MicrosoftTeams.min.js"></script>
```

The final option, using a local copy on your servers, eliminates that dependency but requires hosting and updating a local copy of the SDK.

> [!IMPORTANT]
> Do not copy/paste these `<script src=...` URLs from this page; they refer to a specific version of the SDK. To get the `<script src=...></script>` markup for the latest version, always go to https://www.npmjs.com/package/@microsoft/teams-js.

> [!TIP]
> If you are a TypeScript developer it is helpful to install the NPM package as described [above](#installing-the-sdk), even if you don't link to the copy of `MicrosoftTeams.min.js` in `node_modules` from your HTML, because IDEs such as Visual Studio Code will use it for Intellisense and type checking.

## Reference

The following sections contain reference pages for all the elements of the Teams client API. These pages are auto-generated from the source found in the npm module on https://www.npmjs.com/package/@microsoft/teams-js. The source code for the SDK is located at https://github.com/OfficeDev/microsoft-teams-library-js.

* [microsoft.teams-js](https://docs.microsoft.com/javascript/api/%40microsoft/teams-js/)

And remember that [The Microsoft Teams developer platform](https://docs.microsoft.com/microsoftteams/platform) has full documentation on using the platform and the SDK.
