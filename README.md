<head>  

<link rel="icon" href="https://i.postimg.cc/jCYKxR9N/Picsart-23-12-31-02-41-43-217.jpg" type="image/png" sizes="48x48">

<meta charset="UTF-8">  

<title>ASTRO CRICKET</title>  

<meta http-equiv="X-UA-Compatible" content="IE=edge">  

<meta name="viewport" content="width=device-width, initial-scale=1.0">  

<script src="https://cdn.jsdelivr.net/gh/oziltv/dondoo@main/master/shaka.js"></script>

<script src="https://cdn.jsdelivr.net/gh/oziltv/dondoo@main/master/shaka-player.ui.js"></script>

<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/gh/oziltv/dondoo@main/master/shaka.css">   

<div class='post-body entry-content float-container' id='post-body-3814173843942804688'>

<meta name="referrer" content="no-referrer" />

 <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1" />

 <meta name="viewport" content="width=device-width, initial-scale=1.0" />

<center>
  
  
<style>

#tglogo {

position: absolute;

left: 30%;

top: 0%;

height: 7%;

width: 7%;

} 
</style>
  
<div data-shaka-player-container="" style="max-width: 100em; cursor: none;" data-shaka-player-cast-receiver-id="8D8C71A7" shaka-controls="true" class="shaka-video-container">

<video autoplay="true" data-shaka-player="" id="video" poster="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEiRrHIX5VjmYiauiCTO_Vx4v1GHzq-_SNjzuZ4XnqPt5TttSYpAFvhMoCSLJaPqlfMzicj-xpYW_EZB9S66MjqtkSyhhKX1zxORgBQMaEbfGWjoDwQwhJJp2zqlq2yRDADo-kBnQRj2-_SVaFkwQjkw4OYZ5wiMMkSHfynVkbDWV71VNHSF9fXi18OtCxs/s1600/Picsart_23-11-27_19-18-36-812.png" style="width: 100%; height: 100%;" class="shaka-video" src=""></video>

<img id="tglogo" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhhTzcwb_E0kAAPG8gyrI1-4sPohQZZ9SWBjHNBNooChVYbWKtwbHIvK8pz1yCXVD20E9MtA1MTwl4Gvy-6dVjgTpejprPzdBxtjpQa8Gu4oII-3Gf5-qPZOsFOf1gymoO77u5GkObifPOH6icjrae9MOj9gVp8ekaHYxdcGUm18ZTTsnPffPIt4IkF8uU/s1600/Picsart_24-06-20_14-21-29-451.png"> 
  
    <script>
        if (confirm("Join Our Telegram Channel @shwe7ank")) {
            window.location.href = "https://t.me/+U_dJ3R571Po2OTA1";
        }

        async function init() {
            let e = document.getElementById("video"),
                r = e.ui,
                n = r.getControls(),
                o = n.getPlayer();

            // Faster startup and reduced buffering
            o.configure({
                drm: {
                    clearKeys: {
                        "cb8daf414566aa17d06f8294f3f3b444": "89d58908a57d70ef87bf16c9b5821ca2"
                    }
                },
                streaming: {
                    startAtSegmentBoundary: true, // Start playback exactly at segment boundary
                    ignoreTextStreamFailures: true, // Ignore subtitle loading issues
                    rebufferingGoal: 1, // Lower rebufferingGoal for faster resume
                    bufferingGoal: 3, // Lower bufferingGoal for faster start
                    bufferBehind: 5, // Lower bufferBehind to free memory
                    autoLowLatencyMode: true, // Enable auto low latency if available
                    lowLatencyMode: true, // Enable low-latency streaming
                    jumpLargeGaps: true, // Allow skipping over gaps in the stream
                    inaccurateManifestTolerance: 0.3, // Faster manifest synchronization
                    stallEnabled: false // Disable stall detection for faster start
                },
                manifest: {
                    dash: {
                        ignoreMinBufferTime: true, // Ignore minBufferTime in MPD for faster start
                        autoCorrectDrift: true // Auto-correct time drift
                    }
                }
            });
            // UI configurations
            r.configure({
                controlPanelElements: ["play_pause", "mute", "volume", "spacer", "time_and_duration", "quality", "fullscreen", "overflow_menu"],
                volumeBarColors: { base: 'rgba(63, 187, 1, 1)', level: 'rgb(255, 69, 0)' },
                seekBarColors: { base: 'rgb(41, 41, 163)', buffered: 'rgb(35, 99, 3)', played: 'rgba(63, 187, 1, 1)' }
            });

            window.player = o;
            window.ui = r;

            o.addEventListener("error", onPlayerErrorEvent);
            n.addEventListener("error", onUIErrorEvent);

            // Load the video as quickly as possible
            try {
                await o.load("https://aba5sdmaaaaaaaamjyr2xiy4rbicb.otte.live.cf.ww.aiv-cdn.net/pdx-nitro/live/clients/dash/enc/zqhtvqjquq/out/v1/190f1d69a3d5467f8fb7d9df4339bc49/cenc.mpd");
                console.log("The video has now been loaded instantly!");
            } catch (a) {
                onPlayerError(a);
            }
        }

        function onPlayerErrorEvent(e) {
            onPlayerError(e.detail);
        }

        function onPlayerError(e) {
            console.error("Error code", e.code, "object", e);
        }

        function onUIErrorEvent(e) {
            onPlayerError(e.detail);
        }

        function initFailed(e) {
            console.error("Unable to load the UI library!");
        }

        document.addEventListener("shaka-ui-loaded", init);
        document.addEventListener("shaka-ui-load-failed", initFailed);
    </script>
</body>

</html>
