# Groove Atlas

Groove Atlas is a browser-based music practice studio with 80 original four-bar loops. The presets draw on production characteristics from four Lorde album eras, with 20 grooves each for *Pure Heroine*, *Melodrama*, *Solar Power*, and *Virgin*. The Web Audio engine generates the sounds in the browser.

## Practice with a groove

1. Choose an album era and a groove, then press **Play** to start the loop.
2. Click steps on the 16-step sequencer to edit the drum, bass, and chord patterns. Adjust BPM and swing to change the feel, and use the mixer to balance the parts.
3. For vocal or instrument practice, start the microphone pitch monitor and grant browser permission. Use headphones to keep loop audio from bleeding into the microphone. The monitor needs HTTPS or localhost.

## Run locally

From the repository root, run `python3 -m http.server 8000` and open [localhost:8000](http://localhost:8000/). The studio runs from `index.html` with no build step.

## Publish with GitHub Pages

Open the repository's **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select **main** and **/(root)**, then click **Save**. After GitHub completes the deployment, open the site URL shown in Pages and check that Groove Atlas loads. The root `.nojekyll` file tells Pages to serve the static files directly.
