---
title: Microsoft Teams client SDK
description: Reference documentation for the Microsoft Teams client SDK
keywords: msteams teams client sdk javascript reference
ms.date: 08/08/2018
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
<!-- Microsoft Teams JavaScript API (linking to a specific version via CDN) -->
<script src="https://unpkg.com/@microsoft/teams-js@1.3.3/dist/MicrosoftTeams.min.js" integrity="sha384-g1iQyAjC6TaAEj70a8TEV96chNDvgDxIjqEdppo/wph3gPqZ60d7lA1mxDUkAETe" crossorigin="anonymous"></script>

<!-- Microsoft Teams JavaScript API (via npm) -->
<script src="node_modules/@microsoft/teams-js@1.3.3/dist/MicrosoftTeams.min.js"></script>

<!-- Microsoft Teams JavaScript API (copied local) -->
<script src="MicrosoftTeams.min.js"></script>
```

The first method, using unpkg.com, is probably the most practical unless you prefer not to use a third-party party service like unpkg.com. The final option, using a local copy on your servers, eliminates that dependency but requires hosting and updating a local copy of the SDK.

> [!IMPORTANT]
> Do not copy/paste these `<script src=...` URLs from this page; they refer to a specific version of the SDK. To get the URLs for the latest version, always go to https://www.npmjs.com/package/@microsoft/teams-js.

## Reference

The following sections contain reference pages for all the elements of the Teams client API. These pages are auto-generated from the source found in the npm module on https://www.npmjs.com/package/@microsoft/teams-js. The source code for the SDK is located at https://github.com/OfficeDev/microsoft-teams-library-js.

* [microsoft.teams-js](/javascript/api/msteams-client/)

And remember that [The Microsoft Teams developer platform](https://docs.microsoft.com/en-us/microsoftteams/platform/overview) has full documentation on using the platform and the SDK.
