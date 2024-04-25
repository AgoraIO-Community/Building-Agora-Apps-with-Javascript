# Building Agora Apps with Javascript: A Guide for Frontend Developers
Javascript and Typescript are the top languages for front-end developers build websites, web-apps, and PWA's. In this post, you'll get a birds eye view of the different Agora JavaScript SDKs and see examples of how you can utilize them in your next project.

## Prerequisites
To make the most of the resources in this post, you should have:
- An Agora account (first 10k minutes are free each month)
- A working knowledge of Javascript and Node.js
- Node.js installed on your machine
- npm, or yarn

## The Agora JavaScript SDKs
Agora offers JavaScript SDKs for all products that are used to develop real-time features in frontend apps. These SDKs allow you to build browser apps for video calling, voice calling, chat, and more. They include:
- The Agora [Voice Web SDK](https://docs.agora.io/en/voice-calling/overview/product-overview?platform=web) for realtime voice calling/live-streaming
- The Agora [Video Web SDK](https://docs.agora.io/en/video-calling/overview/product-overview?platform=web) for realtime video calling/live-streaming
- The Agora [Chat Web SDK](https://docs.agora.io/en/agora-chat/overview/product-overview?platform=web) for building robust chat apps
- The Agora [Signaling Web SDK](https://docs.agora.io/en/signaling/overview/product-overview?platform=web) for real-time synchronization
- The Agora [Whiteboard Web SDK](https://docs.agora.io/en/interactive-whiteboard/overview/product-overview?platform=web) for real-time collaboration 

### Generating Access Tokens
To make use of these SDKs, you need a way to authenticate your users with Agora, in a way that doesn't expose your Agora credentials. That means, even though you're building a client side app, you'll still need a backend server to generate access tokens. These tokens verify the client has your authorization to access Agora's real-time network.
- [Generate Access Tokens in Node.js](https://www.agora.io/en/blog/how-to-build-a-token-server-for-agora-applications-using-nodejs/)
- [Quick Deploy A Token Server](https://github.com/AgoraIO-Community/agora-token-service)

### Voice Calls and Live Podcasting with Agora Web SDK
Agora Voice Calling allows you to add crystal-clear audio chat or live audio streaming to any web application. With this SDK, you can add one-to-one or small-group voice communication with smooth, jitter-free streaming to your web app.

To install it from your command line:
```bash
npm i agora-rtc-sdk-ng
```

Once you've installed the SDK and generated your access token, you're free to start building real-time voice communication features into your project.
- See [how to get started with real-time voice for web](https://docs.agora.io/en/voice-calling/get-started/get-started-sdk?platform=web) using Agora's Web SDK.

### Programmable Real-time Video in Web with Agora Video
The Agora  Video Web SDK allows you to build robust and high quality video and voice calling and live-streaming apps in the browser using Javascript. Check out Agora's detailed [API documentation](https://docs.agora.io/en/api-reference?platform=web).

Install Agora Video Web SDK:
```bash
npm i agora-rtc-sdk-ng
```

For React JS developers, use the Agora Video React Web SDK:
```bash
npm i agora-rtc-react
```

- Learn how to [build a video chat app with vanilla Javascript and the Agora Video Web SDK](https://medium.com/agora-io/a-simple-approach-to-building-a-group-video-chat-web-app-0b8a6cacfdfd)
- See how to [build a video chat app with Agora's React SDK using Agora components and hooks.](https://medium.com/agora-io/how-to-build-a-real-time-video-web-app-with-react-11056318ef4d)

### Agora  Chat 
Agora Chat enables you to develop text-based chatting applications. Integrate private and group messaging into your applications.

Install the Agora Chat Web SDK:
```bash
npm i agora-chat
```

Explore this project to [learn how to build a full-feature chat web app with Javascript and the Agora Chat web SDK.](https://github.com/AgoraIO/Agora-Chat-API-Examples/tree/main/Chat-Web)

### Agora Signaling
Agora Signaling provides low-latency, high-concurrency signaling and synchronization capabilities for real-time systems. It enables developers to apply low-latency event notifications and real-time changes to user, device, and channel attributes in applications without setting up complex backends to send and synchronize the data.

To get started with the Agora Signaling, install it with this command:
```bash
npm i agora-rtm-sdk
```

- Explore this quick-start guide to [learn how to build add Agora signaling to your web app](https://docs.agora.io/en/signaling/develop/get-started-sdk?platform=web)
- Check out this project to [learn how to add Agora signaling's robust features to your web app](https://github.com/AgoraIO/signaling-sdk-samples-web)

## Other Resources
- Dive into the [Agora Documentation](https://docs.agora.io/en/) to gain a deeper understanding of the features and capabilities offered by Agora SDK. Explore the API reference, sample codes, and best practices.
- Be part of the Agora developer community: Join the conversation on [X(Twitter)](https://twitter.com/AgoraIO), or [LinkedIn](https://www.linkedin.com/company/agora-lab-inc/) to share experiences, and stay updated on the latest developments. Need support? Reach out via [StackOverflow](https://stackoverflow.com/questions/tagged/agora.io) for advice on your implementation.
Continue your developer journey with more guides from [Agora's Medium publication](https://medium.com/agora-io).

## Next Steps
I hope this article helped you get started building web apps with the Agora JavaScript SDKs. Make sure to bookmark this page so you have all the resources you need in one place. Also, if you'd like to see more articles like this that use Agora's other SDKs, drop a comment with your ideas!
