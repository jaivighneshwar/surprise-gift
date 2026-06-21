# 🎰 Experience Roulette
**Experience Roulette** is an ultra-precise, high-density spatial discovery web application designed for discerning explorers. By stripping away text clutter and unifying geographical telemetry, real-time map tracking, transit metrics, and vibe categories into a single, seamless user interface, it replaces decision fatigue with pure, calculated serendipity.

---

## 🛠️ Advanced Precision Features

* **Geographic Control & Constraints Deck:** All parameters (map telemetry, dual-routing scenarios, price tiers, and time picking inputs) are unified into a space-saving, dense control panel directly below the map canvas for a clean, linear user flow.
* **Dual Routing Constraint Engines:** 
  * **Scenario 1 (Radius):** Enforces a strict physical distance boundary around your coordinates.
  * **Scenario 2 (Transit):** Translates travel time directly into spatial bounds using hardcoded urban velocity constants for **🚗 Driving**, **🚊 Public Transit**, or **🚶‍♂️ Walking**.
* **High-Density Vibe Classification:** Ditch generic categories. Select from beautifully organized, sleek mood tiles spanning aesthetic media vantage points, wilderness exploration, gastronomy hubs, leisure wellness, and culture matrices.
* **Gastronomy Profile Deck:** Activating dining options reveals a sub-deck to instantly tailor results by specific cuisines (Indian, Italian, Asian, French, Regional).
* **Multi-Platform Map Deep-Linking:** The synthesis engine pairs active coordinates, dates, times, and maximum budget tiers directly with advanced search arrays, instantly bridging to **Google Maps** or **Apple Maps**.
* **Digital Passport & Group Dispatch:** Lock your chosen venue to generate an elite, custom destination passport complete with a live-rendered vector QR code. Copy the styled manifest text instantly to your clipboard and forward it straight to a dedicated WhatsApp group.
* **Surprise Me Engine 🎲:** Feeling entirely indecisive? Tap **Surprise** to instantly randomize your spatial constraints, transit modes, budget tier, and category selections.

---

## 🚀 Tech Stack

This application is built entirely as a dependency-contained, lightweight, vanilla front-end system:
* **Styling & UI:** Pure CSS3 featuring high-density grid layouts, fluid micro-interactions, hardware-accelerated transitions, and responsive scaling tailored for mobile viewports (`viewport-fit=cover`).
* **Typography:** Google Fonts integration (*Montserrat* & *Cormorant Garamond*).
* **Mapping Interface:** Leaflet.js paired with lightweight, clean, vector-style tile coordinates provided by **CartoDB Voyager**.
* **Geocoding Engine:** Leaflet Control Geocoder running over the **Nominatim** indexing engine for fast landmark and suburb text resolutions.
* **QR Encoding:** Client-side vector generation powered by `QRCode.js`.

---

## 📦 Installation & Deployment

Because the application is fully self-contained within a single web architecture file, it requires **zero compilation**, zero package managers, and zero server environments to operate.
1. **Clone or Copy:** Save the codebase as an `index.html` file on your filesystem.
2. **Launch:** Double-click the file to open it directly in any modern mobile or desktop browser (Safari, Chrome, Edge, Firefox).
3. **Deploy:** Drop the single file onto free static hosting platforms like GitHub Pages, Vercel, or Netlify for instant access anywhere.

---

## 🔧 How It Works

1. **Anchor:** Set your focus area using the map canvas, text entry search, or the integrated hardware GPS pin.
2. **Constrain:** Choose your routing constraints (Strict Radius or Commute Threshold), set your date/time window, and pick a maximum financial tier.
3. **Classify:** Tap your preferred Discovery Vibe profile to instantly focus target keywords.
4. **Synthesize:** Click **Synthesize Parameters ✨** to generate strict platform deep-links for Google or Apple Maps.
5. **Lock & Passport:** Browse verified live listings, enter your final choice into the text input, and generate your custom digital pass and destination QR code. 

---

## ⚙️ Configuration & Customization

### Updating the WhatsApp Share Target
To route the generated **Destination Passports** directly to your own group chat or event thread, update the integration URL inside the script block:
1. Open `index.html` in your text editor.
2. Locate the `copyPassportAndLaunchGroup()` function near the bottom of the file.
3. Replace the sample `targetWhatsAppGroupChatUrl` string with your own **WhatsApp Group Invite Link**:
```javascript
   const targetWhatsAppGroupChatUrl = "[https://chat.whatsapp.com/YOUR_GROUP_INVITE_ID](https://chat.whatsapp.com/YOUR_GROUP_INVITE_ID)";
'''

---

### Adjusting Transit Velocities
If your target area features faster highway networks or slower rural pathways, you can fine-tune the urban velocities used to compute transit matrices. Locate refreshSpatialCanvasVector() and compileSpatialDiscoveryEngine() to update these hardcoded km/h limits:
Walking Speed: Defaulted to 4.5 km/h.
Public Transit Speed: Defaulted to 22 km/h.
Driving Speed: Defaulted to 40 km/h.

---

## 🔒 Privacy & Permissions

**Location Access:** Device location services are requested via standard, sandboxed browser tools. If you decline access, the application functions perfectly by letting you search a city or interact with the map manually.

**Data Integrity:** This app runs 100% client-side. No search parameters, location coordinates, or selection paths are ever transmitted to or stored on an external database. Your destination choices remain strictly yours.