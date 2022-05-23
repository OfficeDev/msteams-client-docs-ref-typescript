---
title: Microsoft Teams client SDK version 1.12.1
description: Reference documentation for version 1.12.1 of the Microsoft Teams client SDK
keywords: msteams teams client sdk javascript reference previous
---
# Microsoft Teams JavaScript client SDK version 1.12.1

> [!IMPORTANT]
> The reference content in this section refers to a previous version (`v.1.12.1`) of the Microsoft Teams client SDK. Best practice is to use the latest release (`v.2.0.0` or later) of `@microsoft/teams-js`  whenever possible, in order to benefit from the latest improvements and new feature support. TeamsJS v.1.12 will continue to be supported, but no new features or improvements will be added.
>
> For more info, see the [Teams JavaScript client SDK](/microsoftteams/platform/tabs/how-to/using-teams-client-sdk) overview.

The Microsoft Teams JavaScript client SDK is part of the Microsoft Teams developer platform. It makes it easy to integrate your own services with Teams, whether you develop custom apps for your enterprise or SaaS applications for teams around the world. See [The Microsoft Teams developer platform](https://docs.microsoft.com/en-us/microsoftteams/platform/overview) for full documentation on the platform and on the SDK.

## Finding the SDK

The Teams client SDK version `1.12.1` is distributed as an npm package:
https://www.npmjs.com/package/@microsoft/teams-js/v/1.12.1

## Installing the SDK

You can install this package using npm or yarn:

* `npm install --save @microsoft/teams-js@1.12.1`
* `yarn add @microsoft/teams-js@1.12.1`

## Using the SDK

If you are using any dependency loader or module bundler such as [RequireJS](http://requirejs.org/), [SystemJS](https://github.com/systemjs/systemjs), [browserify](http://browserify.org/), or [webpack](https://webpack.github.io/), you can use `import` syntax to import specific modules. For example:

```typescript
import * as microsoftTeams from "@microsoft/teams-js@1.12.1";
```

You can also reference the entire library in html pages using a script tag.  There are three ways to do this:

> [!IMPORTANT]
> Do not copy/paste these `<script src=...` URLs from this page; they refer to a specific version of the SDK. To get the `<script src=...></script>` markup for the latest version, always go to https://www.npmjs.com/package/@microsoft/teams-js.

```html
<!-- Microsoft Teams JavaScript API (via CDN) -->
<script src="https://statics.teams.microsoft.com/sdk/v1.12.1/js/MicrosoftTeams.min.js" crossorigin="anonymous"></script>
 
<!-- Microsoft Teams JavaScript API (via npm) -->
<script src="node_modules/@microsoft/teams-js@1.12.1/dist/MicrosoftTeams.min.js"></script>

<!-- Microsoft Teams JavaScript API (copied local) -->
<script src="MicrosoftTeams.min.js"></script>
```

The final option, using a local copy on your servers, eliminates that dependency but requires hosting and updating a local copy of the SDK.

> [!TIP]
> If you are a TypeScript developer it is helpful to install the NPM package as described [above](#installing-the-sdk), even if you don't link to the copy of `MicrosoftTeams.min.js` in `node_modules` from your HTML, because IDEs such as Visual Studio Code will use it for Intellisense and type checking.

## Reference

The following sections contain reference pages for all the elements of the Teams client API. These pages are auto-generated from the source found in the npm module on https://www.npmjs.com/package/@microsoft/teams-js. The source code for the SDK is located at https://github.com/OfficeDev/microsoft-teams-library-js.

* [microsoft.teams-js](https://docs.microsoft.com/javascript/api/%40microsoft/teams-js/)

And remember that [The Microsoft Teams developer platform](https://docs.microsoft.com/microsoftteams/platform) has full documentation on using the platform and the SDK.
