---
title: Microsoft Teams JavaScript client SDK
description: Reference documentation for the latest Microsoft Teams JavaScript client SDK
keywords: msteams teams client sdk javascript reference latest
---
# Microsoft Teams JavaScript client SDK

Starting with *@microsoft/teams-js* version `2.0.0`, the Microsoft Teams JavaScript client SDK has been refactored to enable [Teams apps to run in Outlook and Office](/microsoftteams/platform/m365-apps/overview), in addition to Microsoft Teams. From a functional perspective, the TeamsJS SDK is a superset of TeamsJS 1.x versions: it supports existing Teams app functionality while adding the ability to host Teams apps in Outlook and Office.

> [!TIP]
> Refer to the [Teams JavaScript client SDK](/microsoftteams/platform/tabs/how-to/using-teams-client-sdk) overview for guidance on building both Teams-only and Microsoft 365-enabled apps and for current SDK capability support across Teams, Outlook, and Office.

## Finding the SDK

The TeamsJS client is distributed as an npm package. The latest version can be found here:

www.npmjs.com/package/@microsoft/teams-js

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

> [!IMPORTANT]
> Do not copy/paste these `<script src=...` URLs from this page; they refer to a specific version of the SDK. To get the `<script src=...></script>` markup for the latest version, always go to https://www.npmjs.com/package/@microsoft/teams-js.

```html
<!-- Microsoft Teams JavaScript API (via CDN) -->
<script
  src="https://res.cdn.office.net/teams-js/2.0.0/js/MicrosoftTeams.min.js"
  integrity="sha384-QtTBFeFlfRDZBfwHJHYQp7MdLJ2C3sfAEB1Qpy+YblvjavBye+q87TELpTnvlXw4"
  crossorigin="anonymous"
></script>

<!-- Microsoft Teams JavaScript API (via npm) -->
<script src="node_modules/@microsoft/teams-js@2.0.0/dist/MicrosoftTeams.min.js"></script>

<!-- Microsoft Teams JavaScript API (via local) -->
<script src="MicrosoftTeams.min.js"></script>
```

The final option, using a local copy on your servers, eliminates that dependency but requires hosting and updating a local copy of the SDK.

> [!TIP]
> If you are a TypeScript developer it is helpful to install the NPM package as described [above](#installing-the-sdk), even if you don't link to the copy of `MicrosoftTeams.min.js` in `node_modules` from your HTML, because IDEs such as Visual Studio Code will use it for Intellisense and type checking.

## Reference

The following sections contain reference pages for all the elements of the Teams client SDK. These pages are auto-generated from the source found in the npm module on https://www.npmjs.com/package/@microsoft/teams-js. The source code is located at https://github.com/OfficeDev/microsoft-teams-library-js/tree/main/packages/teams-js.
