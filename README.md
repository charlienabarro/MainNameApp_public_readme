# MainName — Social Identity and Discovery App

A mobile-app prototype exploring how people can share different parts of their social identity in different contexts.

## Project overview

MainName combines profile creation, selectable identities, social-account links and discovery screens. The idea is to let someone choose which version of their profile to share when meeting people at an event, on campus or through a social plan.

## Implemented prototype features

- Profile onboarding and editing with locally stored profile data.
- Multiple identities with selected social links.
- Profile previews and user-search screens.
- Connection-request and identity-sharing flows.
- Map-based discovery screens with location permissions, group selection and illustrative nearby users.
- Identity-specific QR-code generation, link copying and native sharing.
- Navigation and deep-link routing between app screens.

## Tech stack

| Area | Technologies |
| --- | --- |
| Language | TypeScript |
| UI | React, React Native |
| App framework | Expo |
| Navigation | React Navigation |
| Local persistence | AsyncStorage |
| Location and maps | Expo Location, react-native-maps |
| Sharing and QR codes | Expo Linking, Expo Clipboard, react-native-qrcode-svg |

## Status and scope

Interactive prototype using mock users and local/in-memory state for several flows. The map illustrates discovery behaviour; it is not a production service tracking other users. Camera-based QR scanning is planned rather than implemented.

## Skills demonstrated

Reusable mobile UI, typed navigation, local persistence, state management, location integration, QR generation and designing context-sensitive sharing flows.

## About this repository

This public repository contains only a project overview. App source code, assets and original commit history remain private.
