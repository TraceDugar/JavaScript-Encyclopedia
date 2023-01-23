# Class 41

(https://reactnative.dev/docs/intro-react-native-components)

Name three Core Components of React Native and describe what they do.
View, A container that supports layout with flexbox, style, some touch handling, and accessibility controls.  Text, 	Displays, styles, and nests strings of text and even handles touch events.  Image, 	Displays different types of images.
<br>

What problem does React Native solve (why call it native)?
In Android development, you write views in Kotlin or Java; in iOS development, you use Swift or Objective-C. With React Native, you can invoke these views with JavaScript using React components. At runtime, React Native creates the corresponding Android and iOS views for those components. Because React Native components are backed by the same views as Android and iOS, React Native apps look, feel, and perform like any other apps. We call these platform-backed components Native Components.
<br>

What are the building blocks of a React Native app? How does that compare to a React app?
Because React Native uses the same API structure as React components, you’ll need to understand React component APIs to get started. The next section makes for a quick introduction or refresher on the topic. However, if you’re already familiar with React, feel free to skip ahead.
<br>

(www.google.com)

What solution does expo provide?
Develop for all your users' devices with just one codebase. Add fast refresh, true native capabilities, and your creativity, and you'll have the app your users want in no time.
<br>

Expo tries to manage as much of the complexity of building apps as possible, which is why we call it the managed workflow.

<br>

What is the difference between React Native and Expo?
Expo lets web developers build truly native apps that work across both iOS and Android by writing them once in just JavaScript.
<br>

(https://snack.expo.io/)

Checkout this tool. What does snack allow you to do?
puts people in a queue, and instantly make changes
<br>

(https://docs.expo.io/versions/latest/expokit/eject)

What does “eject” mean within the context of Expo?
Because you still depend on the Expo SDK, but your project no longer lives inside Expo Go. You control the native projects, including configuring and building them yourself.
<br>

When should you not eject?
You should not eject if:
<ul>
<li>All you need is to distribute your app in the iTunes Store or Google Play. Expo can build binaries for you in that case. If you eject, we can't automatically build for you any more.</li>
<li>You are uncomfortable writing native code. Ejected apps will require you to manage Xcode and Android Studio projects.</li>
<li>You enjoy the painless React Native upgrades that come with Expo. After your app is ejected, breaking changes in React Native will affect your project differently, and you may need to figure them out for your particular situation.</li>
<li>You require Expo's push notification services. After ejecting, since Expo no longer manages your push credentials, you'll need to manage your own push notification pipeline.</li>
<li>You rely on asking for help in the Expo community. In your native Xcode and Android Studio projects, you may encounter questions which are no longer within the realm of Expo.</li>
</ul>
<br>

Why might you choose to eject?
Your Expo project needs a native module that Expo doesn't currently support. We're always expanding the Expo SDK, so we hope this is never the case. But it happens, especially if your app has very specific and uncommon native demands.
