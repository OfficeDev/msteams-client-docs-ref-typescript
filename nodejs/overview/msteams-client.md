---
title: Microsoft Teams SDK reference
description: Reference documentation for Microsoft Teams SDK
ms.date: 01/03/2023
ms.topic: reference
keywords: msteams live-share teamsfx teams client sdk javascript library reference latest
---
# Microsoft Teams SDK reference

This page contains general information about library's to support you in the development of using The Microsoft Teams SDK.

| Library | Description | APIs |
|-|-|-|
| **Live Share** | Live Share transforms the Microsoft 365 platforms to be more a collaborative experience without writing any dedicated back-end code | [Live Share](../docs-ref-autogen/%40microsoft/live-share/index.yml)<br/><br/>[Live Share canvas](../docs-ref-autogen/%40microsoft/live-share-canvas/index.yml)<br/><br/>[Live Share media](../docs-ref-autogen/%40microsoft/live-share-media/index.yml) |
| **TeamsJs** | Teams Java script client library enables developers to create app content hosted in [IFrame](https://developer.mozilla.org/docs/Web/HTML/Element/iframe) across the Microsoft 365 ecosystem | [TeamsJS ](../docs-ref-autogen/%40microsoft/teams-js/index.yml) |
| **TeamsFx** | TeamsFx helps to reduce tasks by using Microsoft Teams single sign-on (SSO) and accessing cloud resources down to single line statements with little configuration | [Teamsfx](../docs-ref-autogen/%40microsoft/teamsfx/index.yml) |

## Microsoft Teams Live Share

The [Live Share SDK](https://github.com/microsoft/live-share-sdk) is compromised of three sub-packages enabled to allow for more collaborative moments across Microsoft Teams. The Live Share (or sometimes called Live Share core) package enables connecting to Fluid Framework through `sidePanel` and `meetingStage` for in meeting pop-up cards. The Live Share media package allows for media synchronization for HTML `<video>` and `<audio>` elements and are beneficial for presenting video and audio is a Teams session. Live Share canvas adds annotation tools for whiteboard and PowerPoint presentations. 

### Finding the library

The Live Share SDK is a JavaScript package comprised of three sub-packages ([Live Share](/msteams-docs/msteams-platform/apps-in-teams-meetings/teams-live-share-capabilities.md), [Live Share media](/msteams-docs/msteams-platform/apps-in-teams-meetings/teams-live-share-media-capabilities.md), and [Live Share canvas](/msteams-docs/msteams-platform/apps-in-teams-meetings/teams-live-share-canvas.md)) which are published on npm and can be installed using npm or yarn.

#### Live Share

To install the latest version of the Live Share package to your application:

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
To install the latest version of the Live Share media package to your application:

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

To install the latest version of the Live Share media package to your application:

# [NPM](#tab/yarn)

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

## Microsoft Teams JavaScript client library

The Microsoft Teams JavaScript client library version `2.x.x` is enabled to [run apps across Microsoft 365](/microsoftteams/platform/m365-apps/overview). The TeamsJS SDK is a superset of TeamsJS `1.x` versions: and supports existing Teams app functionality while adding the ability to host Teams apps in Outlook and Microsoft 365. Refer to the [Teams JavaScript client library](/microsoftteams/platform/tabs/how-to/using-teams-client-library) overview for guidance on building Microsoft 365-enabled apps.

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