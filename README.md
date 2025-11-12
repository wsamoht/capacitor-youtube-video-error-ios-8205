A reproduction for https://github.com/ionic-team/capacitor/issues/8205

# Reproducing

Run the following:

```bash
npm install
ionic cap build ios
```

Then run in an iOS Simulator and try to play the YT video.

Running with Live Reload works (YouTube doesn't give an error) because the HTTP scheme is `http` vs. `capacitor`. This is why I believe Android works too.

# Resources

-   https://developers.google.com/youtube/terms/required-minimum-functionality
    -   Mentions how to handle WebViews
-   https://developers.google.com/youtube/iframe_api_reference
