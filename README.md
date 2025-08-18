# Glass Clock - A Modern Glassmorphism Analog Clock

A beautifully designed, interactive analog clock built with modern web technologies. This project showcases a stunning glassmorphism effect, complete with dynamic shadows, highlights, and reflections. It features a real-time, fully customizable interface controlled by a sleek settings panel.

![Glass Clock Screenshot](https://i.ibb.co/5hb6xNGC/Screenshot-2025-08-18-175705.png)

---

## ✨ Features

*   **Stunning Glassmorphism UI**: Utilizes modern CSS to create a realistic "glass" look with `backdrop-filter`, complex gradients, and layered shadows.
*   **Live Analog Clock**: Accurately displays the current time (hardcoded to the Kolkata timezone) with hour, minute, and second hands.
*   **Interactive Settings Panel**: Powered by **Tweakpane**, allowing real-time customization of the clock's appearance.
*   **Deep Customization**:
    *   Adjust the opacity of minute markers, reflections, and glossy effects.
    *   Toggle the visibility of the hour numbers.
    *   Control the intensity of inner and outer shadows.
    *   Modify the colors of the clock hands, numbers, and markers.
    *   Change the lighting angles for dynamic highlight and shadow effects.
*   **Multiple Second-Hand Animations**: Choose between several animation modes for the second hand:
    *   **Smooth Movement**: A continuous, fluid sweep.
    *   **Tick Every Second**: Classic one-tick-per-second movement.
    *   **Half-Second Ticks**: A faster, two-tick-per-second movement.
    *   **High-Frequency Sweep**: An ultra-smooth sweep with 8 ticks per second.
*   **Keyboard Shortcut**: Press <kbd>H</kbd> to easily toggle the visibility of the settings panel.

---

## 🛠️ Technologies Used

*   **HTML5**: Semantic structure for the clock face and its components.
*   **CSS3**: Advanced styling for the glassmorphism effect, including:
    *   CSS Custom Properties (Variables)
    *   `@property` for smooth animation of gradients and angles
    *   `backdrop-filter` for the frosted glass look
    *   `transform` for rotating the clock hands
*   **Modern JavaScript (ES Modules)**:
    *   Dynamically generates clock markers and numbers.
    *   Calculates and applies real-time rotations for the clock hands.
    *   Manages the different animation loops using `requestAnimationFrame` and `setTimeout`.
    *   Handles user interaction and updates CSS variables.
*   **Tweakpane**: A lightweight and powerful library used to create the interactive settings panel.

---

## 🚀 How to Run Locally

This project uses JavaScript Modules (`import` syntax), which requires it to be run from a web server due to browser security policies (Same-Origin Policy). Opening the `html.html` file directly will not work.

The easiest way to run this project is by using Python's built-in web server.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    ```

2.  **Navigate into the project directory:**
    ```bash
    cd your-repo-name
    ```

3.  **Start the local server:**
    *   If you have Python 3 (most common):
        ```bash
        python -m http.server
        ```
    *   If you have an older version of Python 2:
        ```bash
        python -m SimpleHTTPServer
        ```

4.  **Open the project in your browser:**
    *   Navigate to **[http://localhost:8000/html.html](http://localhost:8000/html.html)**


## 📜 License

This project is open-source and available under the [MIT License](LICENSE).
