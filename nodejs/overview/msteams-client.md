---
title: Microsoft Teams SDK reference
description: Reference documentation for Microsoft Teams SDK
ms.date: 01/03/2023
ms.topic: reference
keywords: msteams live-share teamsfx teams client sdk javascript library reference latest
---
# Microsoft Teams SDK reference

There are a number of JavaScript/TypeScript libraries available to support various aspects of Teams app development. This article provides an overview of each, along with basic installation instructions.
 
| Library | Description | API reference |
|-|-|-|
| **Live Share** | Live Share transforms the Microsoft 365 platforms to be more a collaborative experience without writing any dedicated back-end code | [Live Share](../docs-ref-autogen/%40microsoft/live-share/index.yml)<br/><br/>[Live Share canvas](../docs-ref-autogen/%40microsoft/live-share-canvas/index.yml)<br/><br/>[Live Share media](../docs-ref-autogen/%40microsoft/live-share-media/index.yml) |
| **TeamsJs** | TeamsJS client library enables developers to create app content hosted in [IFrame](https://developer.mozilla.org/docs/Web/HTML/Element/iframe) across the Microsoft 365 ecosystem | [TeamsJS ](../docs-ref-autogen/%40microsoft/teams-js/index.yml) |
| **TeamsFx** | TeamsFx helps to reduce tasks by using Microsoft Teams single sign-on (SSO) and accessing cloud resources down to single line statements with little configuration | [Teamsfx](../docs-ref-autogen/%40microsoft/teamsfx/index.yml) |

## Microsoft Teams Live Share

The [Live Share SDK](https://github.com/microsoft/live-share-sdk) is compromised of three sub-packages with features to help developers create more collaborative moments across Microsoft Teams. Live Share (or sometimes called Live Share core) is for connecting to Fluid Framework through `sidePanel` and `meetingStage` for in meeting pop-up cards. Live Share media allows for media synchronization for HTML `<video>` and `<audio>` elements; which are beneficial for presenting video and audio is a Teams session. Live Share canvas adds annotation tools for whiteboard and PowerPoint presentations. 

### Finding the library

The Live Share SDK is a JavaScript package comprised of three sub-packages ([Live Share](/msteams-docs/msteams-platform/apps-in-teams-meetings/teams-live-share-capabilities.md), [Live Share media](/msteams-docs/msteams-platform/apps-in-teams-meetings/teams-live-share-media-capabilities.md), and [Live Share canvas](/msteams-docs/msteams-platform/apps-in-teams-meetings/teams-live-share-canvas.md)) which are published on npm and can be installed using npm or yarn.

To install the latest version of the Live Share packages to your application:

#### Live Share core

The Live Share SDK can be added to your meeting extension's sidePanel and meetingStage contexts with minimal effort to unlock new collaborative app scenarios throughout the lifecycle of a meeting. For more, see [Live Share core capabilities](/msteams-docs/msteams-platform/apps-in-teams-meetings/teams-live-share-capabilities.md).

# [NPM](#tab/npm)

```bash
npm install @microsoft/live-share@next --save
```
# [Yarn](#tab/yarn)

To install using yarn
```bash
yarn add @microsoft/live-share@next
```

---

#### Live Share media

The Live Share SDK enables robust media synchronization for any HTML <video> and <audio> element with just a few lines of code. By synchronizing media at the player state and transport controls layer, you can individually attribute views and license, while providing the highest possible quality available through your app. For more, see [Live Share media capabilities](/msteams-docs/msteams-platform/apps-in-teams-meetings/teams-live-share-media-capabilities.md).

# [NPM](#tab/npm)

```bash
npm install @microsoft/live-share@next --save
npm install @microsoft/live-share-media@next --save
```
# [Yarn](#tab/yarn)

```bash
yarn add @microsoft/live-share@next
yarn add @microsoft/live-share-media@next
```

---

#### Live Share canvas

Using Live Share canvas, your app can bring the power of [PowerPoint Live](https://support.microsoft.com/en-us/office/present-from-powerpoint-live-in-microsoft-teams-28b20e74-7165-499c-9bd4-0ad975d448ad) inking tools with minimal effort. For more, see [Live Share canvas overview](/msteams-docs/msteams-platform/apps-in-teams-meetings/teams-live-share-canvas.md).

# [NPM](#tab/npm)

```bash
npm install @microsoft/live-share@next --save
npm install @microsoft/live-share-canvas@next --save
```
# [Yarn](#tab/yarn)

```bash
yarn add @microsoft/live-share@next
yarn add @microsoft/live-share-canvas@next
```

---

## Microsoft Teams JS client library

With the Microsoft TeamsJS client library version `2.x.x` developers can [run apps across Microsoft 365](/microsoftteams/platform/m365-apps/overview). Developers can deliver a cross-platform app to a broader user base from a single codebase, creating a streamlined experience for app users and consolidating development resources for developers. The TeamsJS SDK is a superset of TeamsJS `1.x` versions: and supports existing Teams app functionality while adding the ability to host Teams apps in Outlook and Microsoft 365. Refer to the [TeamsJS client library](/microsoftteams/platform/tabs/how-to/using-teams-client-library) overview for guidance on building Microsoft 365-enabled apps.

### Finding the library

The TeamsJS client is distributed as an [npm package](https://npmjs.com/package/@microsoft/teams-js/) and can be installed using npm or yarn.

To install using npm

  ```bash
npm install --save @microsoft/teams-js
  ```
OR

To install using yarn

```bash
yarn add @microsoft/teams-js
```
## Microsoft Teams Fx library

The [TeamsFx SDK](/msteams-docs/msteams-platform/toolkit/TeamsFx-SDK.md) helps to reduce tasks by using Microsoft Teams single sign-on (SSO) and accessing cloud resources down to single line statements with little configuration.

### Finding the library

The TeamsFx client is distributed as an [npm package](https://npmjs.com/package/@microsoft/teams-js/) for Typescript and JavaScript.

To install using npm

```bash
npm install @microsoft/teamsfx
```