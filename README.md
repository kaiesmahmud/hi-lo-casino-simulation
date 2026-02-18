# hi-lo-casino-simulation
# 📬 Contact: kaiesmahmudnehal@gmail.com

---

# 🎰 Hi-Lo Casino — Demo UI with Casino Algorithm

A fully functional **Hi-Lo card game** built as a frontend demo showcasing real casino-style game logic, animated UI, and a house profit algorithm — all in a single HTML file with zero dependencies.

---

## 🚀 What This Demo Shows

### UI & Frontend Skills
- Smooth **3D card flip animations** using pure CSS `perspective` + `rotateY`
- Responsive layout — works on **mobile portrait, landscape, tablet, and desktop**
- Custom casino aesthetic using **CSS variables, Google Fonts (Cinzel), and keyframe animations**
- Progress tracker, round timer with SVG ring, chip selector, win/loss overlays
- All built with **vanilla HTML, CSS, and JavaScript** — no frameworks, no libraries

### Casino Algorithm Logic
- **52-card deck** shuffled fresh each match (Fisher-Yates algorithm)
- Cards dealt without repeat — each round pulls from the **remaining deck** (51 → 50 → 49...)
- **5 rounds per match** — player must win 3+ rounds to double their bet
- **15-second timer** per round with auto-guess on timeout
- **Profit Shield Algorithm** — house monitors giveaway pool and profit threshold:
  - If payout would exceed the giveaway balance → forced loss mode activates
  - If house profit drops below threshold → forced loss mode activates
  - Admin debug panel shows live algorithm state (Safe Mode / Forced Loss Mode)
- Pool split: **40% giveaway** | **40% house profit** | **20% dev fee**

---

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, 3D transforms, keyframes) |
| Logic | Vanilla JavaScript (ES6+) |
| Persistence | localStorage |
| Fonts | Google Fonts (Cinzel, Cinzel Decorative, Rajdhani) |

---

## 💡 Use Cases This Pattern Supports

- **Web3 / On-chain casino games** — same algorithm can be ported to Solidity smart contracts
- **Provably fair gaming** — deck shuffle logic is auditable and replaceable with VRF
- **Frontend for blockchain dApps** — React/Next.js version ready to connect to wallet + contract
- **Demo for investors / clients** — full working product in a single file

---

## 👨‍💻 About the Developer

CS student with **4+ years of web development experience**.

**Skills:** React · Next.js · TypeScript · JavaScript · Node.js · Express · MongoDB · Firebase · TailwindCSS · ShadCN · HTML/CSS · Linux

Currently learning **Solidity + Rust** for blockchain/Web3 development — targeting remote opportunities.

Open to: **Remote frontend roles · Web3/DApp development · Casino/gaming UI contracts**

---

# 📬 Contact: kaiesmahmudnehal@gmail.com
