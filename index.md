---
layout: default
---

## Prerequisites
- [OBS Studio](https://obsproject.com/)
- [Branch Output for OBS](https://github.com/OPENSPHERE-Inc/branch-output/releases)

Welcome to Loop, we're glad to have you! If you haven't already, please visit https://looptv.studio/ and create an account.

## Single Stream on One Device

1. Once you've created an account, go to your Streamer Studio. 
2. In your Streamer Studio, you can click the "New Stream" button to create a new stream, and set the title to whatever you would like. 
3. After this, you will be asked if you would like to stream with an external encoder, or our browser webcaster. As we're using OBS in this tutorial, click External Encoder
4. Once you have done this, click the "Show RTMP" button in your stream
5. Open OBS, and navigate to **Settings > Stream**
	- Set the Service option to Custom
	- Paste the RTMP URL from your Streamer Studio into the Destination box 
	- Paste the Stream Key from your Streamer Studio into the Stream Key box 
6. From there, you're ready to stream!

## Multi-Streaming
**This section is WIP until multi-streaming is fully functional on our website**
Now that you know how to stream with one input, you can start to use our Multi-Streaming features!

Before you begin this step, make sure you've installed the **Branch Output** plugin found in the [Prerequisites](#Prerequisites) section. Scroll down in the linked GitHub page, and download the installer for your operating system.

1. Once the plugin is installed, right-click a scene you would like to stream, and click "Filters"
2. Click the "+" button in the bottom left, and then add a Branch Output filter.
3. Paste the RTMP link into Stream > Streaming 1 Server
4. Paste the Stream Key into Stream > Stream Key
5. If you would like to use a custom audio source, you can enable it in the filter. Otherwise, your stream will use the audio sources from your selected scene.
6. **By default, a scene will not have any audio. If you haven't added an audio source to your scene, you must do so. Otherwise, use the "Custom Audio Source" setting in the Branch Output filter.**
7. Repeat the process for each scene you would like to broadcast.
8. When you're ready to start the streams, go to Docks > Branch Output Status
9. There are eye icons to the left of each stream. If the eye is dark and crossed out, the stream has not started. When you are ready to start a stream, click the eye icon to enable it. 
10. You're now ready to multi-stream!
