# Awesome Firestore [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

>  [Cloud Firestore](https://firebase.google.com/docs/firestore/)の情報まとめ


## 目次

- [ドキュメント](#ドキュメント)
  - [リファレンス](#リファレンス)
- [バインディング](#バインディング)
- [ヘルパー](#ヘルパー)
- [GUI管理クライアント](#gui管理クライアント)
- [非対応(RTDBのみ対応)](#非対応rtdbのみ対応)

## ドキュメント

- [Cloud Firestore ガイド](https://firebase.google.com/docs/firestore/)

### リファレンス

#### クライアントサイド
- [Android](https://firebase.google.com/docs/reference/android/com/google/firebase/firestore/package-summary)  
- [iOS - Swift](https://firebase.google.com/docs/reference/swift/firebasefirestore/api/reference/Classes)  
- [iOS - Objective-C](https://firebase.google.com/docs/reference/ios/firebasefirestore/api/reference/Classes)  
- [Web](https://firebase.google.com/docs/reference/js/firebase.firestore)  
- [REST](https://firebase.google.com/docs/firestore/reference/rest/)
- [RPC](https://firebase.google.com/docs/firestore/reference/rpc/)

#### サーバサイド
- [Cloud Functions](https://firebase.google.com/docs/reference/functions/functions.firestore)  
- [Node.js](https://cloud.google.com/nodejs/docs/reference/firestore/0.14.x/)
- [Java](https://googlecloudplatform.github.io/google-cloud-java/google-cloud-clients/apidocs/index.html?com/google/cloud/firestore/package-summary.html)
- [Python](https://google-cloud-python.readthedocs.io/en/latest/firestore/client.html)
- [Go](https://godoc.org/cloud.google.com/go/firestore)

#### その他
- [セキュリティルール](https://firebase.google.com/docs/reference/rules/index-all)
- [CLI](https://firebase.google.com/docs/cli/)

## バインディング

- ~[firebase/angularfire](https://github.com/firebase/angularfire)~ - 公式のAngularJSバインディングだが[Firestoreはまだ非対応](https://github.com/firebase/angularfire/issues/956)．
- [angular/angularfire2](https://github.com/angular/angularfire2) - 公式のAngularバインディング．
- [vuejs/vuefire](https://github.com/vuejs/vuefire) - 公式のVue.jsバインディング．
  - [posva/vuexfire](https://github.com/posva/vuexfire) - VuefireメンテナによるVuexバインディング.
- [tylermcginnis/re-base](https://github.com/tylermcginnis/re-base) - React.jsバインディング．
  - [prescottprue/react-redux-firebase](https://github.com/prescottprue/react-redux-firebase) - Reduxバインディング．

## ヘルパー

- [firebase/FirebaseUI-Android](https://github.com/firebase/FirebaseUI-Android)	- An official library of UI components for several Firebase features.
- [firebase/FirebaseUI-iOS](https://github.com/firebase/FirebaseUI-iOS)	- An official library of UI components for several Firebase features.
- ~[firebase/geofire-js](https://github.com/firebase/geofire-js)~ - An official library for the RTDB that adds support for geospatial querying but [it doesn't support  Firestore yet](https://github.com/firebase/geofire-js/issues/163).


## GUI管理クライアント

- [prescottprue/fireadmin](https://github.com/prescottprue/fireadmin) - Application for Managing Firebase App including support for multiple environments and data migrations.
- [Chat SDK](https://chatsdk.co/) - A fully featured open source messaging framework for iOS and Android.


## 非対応(RTDBのみ対応)

firebase/angularfire, firebase/geofire-java, firebase/geofire-objc, firebase/geofire-js, firebase/firebase-util, firebase/firebase-jobdispatcher-android, firebase/firebase-jobdispatcher-ios, firebase/firepad

## 貢献

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


## ライセンス

[MIT License](./LICENSE.md) (c) 2018 [Firebase Japan User Group](https://firebase.asia) by using [awesome-firebase](https://github.com/afonsopacifer/awesome-firebase) as reference.
