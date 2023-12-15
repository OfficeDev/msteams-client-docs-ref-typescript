---
title: Microsoft Teams SDK reference
description: Reference documentation for Microsoft Teams SDK
ms.date: 02/03/2023
ms.topic: reference
keywords: sdk msteams live-share teamsfx teams client javascript library reference latest
---
# Microsoft Teams SDK reference

There are several libraries available to support various aspects of Teams app development. This article provides an overview of each, along with basic installation instructions.
 
| Library | Description | API reference |
|-|-|-|
| **Live Share SDK** | Live Share enables collaborative app experiences | [Live Share](../docs-ref-autogen/%40microsoft/live-share/index.yml)<br/><br/>[Live Share canvas](../docs-ref-autogen/%40microsoft/live-share-canvas/index.yml)<br/><br/>[Live Share media](../docs-ref-autogen/%40microsoft/live-share-media/index.yml) |
| **TeamsJS library** | Teams JavaScript client library enables you to create hosted experiences in Teams, Outlook, and the Microsoft 365 app | [TeamsJS ](../docs-ref-autogen/%40microsoft/teams-js/index.yml) |
| **TeamsFx SDK** | TeamsFx helps to reduce tasks by using Microsoft Teams single sign-on (SSO) and accessing cloud resources down to single line statements with little configuration | [Teamsfx](../docs-ref-autogen/%40microsoft/teamsfx/index.yml) |

## Microsoft Teams Live Share

The [Live Share SDK](https://github.com/microsoft/live-share-sdk) is compromised of three sub-packages with features to help developers create more collaborative moments across Microsoft Teams. Live Share (sometimes called *Live Share core*) is for connecting to Fluid Framework through `sidePanel` and `meetingStage` for in meeting pop-up cards. *Live Share media* allows for media synchronization of video and audio during a Teams session. *Live Share canvas* adds annotation tools for whiteboard and PowerPoint presentations. 

### Finding the library

The Live Share SDK is a JavaScript package comprised of three sub-packages ([Live Share](/microsoftteams/platform/apps-in-teams-meetings/teams-live-share-capabilities), [Live Share media](/microsoftteams/platform/apps-in-teams-meetings/teams-live-share-media-capabilities), and [Live Share canvas](/microsoftteams/platform/apps-in-teams-meetings/teams-live-share-canvas)) which are published on npm and can be installed using npm or yarn.

To install the latest version of the Live Share packages to your application:

#### Live Share core

The Live Share SDK can be added to your meeting extension's `sidePanel` and `meetingStage` contexts with minimal effort to unlock new collaborative app scenarios throughout the lifecycle of a meeting. For more, see [Live Share core capabilities](/microsoftteams/platform/apps-in-teams-meetings/teams-live-share-capabilities).

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

The Live Share SDK enables robust media synchronization for any HTML `<video>` and `<audio>` element with just a few lines of code. By synchronizing media at the player state and transport controls layer, you can individually attribute views and license, while providing the highest possible quality available through your app. For more, see [Live Share media capabilities](/microsoftteams/platform/apps-in-teams-meetings/teams-live-share-media-capabilities).

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

Using Live Share canvas, your app can bring the power of [PowerPoint Live](https://support.microsoft.com/office/present-from-powerpoint-live-in-microsoft-teams-28b20e74-7165-499c-9bd4-0ad975d448ad) inking tools with minimal effort. For more, see [Live Share canvas overview](/microsoftteams/platform/apps-in-teams-meetings/teams-live-share-canvas).

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

## Microsoft Teams JavaScript client library

With the latest Microsoft TeamsJS client library, your Teams app can [run across Microsoft 365](/microsoftteams/platform/m365-apps/overview), including Outlook and the Microsoft 365 app. With TeamsJS you can deliver a cross-platform app to more users from a single codebase, and a more streamlined experience for your customers. The TeamsJS v.2.x.x SDK is a superset of TeamsJS `1.x` versions; it supports existing Teams app functionality while adding the ability to host Teams apps in Outlook and Microsoft 365 app. Refer to the [TeamsJS client library](/microsoftteams/platform/tabs/how-to/using-teams-client-library) overview for guidance on building Microsoft 365-enabled apps.

### Finding the library

The TeamsJS client is distributed as an [npm package](https://npmjs.com/package/@microsoft/teams-js/) and can be installed using npm or yarn. It can also be referenced from its CDN endpoint.

# [NPM](#tab/npm)

  ```bash
npm install --save @microsoft/teams-js
  ```

# [Yarn](#tab/yarn)

```bash
yarn add @microsoft/teams-js
```

---

#### CDN
TeamsJS can also be referenced from its CDN endpoints:

```javascript
<!-- Microsoft Teams JavaScript API (via CDN) -->
<script
  src="https://res.cdn.office.net/teams-js/2.18.0/js/MicrosoftTeams.min.js"
  integrity="sha384-g8DoRkiR0ECQ9rwKIgY8GjQ5h0d2jp1347CmU/IRlyUHPjJZiFWEOYc+hFtT9MGL"
  crossorigin="anonymous"
></script>

<!-- Microsoft Teams JavaScript API (via npm) -->
<script src="node_modules/@microsoft/teams-js@2.18.0/dist/MicrosoftTeams.min.js"></script>

<!-- Microsoft Teams JavaScript API (via local) -->
<script src="MicrosoftTeams.min.js"></script>
```

## Microsoft TeamsFx SDK

The [TeamsFx SDK](/microsoftteams/platform/toolkit/teamsfx-sdk) greatly simplifies Microsoft Teams single sign-on (SSO) and cloud resource access in your app.

### Finding the library

The TeamsFx client is distributed as an [npm package](https://npmjs.com/package/@microsoft/teams-js/) for Typescript and JavaScript.

# [NPM](#tab/npm)

```bash
npm install @microsoft/teamsfx
```

# [Yarn](#tab/yarn)

```bash
yarn add @microsoft/teamsfx
```

---
