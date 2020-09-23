# Webrtc Demo: Connection through self-hosted TURN server  
This page is used for testing self-hostd TURN Server.   
Streaming from one video to another by WebRTC relay connection.  
[Demo Page](https://webrtc-turn-server-test.vercel.app/)

You can
1. Key in username and password if your TURN server is using long-term credential.  
2. Key in username and static secret if your TURN server is using short-term credential. This page will generate password for you.  
3. Or keep blank if no-auth is used.

## Trouble shooting
If you don't see the video on destination, please open `chrome://webrtc-internals/` on Chrome or `about:webrtc` on Firefox.  
You need to check why connection is failed.  