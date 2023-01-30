---
title: Microsoft Teams SDK JavaScript client library
description: Reference documentation for the latest Microsoft Teams SDK JavaScript client library
keywords: sdk msteams teams client javascript library reference latest
---
# Microsoft Teams JavaScript client library

Starting with *@microsoft/teams-js* version `2.0.0`, the Microsoft Teams JavaScript client library has been refactored to enable [Teams apps to run in Outlook and Office](/microsoftteams/platform/m365-apps/overview), in addition to Microsoft Teams. From a functional perspective, the TeamsJS SDK is a superset of TeamsJS 1.x versions: it supports existing Teams app functionality while adding the ability to host Teams apps in Outlook and Office.

> [!TIP]
> Refer to the [Teams JavaScript client library](/microsoftteams/platform/tabs/how-to/using-teams-client-library) overview for guidance on building both Teams-only and Microsoft 365-enabled apps and for current SDK capability support across Teams, Outlook, and Office.

## Finding the library

The TeamsJS client is distributed as an npm package. The latest version can be found here:

www.npmjs.com/package/@microsoft/teams-js

## Installing the library

You can install the package using npm or yarn:

* `npm install --save @microsoft/teams-js`
* `yarn add @microsoft/teams-js`

## Using the library

If you are using any dependency loader or module bundler such as [RequireJS](http://requirejs.org/), [SystemJS](https://github.com/systemjs/systemjs), [browserify](http://browserify.org/), or [webpack](https://webpack.github.io/), you can use `import` syntax to import specific modules. For example:

```typescript
import * as microsoftTeams from "@microsoft/teams-js";
```

You can also reference the entire library in html pages using a script tag.  There are three ways to do this:

> [!IMPORTANT]
> Do not copy/paste these `<script src=...` URLs from this page; they refer to a specific version of the SDK. To get the `<script src=...></script>` markup for the latest version, always go to https://www.npmjs.com/package/@microsoft/teams-js.

```html
<!-- Microsoft Teams JavaScript API (via CDN) -->
<script
  src="https://res.cdn.office.net/teams-js/2.0.0/js/MicrosoftTeams.min.js"
  integrity="sha384-Q2Z9S56exI6Oz/ThvYaV0SUn8j4HwS8BveGPmuwLXe4CvCUEGlL80qSzHMnvGqee"
  crossorigin="anonymous"
></script>

<!-- Microsoft Teams JavaScript API (via npm) -->
<script src="node_modules/@microsoft/teams-js@2.0.0/dist/MicrosoftTeams.min.js"></script>

<!-- Microsoft Teams JavaScript API (via local) -->
<script src="MicrosoftTeams.min.js"></script>
```

The final option, using a local copy on your servers, eliminates that dependency but requires hosting and updating a local copy of the SDK.

> [!TIP]
> If you are a TypeScript developer it is helpful to install the NPM package as described [above](#installing-the-library), even if you don't link to the copy of `MicrosoftTeams.min.js` in `node_modules` from your HTML, because IDEs such as Visual Studio Code will use it for Intellisense and type checking.

## Reference

The following sections contain reference pages for all the elements of the Teams client SDK. These pages are auto-generated from the source found in the npm module on https://www.npmjs.com/package/@microsoft/teams-js. The source code is located at https://github.com/OfficeDev/microsoft-teams-library-js/tree/main/packages/teams-js.
