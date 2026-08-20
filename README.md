<!-- badges -->

<div align="center">

<!-- title -->

<!--lint ignore no-dead-urls-->

# Awesome Firebase with stars

<!-- subtitle -->

The most **up to date** list of Firebase docs, talks, tools, examples & articles the internet has to offer.

<!-- image -->

<a href="https://firebase.google.com/docs/" target="_blank" rel="noopener noreferrer">
  <img src="images/firebase-services.gif" />
</a>

<!-- translations -->

Translations: [🇬🇧 en](readme.md) · [🇰🇷 ko](readme-ko.md) · [🇷🇺 ru](readme-ru.md) <!-- · [🇪🇸 es](readme-es.md) · [🇮🇩 id](readme-id.md) · [🇯🇵 ja](readme-ja.md) · [🇵🇹 pt](readme-pt.md) · [🇨🇳 zh](readme-zh.md) -->

[Firebase](https://firebase.google.com) is an app dev platform built on the [Google Cloud Platform](https://cloud.google.com/products) providing services and cross-platform SDKs!

</div>

<!-- toc -->

## Contents

* [Featured (new releases)](#featured-new-releases)
* [Official Docs & Quickstarts](#official-docs--quickstarts)
* [Firebase Extensions](#firebase-extensions)
* [Web](#web)
* [Mobile](#mobile)
* [Games](#games)
* [Server-side (Cloud Functions, BigQuery etc)](#server-side-cloud-functions-bigquery-etc)
* [CLI & Editor](#cli--editor)
* [Other](#other)
* [Follow](#follow)

**Legend**: 📝 blog posts · 💡 examples · 📖 docs · 🔌 libraries · 🔧 tools · 📹 talks/video · 🔊 podcasts

<!-- START content -->

## Featured (new releases)

* 🔧 [(Unofficial) Firebase Admin SDK for PHP](https://github.com/kreait/firebase-php) ⭐ 2,435 | 🐛 19 | 🌐 PHP | 📅 2026-08-17 - The Firebase Admin PHP SDK enables access to Firebase services from privileged environments (such as servers or cloud) in PHP.
* 📖 [App Check](https://firebase.google.com/docs/app-check) - Protect your backend resources from abuse, such as billing fraud or phishing.
* 📖 [Firestore Data Bundles](https://firebase.google.com/docs/firestore/bundles) - Data Bundles are static query results for CDN caching to speed first page loads.
* 📖 [Modular Web SDK (v9)](https://firebase.google.com/docs/web/learn-more#modular-version) - Import only what you need reducing SDK size up to 80%.

## Official Docs & Quickstarts

* 📖 [Firebase Documentation](https://firebase.google.com/docs) - Official Firebase Documentation.
* 🔧 [Firebase Status Dashboard](https://status.firebase.google.com) - This page provides status information on the services that are part of Firebase.
* 💡 [Firebase Quickstarts](https://github.com/firebase?utf8=%E2%9C%93\&q=quickstart\&type=\&language=) - Official Firebase Quickstarts.
* 💡 [Google Codelabs | Firebase](https://codelabs.developers.google.com/?cat=Firebase) - Google Developers Codelabs provide a guided, tutorial, hands-on coding experience.
* 📖 [Firebase for Games](https://firebase.google.com/games) - New Firebase for Games landing page with links to Firebase/Google resources for game developers.

## Firebase Extensions

* 🔧 [Stripe Extensions](https://github.com/stripe/stripe-firebase-extensions) ⚠️ Archived - Official Stripe subscriptions and invoices extensions.
* 🔧 [Experimental Firebase Extensions](https://github.com/FirebaseExtended/experimental-extensions) ⚠️ Archived -  laboratory for new extensions created by Firebase.
* 🔧 [Typesense Extension for Full-Text Search](https://github.com/typesense/firestore-typesense-search) ⭐ 182 | 🐛 23 | 🌐 JavaScript | 📅 2026-05-14 - Official Typesense extension to add full-text search in Firestore, by syncing the data to [Typesense](https://github.com/typesense/typesense) ⭐ 26,454 | 🐛 868 | 🌐 C++ | 📅 2026-08-18, an OSS alternative to Algolia.
* 🔧 [Algolia Extensions](https://github.com/algolia/firestore-algolia-search) ⭐ 123 | 🐛 36 | 🌐 TypeScript | 📅 2026-07-07 - Official Algolia extension to enable full text search of Cloud Firestore with Algolia.
* 🔧 [Mailchimp Extensions](https://github.com/mailchimp/Firebase) ⭐ 21 | 🐛 17 | 🌐 JavaScript | 📅 2024-01-24 - Official Mailchimp extension to sync Firebase Authentication events to create member tags, merge fields, and member events with Mailchimp.
* 🔧 [MessageBird Extensions](https://github.com/messagebird/firestore-send-msg) ⭐ 12 | 🐛 11 | 🌐 TypeScript | 📅 2024-04-26 - Official MessageBird extension to send messages via the MessageBird Converstations API.
* 🔧 [Firebase Extensions](https://firebase.google.com/products/extensions) - Firebase Extensions provide extended functionality to your apps without the need to research, write, or debug code on your own.

## Web

* 🔌 [Angular Fire 2](https://github.com/angular/angularfire2) ⭐ 7,806 | 🐛 194 | 🌐 TypeScript | 📅 2026-08-18 - Official library for Firebase and Angular.
* 🔌 [Firebase UI](https://github.com/firebase/firebaseui-web) ⭐ 4,874 | 🐛 11 | 🌐 TypeScript | 📅 2026-08-18 - FirebaseUI is an open-source JavaScript library for Web that provides simple, customizable UI bindings on top of Firebase SDKs to eliminate boilerplate code and promote best practices.
* 🔌 [VueFire](https://github.com/vuejs/vuefire) ⭐ 3,908 | 🐛 46 | 🌐 TypeScript | 📅 2026-04-15 - Firebase bindings for Vue.js.
* 💡 [FirePad](https://github.com/FirebaseExtended/firepad) ⚠️ Archived - Collaborative Text Editor Powered by Firebase.
* 🔌 [React Firebase Hooks](https://github.com/CSFrequency/react-firebase-hooks) ⭐ 3,634 | 🐛 43 | 🌐 TypeScript | 📅 2024-04-22 - React Hooks for Firebase services.
* 🔌 [React Fire](https://github.com/FirebaseExtended/reactfire) ⭐ 3,571 | 🐛 47 | 🌐 TypeScript | 📅 2026-08-19 - Official Firebase React library with Hooks, Context Providers, and Components that make it easy to interact with Firebase.
* 🔌 [React Redux Firebase](https://github.com/prescottprue/react-redux-firebase) ⭐ 2,533 | 🐛 133 | 🌐 JavaScript | 📅 2026-08-18 - Redux bindings for Firebase. Includes Higher Order Component for use with React.
* 🔌 [Re-base](https://github.com/tylermcginnis/re-base) ⭐ 2,102 | 🐛 22 | 🌐 JavaScript | 📅 2018-07-23 - Relay inspired library for building React.js + Firebase applications.
* 🔌 [firebase-kotlin-sdk](https://github.com/GitLiveApp/firebase-kotlin-sdk/) ⭐ 1,716 | 🐛 118 | 🌐 Kotlin | 📅 2026-08-17 - Kotlin-first SDK for Firebase supporting multiplatform projects (`ios`, `android` & `js`).
* 🔌 [SvelteFire](https://github.com/codediodeio/sveltefire) ⭐ 1,660 | 🐛 68 | 🌐 TypeScript | 📅 2024-07-25 - Cybernetically enhanced Firebase apps.
* 🔌 [GeoFire for JavaScript](https://github.com/firebase/geofire-js) ⭐ 1,447 | 🐛 68 | 🌐 TypeScript | 📅 2026-05-28 - Realtime location queries with Firebase.
* 🔌 [Firebase UI for React](https://github.com/firebase/firebaseui-web-react) ⭐ 1,291 | 🐛 101 | 🌐 JavaScript | 📅 2026-06-21 - React Wrapper for firebaseUI Web.
* 💡 [Angular Firebase PWA](https://github.com/codediodeio/angular-firestarter) ⭐ 961 | 🐛 45 | 🌐 TypeScript | 📅 2023-01-07 - Is an Angular PWA powered by Firebase. It can serve as a foundation to learn this stack and roll out more complex features.
* 🔌 [Ember Fire](https://github.com/firebase/emberFire) ⚠️ Archived - Official Ember data adapter for Firebase.
* 🔌 [GeoFirestore](https://github.com/MichaelSolati/geofirestore-js) ⭐ 507 | 🐛 12 | 🌐 TypeScript | 📅 2026-02-18 - Location-based querying and filtering using Firebase Firestore.
* 🔌 [PolymerFire](https://github.com/FirebaseExtended/polymerfire) ⚠️ Archived - Polymer Web Components for Firebase.
* 🔧 [Typesaurus](https://github.com/kossnocorp/typesaurus) ⭐ 443 | 🐛 32 | 🌐 TypeScript | 📅 2024-06-30 - Type-safe TypeScript-first ODM for Firestore.
* 🔌 [Firebase Dart](https://github.com/FirebaseExtended/firebase-dart) ⚠️ Archived - Dart wrapper for Firebase.
* 🔌 [Apollo Link Firebase](https://github.com/Canner/apollo-link-firebase) ⚠️ Archived - Provides a local GraphQL interface to RealtimeDB. DB syncs locally to device, Apollo Link provides querying into the local DB.
* 🔌 [Firestorter](https://github.com/IjzerenHein/firestorter) ⭐ 378 | 🐛 23 | 🌐 TypeScript | 📅 2025-02-07 - Use Firestore in React with zero effort, using MobX (also for react-native).
* 🔌 [FireSQL](https://github.com/jsayol/FireSQL) ⭐ 347 | 🐛 21 | 🌐 TypeScript | 📅 2021-05-10 - Query Firestore using SQL syntax. Issues the minimum amount of queries necessary in order to get the data that you request.
* 🔌 [Firestore Lite](https://github.com/samuelgozi/firebase-firestore-lite) ⭐ 223 | 🐛 7 | 🌐 JavaScript | 📅 2023-07-18 - Lightweight Cloud Firestore library for the browser.
* 🔧 [FirelordJS](https://github.com/tylim88/FirelordJS) ⭐ 95 | 🐛 4 | 🌐 TypeScript | 📅 2026-04-23 - Extremely High Precision Typescript Wrapper for Firestore Web. ([Admin version](https://github.com/tylim88/Firelord) ⭐ 41 | 🐛 2 | 🌐 TypeScript | 📅 2026-05-31)
* 🔧 [Remote Styles with Remote Config](https://github.com/firebaseextended/remote-styles/) ⚠️ Archived - Dynamic/Conditional loading of CSS stored in Remote Config. ([Launch post](https://medium.com/firebase-developers/introducing-remote-styles-conditional-css-loading-made-easy-daddbbcce050)).
* 🔌 [BuckleScript Bindings for Firebase](https://github.com/avohq/bs-firebase) ⚠️ Archived - BuckleScript bindings for Firebase for use in ReasonML projects.
* 💡 [Nextbase](https://github.com/martyan/nextbase) ⚠️ Archived - Boilerplate of Next.js, Redux & Firebase for developers who want a quick start project.
* 🔧 [FireSageJS](https://github.com/tylim88/FireSageJS) ⭐ 12 | 🐛 3 | 🌐 TypeScript | 📅 2023-10-24 - Extreme Type Safe For Realtime Database Web.
* 🔌 [GatsbyJS Firebase Data Source](https://www.gatsbyjs.org/packages/) - Query your Firebase data right into your statically generated pages with Gatsby.
* 📖 [Hosting Version History](https://firebase.google.com/docs/hosting/deploying#set_limit_for_retained_versions) - Automatic deletion of older versions of your site deployments.

## Mobile

* 🔌 [React Native Firebase](https://github.com/invertase/react-native-firebase) ⭐ 12,300 | 🐛 44 | 🌐 TypeScript | 📅 2026-08-20 - Well-tested feature rich modular Firebase implementation for React Native. Supports both iOS & Android platforms.
* 🔌 [FlutterFire](https://github.com/FirebaseExtended/flutterfire) ⭐ 9,247 | 🐛 67 | 🌐 Dart | 📅 2026-08-19 - Collection of Firebase plugins for [Flutter](https://flutter.io/) apps.
* 🔌 [React Native Firebase Cloud Messaging](https://github.com/evollu/react-native-fcm) ⭐ 1,729 | 🐛 305 | 🌐 Java | 📅 2022-12-06 -
  React Native module for Firebase Cloud Messaging and local notification.
* 🔌 [NativeScript plugin Firebase](https://github.com/EddyVerbruggen/nativescript-plugin-firebase) ⚠️ Archived - NativeScript plugin for Firebase.
* 💡 [Expo Native Firebase](https://github.com/EvanBacon/expo-native-firebase) ⚠️ Archived - Native Firebase Expo App (iOS, Android) Demo for Firestore, Notifications, Analytics, Storage, Messaging, Database.
* 🔌 [Flamingo](https://github.com/hukusuke1007/flamingo) ⭐ 118 | 🐛 5 | 🌐 Dart | 📅 2023-02-18 - A Firebase Firestore model framework for Dart.
* 💡 [Flutter Calendar App](https://github.com/mattgraham1/FlutterCalendar) ⭐ 78 | 🐛 1 | 🌐 Dart | 📅 2019-09-07 -
  New Flutter application implementing a simple mobile calendar app for storing basic events into Firebase cloud database.
* 📝 [App Distribution App Bundles](https://firebase.googleblog.com/2021/05/app-distribution-adds-support-to-android-app-bundles.html) - Support for Android App Bundles (AAB) is officially supported in App Distribution.
* 📖 [Firebase Flutter Documentation](https://firebase.google.com/docs/flutter/setup) - Official Firebase Flutter Setup.
* 🔧 [Firebase App Distribution](https://firebase.google.com/products/app-distribution/) - Distribute pre-release versions of your app to your trusted testers.

### Android

* 🔌 [Firebase UI](https://github.com/firebase/firebaseui-android) ⭐ 4,805 | 🐛 10 | 🌐 Kotlin | 📅 2026-08-19 - Optimized UI components for Firebase.
* 🔌 [GeoFire for Java](https://github.com/firebase/geofire-java) ⚠️ Archived - Realtime location queries with Firebase.
* 🔌 [Firecoil](https://github.com/rosariopfernandes/firecoil) ⭐ 44 | 🐛 2 | 🌐 Kotlin | 📅 2022-04-11 - Load images from GCS in your Android app using the image loading library Coil.
* 🔌 [FireXtensions](https://github.com/rosariopfernandes/firextensions) ⚠️ Archived - Unofficial Kotlin Extensions for the Firebase Android SDK.

### iOS

* 🔌 [Firebase UI](https://github.com/firebase/firebaseui-ios) ⭐ 1,593 | 🐛 0 | 🌐 Swift | 📅 2026-08-11 - iOS UI bindings for Firebase.
* 🔌 [GeoFire for Objective-C](https://github.com/firebase/geofire-objc) ⭐ 448 | 🐛 28 | 🌐 Objective-C | 📅 2025-10-15 - Realtime location queries with Firebase.
* 💡 [MLKit - ARKit](https://github.com/FirebaseExtended/MLKit-ARKit) ⚠️ Archived - Example detecting objects using Firebase ML Kit and tags them with 3D labels in Augmented Reality.
* 💡 [MLKit - ARCore](https://github.com/FirebaseExtended/MLKit-ARCore) ⚠️ Archived - Example detecting objects and tags them with 3D labels in Augmented Reality. Uses Firebase ML Kit, ARCore and Firebase RTDB.

## Games

* 📖 [Firestore for C++ and Unity](https://firebase.google.com/docs/firestore) - C++ and Unity SDKs for C++ and Unity (with Firebase Unity SDKs available via Unity Package Manager).

## Server-side (Cloud Functions, BigQuery etc)

* 💡 [Functions Samples](https://github.com/firebase/functions-samples) ⭐ 12,218 | 🐛 198 | 🌐 JavaScript | 📅 2026-08-19 - Collection of sample apps showcasing popular use cases using Cloud Functions for Firebase.
* 💡 [Express Server on Cloud Functions](https://github.com/jthegedus/firebase-gcp-examples/tree/main/functions-express) ⭐ 647 | 🐛 48 | 🌐 JavaScript | 📅 2023-03-04 - Host an Express server on Cloud Functions.
* 💡 [Compiled Code with Cloud Functions](https://github.com/jthegedus/firebase-gcp-examples/tree/main/functions-w-parcel) ⭐ 647 | 🐛 48 | 🌐 JavaScript | 📅 2023-03-04 - Compile your Flow, TypeScript or ReasonML to the correct Node runtime using Babel, TypeScript Compiler or ParcelJS.
* 📖 [Firebase Admin Documentation](https://firebase.google.com/docs/admin/setup) - Official Firebase Admin SDK Server Setup.
* 📝 [GraphQL Server on Cloud Functions](https://codeburst.io/graphql-server-on-cloud-functions-for-firebase-ae97441399c0) - Host an Express server with GraphQL middleware on Cloud Functions.
* 📝 [BigQuery & Google Analytics](https://medium.com/firebase-developers/how-do-i-create-a-closed-funnel-in-google-analytics-for-firebase-using-bigquery-6eb2645917e1) - How Do I Create a Closed Funnel in Google Analytics for Firebase Using BigQuery.

<!--lint ignore double-link-->

* 🔌 [Pyrebase](https://github.com/thisbejim/Pyrebase) ⭐ 2,074 | 🐛 237 | 🌐 Python | 📅 2024-05-14 - A simple python wrapper for the Firebase API.
* 🔌 [Integrify](https://github.com/anishkny/integrify) ⭐ 110 | 🐛 12 | 🌐 TypeScript | 📅 2026-08-18 - Enforce referential and data integrity in Firestore using pre-canned Cloud Functions triggers.
* 🔌 [Firestore Queue System](https://github.com/sbarbat/firestore-queuer) ⭐ 8 | 🐛 0 | 🌐 TypeScript | 📅 2020-08-17 - Simple queue system using Firestore and Cloud Functions.
* 🔌 [Firecode](https://github.com/kafkas/firecode) ⚠️ Archived - A light, fast, and memory-efficient collection traversal library for Firestore and Node.js.
* 📹 [Official Cloud Function #Firecasts](https://www.youtube.com/watch?v=2mjfI0FYP7Y\&list=PLl-K7zZEsYLm9A9rcHb1IkyQUu6QwbjdM) - YouTube video series about understanding how Cloud Functions work.
* 📝 [Firebase Hosting for Cloud Run Services](https://firebase.googleblog.com/2019/04/firebase-hosting-and-cloud-run.html) - Dynamic content with Hosting Rewrites & Cloud Run Services.
* 📝 [Scheduled (Cron) Cloud Functions for Firebase](https://firebase.googleblog.com/2019/04/schedule-cloud-functions-firebase-cron.html) - Firebase-native Cron triggers for Firebase Cloud Functions.
* 🔌 [Free Product Analytics with Firebase + BigQuery + Rakam](https://rakam.io/blog/free-product-analytics-with-firebase---bigquery---rakam/) - How to do behavioral & segmentation analysis on Firebase event data via BigQuery Export and Rakam.

## CLI & Editor

* 🔧 [Firetable](https://github.com/AntlerVC/firetable) ⭐ 6,833 | 🐛 79 | 🌐 TypeScript | 📅 2024-11-23 - Excel/Google Sheets like UI for Firebase/Firestore. No more admin portals!
* 🔧 [Firebase Tools](https://github.com/firebase/firebase-tools) ⭐ 4,456 | 🐛 989 | 🌐 TypeScript | 📅 2026-08-20 - The Firebase Command Line Tools.
* 📖 [Firebase Tools UI](https://github.com/firebase/firebase-tools-ui) ⭐ 291 | 🐛 156 | 🌐 TypeScript | 📅 2026-08-20 - Web UI for Firebase Emulator Suite.
* 🔧 [Fireward](https://github.com/bijoutrouvaille/fireward) ⭐ 235 | 🐛 17 | 🌐 Haskell | 📅 2023-04-10 - Easy to use language for Firestore rules, similar to Firebase Bolt.
* 🔧 [Fuego](https://github.com/sgarciac/fuego) ⭐ 225 | 🐛 6 | 🌐 Go | 📅 2025-11-27 - Firestore client CLI supporting document add/update/query with filtering and pagination.
* 🔧 [Firestore Rules Generator](https://github.com/FirebaseExtended/protobuf-rules-gen) ⚠️ Archived - Official (but experimental) Firebase Rules Generator for Cloud Firestore based on Google's Protocol Buffer format.
* 🔧 [VSCode Firebase Explorer](https://github.com/jsayol/vscode-firebase-explorer) ⭐ 150 | 🐛 25 | 🌐 TypeScript | 📅 2023-11-27 - Explore and manage your Firebase projects.
* 🔧 [VSFire](https://github.com/toba/vsfire) ⚠️ Archived - Deprecated ~~VSCode extension for syntax highlighting & code completions with Firestore security rules & indexes.~~
* 🔧 [Firebase CI](https://github.com/prescottprue/firebase-ci) ⭐ 72 | 🐛 17 | 🌐 JavaScript | 📅 2023-01-16 - Simplified Firebase interaction for continuous integration.
* 🔧 [Firecode](https://github.com/ChFlick/firecode) ⭐ 39 | 🐛 8 | 🌐 TypeScript | 📅 2023-09-27 -  VS Code Firestore Rules Extension.
* 🔧 [Svarog](https://github.com/dantothefuture/svarog) ⚠️ Archived - Cloud Firestore schema validation with JSON Schema generated Security Rule helper functions.
* 🔧 [Firepit](https://github.com/abehaskins/firepit) ⭐ 25 | 🐛 9 | 🌐 JavaScript | 📅 2022-12-09 - Firepit is a standalone, portable version of the Firebase CLI which has no depedencies (including Node.js).
* 🔧 [asdf-firebase](https://github.com/jthegedus/asdf-firebase) ⭐ 19 | 🐛 3 | 🌐 Shell | 📅 2024-02-06 - An [asdf-vm](https://asdf-vm.com/) plugin for `firebase-tools`. Manage your Firebase CLI without Node.js or `npm`! Great for `python`, `golang`, `c++` & `java` Firebase projects.
* 🔧 [Firebase Firestore Snippets](https://github.com/peterhdd/firebase-firestore-snippets) ⭐ 14 | 🐛 2 | 📅 2022-12-07 - Contains the snippet for both Firebase and Firestore in VS Code editor.
* 📖 [Storage in Emulator Suite](https://firebase.google.com/docs/emulator-suite/connect_storage) - Emulator suite is now complete!
* 📝 [Refi App](https://refiapp.io/) - A GUI tool to make developers less painful when interacting with Firestore DB
* 🔧 [Firefoo](https://firefoo.app) - Cloud Firestore GUI Admin Tool with JSON/CSV Export and JavaScript Query Shell.

## Other

* 🔧 [Flank](https://github.com/flank/flank/) ⭐ 698 | 🐛 74 | 🌐 Kotlin | 📅 2026-06-20 - Massively parallel Android and iOS test runner for Firebase Test Lab.
* 🔌 [QtFirebase](https://github.com/Larpon/QtFirebase) ⭐ 289 | 🐛 25 | 🌐 C++ | 📅 2022-11-28 - An effort to bring Google's Firebase C++ API to Qt + QML.
* 💡 [Unity Solutions](https://github.com/FirebaseExtended/unity-solutions) ⚠️ Archived - Use Firebase tools to incorporate common features into your games.
* 🔌 [FireDrill](https://github.com/scottlepp/fire-drill) ⚠️ Archived - Find, Edit, Add, Remove, Import, Export, and Report on your Firebase data.
* 🔌 [Firebase AIR Native Extension](https://github.com/myflashlab/Firebase-ANE) ⚠️ Archived - Firebase ANE collection give you access to the Google Firebase project in your AdobeAir projects supported on both Android and iOS with 100% identical ActionScript API.
* 🔧 [FireCMS](https://firecms.co/docs/) - FireCMS is an open source headless CMS and admin panel built by developers for developers. It generates CRUD views based on your configuration.
* 🔌 [Firestore Query Browser](https://firestore-query-browser.firebaseapp.com) - WebApp to Query, (Batch-)Edit & Export documents with app & user switching.
* 📝 [StackBlitz to Firebase Hosting Deployments](https://medium.com/@ericsimons/announcing-split-second-static-deploys-for-firebase-7440d8e84879) - StackBlitz (online code editor) to Firebase Hosting static deployments.
* 🔧 [Flamelink](https://flamelink.io/) - CMS for Firebase. Supports Firestore, RealtimeDatabase & Storage.
* 📹 [Firebase Summit 2018](https://www.youtube.com/watch?v=lN0VXVXsj9k\&list=PLl-K7zZEsYLnqdlmz7iFe9Lb6cRU3Nv4R) - All Firebase Summit 2018 talks.
* 📹 [Firebase @ Google Cloud Next '18](https://www.youtube.com/watch?v=OPj26MY16F8\&list=PLl-K7zZEsYLmYx3MkJRIUPH_JVFHLTlwL) - All Firebase talks @ Google Cloud Next 2018.
* 📹 [Firebase @ Google IO '18](https://www.youtube.com/watch?v=e-8fiv-vteQ\&list=PLl-K7zZEsYLn1omgx_VUhCDFsQMA7PRDd) - All Firebase talks @ Google IO 2018.
* 📹 [#AskFirebase YouTube Playlist](https://www.youtube.com/watch?v=TSzhzR4wzSE\&list=PLl-K7zZEsYLkkCFs6T9mlqG8v6NCs38pA) - Official #AskFirebase playlist on YouTube.
* 📝 [State of Firebase (mid 2019)](https://codeburst.io/the-state-of-firebase-mid-2019-2b002c458d70) - Cloud Next & Google I/O 2019 updates!
* 📹 [Firebase @ Google IO '19](https://www.youtube.com/playlist?list=PLl-K7zZEsYLlo2L4rfPds-fFLEtOWheoO) - All Firebase talks @ Google IO 2019.
* 📹 [Firebase Summit 2019](https://www.youtube.com/watch?v=YKZ6rP4kwV8\&list=PLl-K7zZEsYLk2OolaVXVyYrFErctrZXSX) - All Firebase talks @ the Firebase Summit 2019.
* 📹 [Firebase Live 2020](https://www.youtube.com/playlist?list=PLl-K7zZEsYLnw0-bXz2f9zo6745VQ_2ep) - Firebase Live is a web series for app developers consisting of talks, tips, and technical tutorials aimed at increasing their productivity, knowledge, and collaboration.
* 📹 [Firebase Summit 2020](https://goo.gle/firebasesummit2020) - All Firebase talks @ the Firebase Summit 2020.
* 🔧 [Dynaboard](https://dynaboard.com) - Generate low-code web apps from Firebase using AI.

<!-- END content -->

## Follow

### Official

* 📹 [Firebase YouTube](https://www.youtube.com/user/Firebase)
* 📝 [Firebase Blog](https://firebase.googleblog.com/)
* 🐦 [@firebase](https://twitter.com/firebase)
* 👤 [Firebase Facebook](https://www.facebook.com/Firebase)
* 🔊 [The Firebase Podcast](https://podcasts.google.com/feed/aHR0cDovL2ZpcmViYXNlcG9kY2FzdC5nb29nbGVkZXZlbG9wZXJzLmxpYnN5bnByby5jb20vcnNz) - This is the place where we dive deep into Firebase products and learn new tips and tricks along the way.

### Community

* :fire: [Firebase Developers Discord](https://discord.gg/BN2cgc3) - an open community dedicated to Firebase and its services, where you can to socialize and help other web and app developers from around the world.
* 📹 [Fireship](https://www.youtube.com/channel/UCsBjURrPoezykLs9EqgamOA) - A YouTube channel by Jeff Delaney, a Google Firebase expert and creator of the famous "X in 100 Seconds" videos.
* 📹 ru [@firebase\_ru - Telegram friendly chat](https://t.me/firebase_ru)

Who else should we be following!?

## Contributing

[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors

[Thanks goes to these contributors](https://github.com/jthegedus/awesome-firebase/graphs/contributors) ⭐ 794 | 🐛 9 | 📅 2024-04-06!

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-20._
