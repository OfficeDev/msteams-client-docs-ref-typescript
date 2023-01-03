---
title: Microsoft Teams Client API reference
description: Reference documentation for the latest Microsoft Teams JavaScript client library
ms.date: 01/03/2023
ms.topic: reference
keywords: msteams live-share teamsfx teams client sdk javascript library reference latest
---
# Microsoft Teams Client API reference

This page contains general information about the client library to support you in the development of using The Microsoft Teams Client SDK.

| Library | Description | APIs |
|-|-|-|
| **Live Share** | Live Share transforms the Microsoft 365 platforms to be more a collaborative experience without writing any dedicated back-end code | [Live Share](../docs-ref-autogen/%40microsoft/live-share/index.yml)<br/><br/>[Live Share canvas](../docs-ref-autogen/%40microsoft/live-share-canvas/index.yml)<br/><br/>[Live Share media](../docs-ref-autogen/%40microsoft/live-share-media/index.yml) |
| **TeamsJS** | Teams Java script client library enables developers to create app content hosted in [IFrame](https://developer.mozilla.org/docs/Web/HTML/Element/iframe) across the Microsoft 365 ecosystem | [TeamsJS ](../docs-ref-autogen/%40microsoft/teams-js/index.yml) |
| **TeamsFx** | TeamsFx helps to reduce tasks by using Microsoft Teams single sign-on (SSO) and accessing cloud resources down to single line statements with little configuration | [Teamsfx](../docs-ref-autogen/%40microsoft/teamsfx/index.yml) |

## Microsoft Teams Live Share

The [Live share SDK]( https://github.com/microsoft/live-share-sdk) is enabled to allow for collaborative moments across Microsoft Teams through `sidePanel` and `meetingStage`, media synchronization for HTML `<video>` and `<audio>` elements, and annotation tools for whiteboard and PowerPoint presentations. 

### Finding the library

The Live share SDK is a JavaScript package comprised of three sub-packages ([Live Share](msteams-docs/msteams-platform/apps-in-teams-meetings/teams-live-share-capabilities.md), [Live Share media](msteams-docs/msteams-platform/apps-in-teams-meetings/teams-live-share-media-capabilities.md), and [Live Share canvas](msteams-docs/msteams-platform/apps-in-teams-meetings/teams-live-share-canvas.md)) which is published on npm and can be installed using npm or yarn.

#### Live share

To install the latest version of the Live share package to your application:

To install using npm

```bash
npm install @microsoft/live-share@next --save
```
OR

To install using yarn
```bash
yarn add @microsoft/live-share@next
```

#### Live Share media
To install the latest version of the Live Share media package to your application:

To install using npm

```bash
npm install @microsoft/live-share@next --save
npm install @microsoft/live-share-media@next --save
```
OR

To install using yarn

```bash
yarn add @microsoft/live-share@next
yarn add @microsoft/live-share-media@next
```

#### Live Share canvas

To install the latest version of the Live Share media package to your application:

To install using npm

```bash
npm install @microsoft/live-share@next --save
npm install @microsoft/live-share-canvas@next --save
```
OR

To install using yarn

```bash
yarn add @microsoft/live-share@next
yarn add @microsoft/live-share-canvas@next
```

## Microsoft Teams JavaScript client library

The Microsoft Teams JavaScript client library version `2.x.x` is enabled [run apps across Microsoft 365](/microsoftteams/platform/m365-apps/overview). The TeamsJS SDK is a superset of TeamsJS `1.x` versions: and supports existing Teams app functionality while adding the ability to host Teams apps in Outlook and Microsoft 365. Refer to the [Teams JavaScript client library](/microsoftteams/platform/tabs/how-to/using-teams-client-library) overview for guidance on building Microsoft 365-enabled apps.

### Finding the library

The TeamsJS client is distributed as an [npm package](www.npmjs.com/package/@microsoft/teams-js) and can be installed using npm or yarn.

To install using npm

  ```bash
npm install --save @microsoft/teams-js
  ```
OR

To install using yarn

```bash
yarn add @microsoft/teams-js`
```
## Microsoft Teams Fx library

The [TeamsFx SDK](msteams-docs/msteams-platform/toolkit/TeamsFx-SDK.md) helps to reduce tasks by using Microsoft Teams single sign-on (SSO) and accessing cloud resources down to single line statements with little configuration.

### Finding the library

The TeamsFx client is distributed as an [npm package](www.npmjs.com/package/@microsoft/teams-js) for Typescript and JavaScript.

To install using npm

```bash
npm install @microsoft/teamsfx
```