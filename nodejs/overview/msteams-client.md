---
title: Microsoft Teams Client API reference
description: Reference documentation for the latest Microsoft Teams JavaScript client library
keywords: msteams live-share teamsfx teams client sdk javascript library reference latest
---
# Microsoft Teams Client API reference

This article contains general information about the client library to support you in the development of using The Microsoft Teams Client SDK.

| Content library | Description | APIs |
|-|-|-|
| **Live Share** | Live Share transforms the Microsoft 365 platforms to be more a collaborative experience without writing any dedicated back-end code  | [Live-share](../docs-ref-autogen/%40microsoft/live-share/index.yml)<br/><br/>[Live-share canvas](../docs-ref-autogen/%40microsoft/live-share-canvas/index.yml)<br/><br/>[Live-share media](../docs-ref-autogen/%40microsoft/live-share-media/index.yml) |
| **Teams-JS** | Teams Java script client library enables developers to create app content hosted in [IFrame](https://developer.mozilla.org/docs/Web/HTML/Element/iframe) across the Microsoft 365 ecosystem | [TeamsJS ](../docs-ref-autogen/%40microsoft/teams-js/index.yml) |
| **Teams-FX** | TeamsFx helps to reduce your tasks by using Microsoft Teams single sign-on (SSO) and accessing cloud resources down to single line statements with zero configuration | [Teamsfx](../docs-ref-autogen/%40microsoft/teamsfx/index.yml) |

## Microsoft Teams JavaScript client library

The Microsoft Teams JavaScript client library version `2.x.x`,  is enabled [run apps across Microsoft 365](/microsoftteams/platform/m365-apps/overview). From a functional perspective, the TeamsJS SDK is a superset of TeamsJS 1.x versions: it supports existing Teams app functionality while adding the ability to host Teams apps in Outlook and Office.

Refer to the [Teams JavaScript client library](/microsoftteams/platform/tabs/how-to/using-teams-client-library) overview for guidance on building both Teams-only and Microsoft 365-enabled apps and for current SDK capability support across Teams, Outlook, and Office.

### Finding the library

The TeamsJS client is distributed as an [npm package](www.npmjs.com/package/@microsoft/teams-js) and be installed using npm (`npm install --save @microsoft/teams-js`) or yarn (`yarn add @microsoft/teams-js`).

### Using the library

If you are using any dependency loader or module bundler such as [RequireJS](http://requirejs.org/), [SystemJS](https://github.com/systemjs/systemjs), [browserify](http://browserify.org/), or [webpack](https://webpack.github.io/), you can use `import` syntax to import specific modules. For example:

```typescript
import * as microsoftTeams from "@microsoft/teams-js";
```
You can also reference the entire library in html pages using a script tag.  There are three ways to do this:

1. Microsoft Teams JavaScript API (via CDN)

```html
<script
  src="https://res.cdn.office.net/teams-js/2.0.0/js/MicrosoftTeams.min.js"
  integrity="sha384-Q2Z9S56exI6Oz/ThvYaV0SUn8j4HwS8BveGPmuwLXe4CvCUEGlL80qSzHMnvGqee"
  crossorigin="anonymous"
></script>
```

1.	Microsoft Teams JavaScript API (via npm)

```html
<script src="node_modules/@microsoft/teams-js@2.0.0/dist/MicrosoftTeams.min.js"></script>
```

1.	Microsoft Teams JavaScript API (via local)

```html
<script src="MicrosoftTeams.min.js"></script>
```
    This option uses a local copy on your servers, eliminating that dependency but requiring hosting and updating a local copy of the SDK.

> [!IMPORTANT]
> Do not copy/paste these `<script src=...` URLs from this page; they refer to a specific version of the SDK. Visit the [NPM site]( https://www.npmjs.com/package/@microsoft/teams-js) for the latest version of the markup. 

If you are a TypeScript developer it is helpful to install the NPM package as described [above](#installing-the-library), even if you don't link to the copy of `MicrosoftTeams.min.js` in `node_modules` from your HTML, because IDEs such as Visual Studio Code will use it for Intellisense and type checking.

