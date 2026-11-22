var myPeerConnection = new RTCPeerConnection({
  iceServers: [
    {
      urls: "stun:stun.relay.metered.ca:80",
    },
    {
      urls: "turn:global.relay.metered.ca:80",
      username: "71d2454b4ab3d1052d3a05d4",
      credential: "7ztr0igHWPFxMijB",
    },
    {
      urls: "turn:global.relay.metered.ca:80?transport=tcp",
      username: "71d2454b4ab3d1052d3a05d4",
      credential: "7ztr0igHWPFxMijB",
    },
    {
      urls: "turn:global.relay.metered.ca:443",
      username: "71d2454b4ab3d1052d3a05d4",
      credential: "7ztr0igHWPFxMijB",
    },
    {
      urls: "turns:global.relay.metered.ca:443?transport=tcp",
      username: "71d2454b4ab3d1052d3a05d4",
      credential: "7ztr0igHWPFxMijB",
    },
  ],
});
