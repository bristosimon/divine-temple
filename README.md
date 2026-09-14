# Sri Ganesha Divine Blessing — 3 Second Person Detection V5

The gesture requirement has been completely removed.

How it works:
1. Camera stays on.
2. When a person is detected in front of the camera, a 3-second timer starts.
3. If the person remains continuously visible for about 3 seconds, the temple bell rings and the Kannada divine blessing plays.
4. The app will not repeatedly trigger while the same person remains in front.
5. After the person leaves the camera view, it becomes ready for the next visitor.

The app uses MediaPipe Pose only for detecting whether a person is present; no bending or hand/gesture detection is used.

Host on HTTPS (GitHub Pages recommended).
