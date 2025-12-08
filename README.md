# SmritiGate (स्मृति-Gate) 🌌

> **"Relive the Unseen."**
> A Mixed Reality Travel Experience for Meta Quest.

SmritiGate is a browser-based Mixed Reality application that democratizes travel. It allows users to open magical portals in their living room, step into photorealistic 3D scans of the world's most beautiful locations, and discover the emotional stories hidden within them.

**Built for the Meta Horizon Start Developer Competition 2025.**

## 🎥 Demo Video
[YouTube Video](https://youtu.be/qkGHdBAR86g)

## 🌟 Key Features

* **MR Portals:** Seamlessly blend your real room with virtual worlds using Passthrough and Occlusion.
* **Hands-First Interaction:** Use natural pinch gestures to summon "Memory Orbs" and navigate the UI. No controllers required.
* **Accessibility First:** Includes a custom "Elevator UI" and "Walking Simulator" interface, allowing users with limited physical space or mobility to explore vast 3D worlds comfortably.
* **Memory Hotspots:** Discover glowing orbs that unlock stories, audio, and history about the location.

## 🛠️ Tech Stack

* **Framework:** [Immersive Web SDK](https://iwsdk.dev/) (Meta)
* **Engine:** Three.js
* **Language:** TypeScript
* **Build Tool:** Vite
* **Assets:** Optimized GLTF photogrammetry scans (Draco + WebP compression).

## 🚀 How to Run Locally

1.  **Clone the repo:**
    ```bash
    git clone https://github.com/kaushik0010/smritigate.git
    cd smritigate
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

3.  **Run the development server:**
    ```bash
    npm run dev
    ```

4.  **Experience:**
    * Open the link (e.g., `https://localhost:8081`) in your Meta Quest Browser.
    * Or use the **Immersive Web Emulator** extension in Chrome on Desktop.

## 🎮 Controls (Desktop Emulator)

When running the project in a browser without a VR headset (e.g., on `localhost` during development), you can use keyboard and mouse shortcuts to simulate movement and interaction.

| Action | Input |
| :--- | :--- |
| **Move Forward** | `Shift + W` |
| **Move Backward** | `Shift + S` |
| **Strafe Left** | `Shift + A` |
| **Strafe Right** | `Shift + D` |
| **Elevate Up (Fly)** | `Shift + Up Arrow` |
| **Elevate Down** | `Shift + Down Arrow` |
| **Look Around** | Click & Drag Mouse |
| **Interact/Click** | `Left Mouse Button - Left Hand` and `Right Mouse Button - Right Hand` |

## 🔮 Future Roadmap: The "Airbnb for Memories"

SmritiGate is built to scale from a curated experience into a global platform for shared human connection.

### 1. User-Generated Memories (UGC Economy)
* **Upload Your World:** Empower users to capture their own local treasures using mobile photogrammetry (Polycam, Luma AI) and upload them to the SmritiGate cloud.
* **Creator Monetization:** Implement a revenue-sharing model where creators earn a commission every time a user visits their scanned memory. This incentivizes high-quality, authentic captures of rare locations.
* **Quality Assurance:** An AI-assisted review process will ensure all uploaded scans meet performance and visual standards before going live.

### 2. Multimedia Storytelling
* **Embedded Video:** Upgrade Memory Cards to support 2D video playback. Imagine standing on a mountain peak and watching a video of your loved one standing in that exact spot years ago.
* **Spatial Audio Notes:** Allow creators to record voice notes that are spatially anchored to specific objects (e.g., a whisper near a tree, a laugh near a bench).

### 3. Multiplayer "Co-Travel"
* **Shared Presence:** Invite a friend to step through the portal with you. See each other's avatars and voice chat as you explore distant lands together.
* **Guided Tours:** Enable locals to host live, guided virtual tours inside their scanned environments.

### 4. The Souvenir Shelf (Mixed Reality Anchors)
* **Bring It Home:** Allow users to "grab" small 3D objects from the virtual world (like a fox mask or a bamboo shoot) and bring them back into their real room.
* **Persistent Decoration:** Using Mixed Reality Anchors, these souvenirs stay on your real-world desk or shelf, serving as a permanent reminder of your virtual journey.

## ⚠️ Known Issues & Hardware Notes

* **Controller Support:** This experience is heavily optimized for **Hand Tracking** and the **Virtual UI**.
* **Beta Controller Input:** Using physical VR controllers (Touch Controllers) for locomotion is currently experimental and may result in hypersensitive movement speed.
* **Recommendation:** For the intended experience, please put down the controllers and use **Hand Tracking** or the on-screen **UI Buttons** to move.

## 📜 Credits
See [CREDITS.md](./CREDITS.md) for a full list of assets used.