# Roadmap

Roughly in the order I plan to do them. This will change as beta testers tell me what's actually annoying.

## Done recently

- **Lightroom, Capture One and Bridge.** Star ratings and color labels are written to .xmp sidecars. (Lightroom keeps pick and reject flags in its catalog, so those stay in Declic.)
- **Folders by event.** Photos are split into events and copied into named folders, with a preview first.

## Next

- **Closed eyes.** Check whether eyes are open on every detected face, so a blink loses to the frame next to it.
- **A real Mac app.** Right now it needs Docker and a terminal. The goal is to drag it to Applications and open it. Work on this has started.
- **More cameras.** Canon CR3, Nikon NEF, Fuji RAF, DNG and iPhone photos, tested on real cards rather than assumed.

## After that

- **Side-by-side finalist check.** For close calls, compare the top two or three frames of a burst together instead of scoring each one alone. That's how you'd pick the peak moment yourself.
- **Learning your taste.** Every time you flip a keep or reject, that's a hint about what you like. Use it to adjust the ranking for you.

## Maybe

- Windows and Linux. The vision model currently relies on Apple's MLX, so this is a bigger job.
- Video. Picking the best frame out of a clip is a similar problem.

## Not planned

- Cloud processing. Declic runs on your machine, and that's the point.
- A subscription you'd need to keep access to your own ratings.

Have an idea? [Open a feature request](../../issues/new?template=feature-request.yml).
