---
title: "Device Support"
description: "Detailed information about passkey support across devices and ecosystems"
layout: minimal
type: minimal
---

This page, along with the rest of passkeys.dev, is targeted at relying party developers and is not intended to be an end user facing resource.

> Said differently, **please don’t link to this page from end user focused resources** 😉

## Overview

Support for passkeys is currently rolling out across major operating systems and browsers. This page will be updated as the ecosystem evolves. The [matrix below](#matrix) maps out the various features that support the passkey experience. Additional information about each platform is available in the [Reference section of Docs](/docs/reference/android).

Passkeys created in **iOS or iPadOS** can be used on:

- The same iPhone or iPad
- iPhones and iPads using the same Apple ID (synced automatically)
- Macs using the same Apple ID (synced automatically)
- Macs using [FIDO Cross-Device Authentication](/docs/reference/terms/#cross-device-authentication-cda)
- Windows devices using [FIDO Cross-Device Authentication](/docs/reference/terms/#cross-device-authentication-cda)
- Chromebooks and other ChromeOS devices using [FIDO Cross-Device Authentication](/docs/reference/terms/#cross-device-authentication-cda)
- Ubuntu devices in Edge and Chrome using [FIDO Cross-Device Authentication](/docs/reference/terms/#cross-device-authentication-cda)

Passkeys created in **Android** can be used on:

- The same Android device
- Android devices using the same Google account (synced automatically)
- Macs using [FIDO Cross-Device Authentication](/docs/reference/terms/#cross-device-authentication-cda)
- Windows devices using [FIDO Cross-Device Authentication](/docs/reference/terms/#cross-device-authentication-cda)
- iPhones and iPads using [FIDO Cross-Device Authentication](/docs/reference/terms/#cross-device-authentication-cda)
- Chromebooks and other ChromeOS devices using [FIDO Cross-Device Authentication](/docs/reference/terms/#cross-device-authentication-cda)
- Ubuntu devices in Edge and Chrome using [FIDO Cross-Device Authentication](/docs/reference/terms/#cross-device-authentication-cda)

Passkeys created in **macOS** can be used on:

- Macs using the same Apple ID (synced automatically)
- iPhones and iPads using the same Apple ID (synced automatically)
  - Passkeys created on a Mac and synced to an iPhone and/or iPad via iCloud Keychain can be used in all the places listed above under "iOS or iPadOS"

[Device-bound passkeys](/docs/reference/terms/#device-bound-passkey) created in **Windows** can be used on:

- the same Windows device that created them