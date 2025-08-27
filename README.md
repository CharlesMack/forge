# forge
FrameForge is a web-based cinematic webcam studio that lets you apply professional-grade color grading and camera effects to your live video feed. Capture stunning, high-quality footage directly from your browser, no complex software required.

### FrameForge: Cinematic Webcam Studio

FrameForge is a web-based **cinematic webcam studio** that lets you apply professional-grade color grading and camera effects to your live video feed. Capture stunning, high-quality footage directly from your browser, no complex software required.

---

### README.md

# FrameForge: Cinematic Webcam Studio 🎥

Welcome to FrameForge, a powerful and accessible web application for transforming your webcam feed into cinematic-quality footage. With a simple, clean interface, you can apply professional color profiles, use advanced exposure tools, and add anamorphic effects—all in real-time.



### ✨ Key Features

-   **Cinematic Color Grading:** Apply built-in color profiles or upload your own **.cube LUTs** to give your video a professional, stylized look.
-   **Exposure & Metering Tools:** Use a real-time **waveform, RGB parade, and vectorscope** to monitor your video's color and luma levels. Use the **false color** and **zebras** (highlight/shadow clipping) tools for precise exposure control.
-   **Cinematic Effects:** Get that widescreen look with **anamorphic desqueeze** options and frame your shots with adjustable **aspect ratio** guides.
-   **Focus Assist:** Highlight sharp areas of your image to ensure your subject is always in perfect focus.
-   **Auto ND Filter:** Automatically adjust your exposure based on ISO and lighting conditions.
-   **High-Quality Recording:** Record directly from your browser in resolutions up to **4K** and frame rates up to **60 FPS**.

### 🛠️ How to Use

1.  **Launch the App:** Simply navigate to the [FrameForge live page](https://charlesmack.github.io/forge/).
2.  **Grant Permissions:** Your browser will ask for permission to access your webcam and microphone. Allow it to begin.
3.  **Adjust Your Look:** Use the controls at the top and bottom of the studio to dial in your desired look.
    -   `Profile` allows you to select a color profile or upload a custom `.cube` LUT.
    -   `Anamorphic` and `Aspect` let you set up your cinematic framing.
    -   `Exposure` and `Focus` offer tools for technical image control.
4.  **Start Recording:** When you're ready, press the large red record button in the bottom center to begin. Your video will be saved as an `.mp4` file.

### ⚙️ Technical Details

FrameForge is built using a modern web stack for maximum performance and compatibility.

-   **Web Technologies:** HTML, CSS, and JavaScript.
-   **Rendering:** Powered by **WebGL**, which handles all real-time color grading and effects directly on the GPU. This ensures smooth performance even at high resolutions.
-   **Recording:** The app uses the **MediaRecorder API** to capture the processed video stream, which can be saved locally or downloaded.
-   **Storage:** Custom LUTs and user preferences are stored securely in **IndexedDB** within your browser.

### 🗺️ Roadmap

-   [ ] Add more built-in cinematic LUTs.
-   [ ] Implement audio controls and monitoring.
-   [ ] Optimize performance for lower-end devices.
-   [ ] Introduce a desktop application for offline use.

### 🤝 Contributing

This project is open-source. Feel free to fork the repository, submit pull requests, or open issues to report bugs or suggest new features. We welcome all contributions!

### 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for details.
