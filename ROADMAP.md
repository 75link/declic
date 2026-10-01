# Roadmap

Roughly in the order I plan to do them. This will change as beta testers tell me what's actually annoying.

## Next

- **Lightroom and Capture One.** Write star ratings and reject flags to XMP sidecars, so the cull carries straight into your editor.
- **Closed eyes.** Check whether eyes are open on every detected face, so a blink loses to the frame next to it.
- **A real Mac app.** Right now it needs Docker and a terminal. The goal is to drag it to Applications and open it.
- **More cameras.** Canon CR3, Nikon NEF, Fuji RAF, DNG and iPhone photos, tested on real cards rather than assumed.

## After that

- **Side-by-side finalist check.** For close calls, compare the top two or three frames of a burst together instead of scoring each one alone. That's how you'd pick the peak moment yourself.
- **Learning your taste.** Every time you flip a keep or reject, that's a hint about what you like. Use it to adjust the ranking for you.
- **Folders and names.** Suggest a folder structure like `2026-09-27 Cycling race / Selects`, show it to you first, and apply it with undo.

## Maybe

- Windows and Linux. The vision model currently relies on Apple's MLX, so this is a bigger job.
- Video. Picking the best frame out of a clip is a similar problem.

## Not planned

- Cloud processing. Declic runs on your machine, and that's the point.
- A subscription you'd need to keep access to your own ratings.

Have an idea? [Open a feature request](../../issues/new?template=feature-request.yml).
