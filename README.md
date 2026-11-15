# Harbordex Privacy Policy

Published by R6T LABS LLC (R6TLabs). Last updated: November 14, 2026.

This policy covers Harbordex for Android, package `com.r6tlabs.harbordex`.

## Your connected computer

Harbordex is a companion to a Harbordex Device running on a computer or server you choose. R6TLabs does not provide a hosted coding-agent backend as part of this app. The app sends your requests to your connected Device and displays the results it returns. Your Device, the coding agents you configure, and any external services you choose process that content under their own settings and policies.

## Content and connection information

Depending on the features you use, the app transmits prompts, commands, review comments, file-search queries, remote-browser URLs and interactions, selected files, photos or videos, optional credentials or secret-request responses, and other content you submit to your connected Device. The Device can forward requests to the agents, model providers, source-control services, and other tools you have configured there. Connection and session identifiers are used to authenticate and operate the connection.

Pairing credentials and app preferences are stored on your phone. The app also keeps local state and cached content needed to display your workspace. Your connected Device stores its own project and conversation data. We do not receive that workspace content through a R6TLabs-hosted relay or analytics service as part of the standard direct-connection workflow.

## Optional dictation

The Android release being prepared for Google Play uses Android’s on-device speech-recognition API on supported Android 13+ devices. Harbordex supplies audio from your selected microphone to the on-device recognizer and does not fall back to a network recognizer. The Android speech service manages language-model availability and downloads under its own privacy controls and terms.

If you select transcription on a connected Device or through a cloud provider, the app requests your consent before sending audio to that destination. The destination and its configured provider handle that audio according to their own policies. Dictation is optional. Your keyboard’s voice typing is a separate operating-system feature.

Earlier internal Android test builds used Google’s ML Kit GenAI speech SDK. That SDK processed input audio on the phone but sent technical metrics to Google, including device and app information, identifiers, performance, feature configuration and version, sizes, feature events and errors, and configured languages. Those SDK disclosures apply to those older test builds. See [Google’s ML Kit privacy information](https://developers.google.com/ml-kit/terms) and [Android data disclosures](https://developers.google.com/ml-kit/android-data-disclosure).

## Optional provider feedback

If you use the Codex `/feedback` command in a Codex thread, the connected Device sends your reason, thread reference, and logs through Codex to OpenAI. This is an optional, user-initiated provider feedback action, separate from contacting R6TLabs.

## Permissions and optional background notifications

Camera access supports QR pairing and camera attachments. Microphone access supports dictation. File and media pickers let you select attachments. Notification permission supports agent activity notifications.

If you enable continuous background notifications, Harbordex uses an Android foreground service to listen for activity from the private Device you paired. Android displays an ongoing notification with a Stop action. This feature uses your connection to the Device rather than a R6TLabs-hosted push relay.

## Security of connections

HTTPS and appropriately configured Tailscale connections can protect traffic in transit. Harbordex also supports plain HTTP and WebSocket connections for user-controlled networks. Do not assume that every connection is encrypted; use an encrypted route when handling private information. The security and availability of your connected Device and providers also depend on their configuration.

## Deleting data and disconnecting

Use the app's connection controls to disconnect a Device, and revoke the phone's authorization from that Device when needed. Android's Clear storage controls remove the app's local data. Delete project files and conversation data on the Device where they are stored, and manage data held by your chosen providers with those providers. R6TLabs cannot directly delete content held on computers or provider accounts you control.

If you contact us for support, we receive the information you choose to send and use it to respond to your request. We retain that correspondence for as long as needed to resolve the request and meet applicable legal obligations. Contact us if you have questions about information you have supplied directly to us.

## Advertising, accounts, and children

Harbordex does not include advertising or a R6TLabs app-account sign-up. Your coding-agent and model subscriptions, if any, are managed with their providers.

Harbordex is designed for developer workflows and is not directed to children under 13.

## Changes and contact

We may update this policy when the app's practices change. The updated date will appear here.

R6T LABS LLC — team@r6tlabs.com
