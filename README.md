# 🎰 Experience Roulette
**Experience Roulette** is a premium, live, on-demand discovery web application designed to break the routine and replace decision fatigue with pure serendipity. By combining interactive spatial tracking, real-time map matching, and a sleek, intuitive interface, it transforms finding your next activity into a thrilling, high-end experience.
## ✨ Features
 * **Interactive Spatial Engine:** Set your search anchor via an integrated map. Use a robust text search, place a custom pin manually, or grab your live coordinates directly via device hardware GPS.
 * **Vibe-Driven Curation:** Skip the rigid categories. Choose from 13 distinct curated mood tiles (ranging from **🍿 Movies** and **🧗‍♀️ Action** to **🌿 Escape** and **🍸 After Dark**).
 * **Live Google Maps Deep-Linking:** The "Synthesize Live" engine pairs your active subregional locality data with advanced search strings, instantly bridging you out to verified, high-rating local destinations.
 * **Digital Passport & QR Code Generation:** Lock in your favorite spot and compile a gorgeous, downloadable experience passport complete with an on-the-fly generated vector QR code routing to the location.
 * **Surprise Me Engine:** Feeling entirely indecisive? Tap **Surprise 🎲** to randomise your timeline, budget duration, and category target automatically.
 * **Instant Dispatch:** Seamlessly download a high-fidelity image payload of your ticket pass while auto-copying your invite payload parameters directly to your clipboard for instant sharing.
## 🚀 Tech Stack
This application is built entirely as a dependency-contained, lightweight, vanilla front-end system:
 * **Styling & UI:** Pure CSS3 featuring dynamic backdrop blurs, fluid micro-interactions, hardware-accelerated animations, and responsive layouts tailored heavily for mobile devices.
 * **Typography:** Google Fonts integration (*Montserrat* & *Cormorant Garamond*).
 * **Mapping Interface:** Leaflet.js tied to lightweight, clean, vector-style tiles provided by **CartoDB Voyager**.
 * **Geocoding & Reverse Geocoding:** Leaflet Control Geocoder running over the **Nominatim** indexing engine for robust landmark and suburb text resolutions.
 * **QR Encoding:** QRCode.js for lightweight client-side SVG/Canvas generation.
 * **Canvas Snapshot Rendering:** html2canvas.js for secure image compilation.
## 📦 Installation & Deployment
Because the application is fully self-contained within a single web architecture file, it requires **zero compilation** or server environments to operate.
 1. **Clone or Copy:** Save the codebase as an index.html file on your filesystem.
 2. **Open:** Double-click the file to launch it directly in any modern mobile or desktop browser (Safari, Chrome, Edge, Firefox).
 3. **Deploy (Optional):** Drop the single file directly onto free static hosting platforms like GitHub Pages, Vercel, or Netlify for instant global access.
## 🔧 How It Works
```
[ 🪙 Tap Engine Token ] ➔ [ 📍 Set Location / GPS Anchor ] ➔ [ 🎭 Choose Vibe Tile ]
                                                                        |
[ 🎟️ Get QR Pass & Image ] 🗂️ [ ✍️ Enter Your Pick ] 💎 [ 🔍 View Live Map Options ]

```
 1. **Initialize:** Tap the shimmering engine token on the landing card to start the tracking array.
 2. **Anchor:** Pick your focus area on the map.
 3. **Curate:** Tap your target date, timing parameters, duration budget, and mood.
 4. **Synthesize:** Click **Synthesize Live ✨**. The engine builds a custom query link that opens verified, real-time Google Maps options matching your exact position and vibe.
 5. **Passport Lock:** Pick your favorite venue from the live listings, type its name into the final field, and hit generate. Your exclusive digital pass and custom destination QR code will render instantly.
## 🔒 Privacy & Permissions
 * **Location Access:** Device location services are requested via standard browser standard sandboxes. If you decline access, the application functions perfectly by letting you type a town name or tap the map manually.
 * **Data Integrity:** This app runs **100% client-side**. No search parameters, location coordinates, or selection paths are ever transmitted to or stored on an external server database. Your choices remain strictly yours.
