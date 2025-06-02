How to run locally:

1. Clone or download this repository.
   Make sure all files are in the same folder:

    index.html
    hls_playlist.m3u8
    all .ts video segments
   
2. Start a local HTTP server using Python 3:

    python -m http.server 8000
   
4. Open your browser and go to:

    http://localhost:8000

Your HLS player should now be running locally.
Note: Browsers do not allow playing .m3u8 files via file://, so a local server is required.

Sample HLS stream URLs:

https://rbmn-live.akamaized.net/hls/live/590964/BoRB-AT/master.m3u8
https://live-hls-web-aje.getaj.net/AJE/index.m3u8
https://test-streams.mux.dev/pts_shift/master.m3u8
