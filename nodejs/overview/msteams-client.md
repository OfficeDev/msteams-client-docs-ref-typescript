---
title: Microsoft Teams client SDK v2 Preview
description: Reference documentation for the Microsoft Teams client SDK v2 Preview
keywords: msteams teams client sdk javascript reference preview beta v2
---
# Microsoft Teams JavaScript client SDK v2 Preview

The Microsoft Teams JavaScript client SDK v2 Preview is a refactor of the existing Teams SDK (@microsoft/teams-js, or simply TeamsJS) that enables Teams developers the ability to extend Teams apps to run in Outlook and Office. From a functional perspective, the TeamsJS SDK v2 Preview (@microsoft/teams-js@next) is a superset of the current TeamsJS SDK, it supports existing Teams app functionality while adding the ability to host Teams apps in Outlook and Office.

You can find the latest on the Microsoft Teams platform from the [Microsoft 365 Developer Blog](https://devblogs.microsoft.com/microsoft365dev/category/teams/) and also learn more about the [changes coming with the SDK v2 Preview](/microsoftteams/platform/m365-apps/using-teams-client-sdk-preview).

## Finding the SDK

The Teams client v2 SDK Preview is distributed as an npm package. You can find the latest version of the v2 SDK Preview using the `next` tag:

https://www.npmjs.com/package/@microsoft/teams-js.

## Installing the SDK

You can install the package using npm or yarn:

* `npm install --save @microsoft/teams-js@next`
* `yarn add @microsoft/teams-js@next`

## Using the SDK

If you are using any dependency loader or module bundler such as [RequireJS](http://requirejs.org/), [SystemJS](https://github.com/systemjs/systemjs), [browserify](http://browserify.org/), or [webpack](https://webpack.github.io/), you can use `import` syntax to import specific modules. For example:

```typescript
import * as microsoftTeams from "@microsoft/teams-js@next";
```

You can also reference the entire library in html pages using a script tag.  There are three ways to do this:

> [!IMPORTANT]
> Do not copy/paste these `<script src=...` URLs from this page; they refer to a specific version of the SDK. To get the `<script src=...></script>` markup for the latest version, always go to https://www.npmjs.com/package/@microsoft/teams-js.

```html
<!-- Microsoft Teams JavaScript API (via CDN) -->
<script
  src="https://res.cdn.office.net/teams-js/2.0.0-beta.2/js/MicrosoftTeams.min.js"
  integrity="sha384-Q2Z9S56exI6Oz/ThvYaV0SUn8j4HwS8BveGPmuwLXe4CvCUEGlL80qSzHMnvGqee"
  crossorigin="anonymous"
></script>

<!-- Microsoft Teams JavaScript API (via npm) -->
<script src="node_modules/@microsoft/teams-js@2.0.0-beta.2/dist/MicrosoftTeams.min.js"></script>

<!-- Microsoft Teams JavaScript API (via local) -->
<script src="MicrosoftTeams.min.js"></script>
```

The final option, using a local copy on your servers, eliminates that dependency but requires hosting and updating a local copy of the SDK.

> [!TIP]
> If you are a TypeScript developer it is helpful to install the NPM package as described [above](#installing-the-sdk), even if you don't link to the copy of `MicrosoftTeams.min.js` in `node_modules` from your HTML, because IDEs such as Visual Studio Code will use it for Intellisense and type checking.

## Reference

The following sections contain reference pages for all the elements of the Teams client SDK v2 Preview. These pages are auto-generated from the source found in the npm module on https://www.npmjs.com/package/@microsoft/teams-js@next. The source code for the v2 SDK Preview is located at https://github.com/OfficeDev/microsoft-teams-library-js/tree/2.0-preview.
