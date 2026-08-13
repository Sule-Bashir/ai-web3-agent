# 🤖AI Web3 Agent - Mobile-First On-Chain Assistant

[![Live Demo](https://img.shields.io/badge/Live_Demo-✅_Vercel-000?style=for-the-badge&logo=vercel)](https://ai-web3-agent.vercel.app)
[![GitHub](https://img.shields.io/badge/GitHub-📦_Repository-181717?style=for-the-badge&logo=github)](https://github.com/Sule-Bashir/ai-web3-agent)

> An AI-powered Web3 assistant that understands natural language commands and converts them into blockchain actions like swaps, transfers, bridges, and balance checks. Built entirely on an Android phone using Termux, proving that Web3 development can be truly accessible and mobile-first.

---

## 🏆 Hackathon

**NTU InnovateX Hackathon 2026**
- **Track:** Track 2: Web3 Applications, AI Agents and Real-World Use Cases
- **Co-organised by:** NTU Centre in Computational Technologies for Finance (CCTF) and SNZ
- **Status:** ✅ Submitted

---

## 🌐 Live Demo

**Try it now:** [https://ai-web3-agent.vercel.app](https://ai-web3-agent.vercel.app)

---

## 📋 Table of Contents

- [About the Project](#-about-the-project)
- [Features](#-features)
- [How It Works](#-how-it-works)
- [Technologies Used](#-technologies-used)
- [Installation](#-installation)
- [Usage](#-usage)
- [Project Structure](#-project-structure)
- [Development Journey](#-development-journey)
- [Challenges & Solutions](#-challenges--solutions)
- [What's Next](#-whats-next)
- [Contributing](#-contributing)
- [License](#-license)
- [Acknowledgments](#-acknowledgments)

---

## 📖 About the Project

### Problem
Web3 technology promises to revolutionize finance and digital ownership, but its interfaces remain overwhelmingly complex. New users are confronted with confusing dashboards, technical jargon, gas fees, and long hexadecimal addresses. This creates a significant barrier to entry for mainstream adoption.

### Solution
**AI Web3 Agent** bridges the gap between blockchain power and conversational simplicity. Users simply type what they want to do in natural language, and the AI agent:
- Understands the intent behind commands
- Extracts key information (amounts, tokens, addresses)
- Prepares blockchain transactions
- Provides clear, user-friendly responses with gas estimates

### Innovation
This project demonstrates that you don't need a laptop to build Web3 applications. The entire prototype was developed on an Android phone using Termux, showing that:
- ✅ Web3 development can be truly accessible
- ✅ Mobile-first development is the future
- ✅ AI agents can simplify blockchain interaction
- ✅ Low-barrier entry for new developers

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 💱 **Swaps** | Convert between tokens like USDC and ETH with estimated rates |
| 📤 **Transfers** | Send tokens to any wallet address with gas fee previews |
| 🌉 **Bridges** | Move assets across chains like Arbitrum and Base |
| 💰 **Balance Checks** | Instantly view wallet holdings across multiple tokens |
| 🔗 **Wallet Connection** | Simulate connecting a Web3 wallet with live status |
| 📜 **Command History** | Track all interactions for easy reference |
| 📱 **Mobile-First** | Responsive design optimized for mobile devices |
| 🎨 **Professional UI** | Gradient-themed interface with glassmorphism effects |

---

## 🔧 How It Works

```
┌─────────────────────────────────────────────────────────────────┐
│                     USER INTERFACE                              │
│  ┌─────────────────────────────────────────────────────────┐    │
│  │  "Swap 10 USDC to ETH"  [Execute]                       │    │
│  └─────────────────────────────────────────────────────────┘    │
│                              │                                   │
│                              ▼                                   │
│  ┌─────────────────────────────────────────────────────────┐    │
│  │                    COMMAND PARSER                        │    │
│  │  • Identifies action (swap, send, bridge, balance)      │    │
│  │  • Extracts amount, token, address, chain              │    │
│  └─────────────────────────────────────────────────────────┘    │
│                              │                                   │
│                              ▼                                   │
│  ┌─────────────────────────────────────────────────────────┐    │
│  │                      AI AGENT                            │    │
│  │  • Processes natural language                          │    │
│  │  • Generates structured response                       │    │
│  │  • Simulates transaction preparation                   │    │
│  └─────────────────────────────────────────────────────────┘    │
│                              │                                   │
│                              ▼                                   │
│  ┌─────────────────────────────────────────────────────────┐    │
│  │                    RESPONSE                              │    │
│  │  ✅ SWAP ORDER READY                                    │    │
│  │  📊 Amount: 10 USDC                                     │    │
│  │  🔄 To: ETH                                             │    │
│  │  💡 Estimated rate: 1 USDC ≈ 0.0012 ETH                │    │
│  │  ⛓️ Network: Arbitrum Sepolia                           │    │
│  └─────────────────────────────────────────────────────────┘    │
└─────────────────────────────────────────────────────────────────┘
```

---

## 🛠️ Technologies Used

### Frontend
- **HTML5** - Semantic markup structure
- **CSS3** - Mobile-first responsive design with glassmorphism
- **JavaScript (Vanilla)** - Zero-dependency logic and interactivity

### Development Environment
- **Termux** - Android terminal emulator for mobile development
- **Python** - Simple HTTP server for local testing

### Deployment
- **Vercel** - Static site hosting and deployment
- **GitHub** - Version control and code hosting

### Tools & Platforms
- **Git** - Version control
- **GitHub Personal Access Tokens** - Secure authentication

---

## 📦 Installation

### Option A: Run Locally

```bash
# Clone the repository
git clone https://github.com/Sule-Bashir/ai-web3-agent.git

# Navigate to project directory
cd ai-web3-agent

# Start a local server (Python)
python -m http.server 8080

# Open in browser
# http://localhost:8080
```

### Option B: Using Termux (Android)

```bash
# Install Termux from F-Droid or Google Play Store

# Update packages
pkg update && pkg upgrade

# Install Python
pkg install python

# Clone and run
git clone https://github.com/Sule-Bashir/ai-web3-agent.git
cd ai-web3-agent
python -m http.server 8080
```

### Option C: Live Demo (No Installation)

Visit: **[https://ai-web3-agent.vercel.app](https://ai-web3-agent.vercel.app)**

---

## 🚀 Usage

### Example Commands

| Command | What It Does |
|---------|--------------|
| `Swap 10 USDC to ETH` | Swaps 10 USDC for ETH |
| `Send 5 USDT to 0x123...` | Sends 5 USDT to specified address |
| `Bridge 1 ETH from Arbitrum to Base` | Bridges ETH from Arbitrum to Base |
| `Check my balance` | Shows wallet balances |

### Quick Start

1. **Open the app** (local or live demo)
2. **Type a command** in natural language
3. **Click Execute** or press Enter
4. **Review the response** with transaction details
5. **Connect Wallet** to simulate wallet integration
6. **View History** to see past commands

---

## 📁 Project Structure

```
ai-web3-agent/
│
├── index.html          # Main application file (single-page app)
├── package.json        # Project configuration
├── vercel.json         # Vercel deployment configuration
└── README.md          # Project documentation
```

---

## 🧠 Development Journey

### Built on Mobile with Termux

This project was developed entirely on an Android phone using Termux, demonstrating:

1. **Setup:** Installed Node.js, Python, and Git in Termux
2. **Coding:** Wrote HTML, CSS, and JavaScript directly in the terminal using Vim/nano
3. **Testing:** Used Python HTTP server for local testing
4. **Version Control:** Committed changes to GitHub using Git
5. **Deployment:** Deployed to Vercel for live hosting

### Development Timeline

| Phase | Activity |
|-------|----------|
| 1 | Project planning and requirements analysis |
| 2 | HTML structure and CSS design |
| 3 | JavaScript logic and command parsing |
| 4 | UI enhancements and mobile optimization |
| 5 | Local testing and debugging |
| 6 | GitHub setup and version control |
| 7 | Vercel deployment and testing |
| 8 | Hackathon submission preparation |

---

## ⚠️ Challenges & Solutions

### Challenge 1: Mobile Development Constraints
**Issue:** Building on Termux with limited resources and network timeouts  
**Solution:** Used lightweight vanilla JS, optimized dependencies, and Personal Access Tokens for authentication

### Challenge 2: Deployment Failures
**Issue:** Next.js build failures due to Tailwind CSS dependency conflicts on Vercel  
**Solution:** Switched to simple static HTML deployment with "Other" framework preset

### Challenge 3: Natural Language Parsing
**Issue:** Creating a robust parser for various command phrasings  
**Solution:** Designed comprehensive regex patterns with fallback responses

### Challenge 4: Network Reliability
**Issue:** Persistent npm timeout issues on Termux  
**Solution:** Used `--legacy-peer-deps` flag and alternative registry configurations

### Challenge 5: Time Constraint
**Issue:** Building a complete prototype within hackathon deadline  
**Solution:** Focused on MVP with core functionality (swaps, sends, bridges, balance)

---

## 🚀 What's Next

- [ ] **Real Blockchain Integration:** Connect to actual networks (Base Sepolia, Arbitrum Sepolia)
- [ ] **WalletConnect Implementation:** Real wallet connection with MetaMask, Trust Wallet
- [ ] **AI Model Integration:** Replace pattern matching with actual LLM APIs (Venice AI, OpenAI)
- [ ] **Multi-Chain Support:** Expand to Ethereum, Polygon, Optimism
- [ ] **Voice Commands:** Speech-to-text for hands-free interaction
- [ ] **Transaction History:** Store and display past on-chain transactions
- [ ] **DeFi Aggregation:** Integrate with 1inch, Paraswap for best-price routing
- [ ] **PWA Support:** Progressive Web App for native-like experience
- [ ] **User Accounts:** Authentication to save preferences and history
- [ ] **Education Mode:** Tooltips and explanations for Web3 onboarding

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Commit** changes (`git commit -m 'Add amazing feature'`)
4. **Push** to branch (`git push origin feature/amazing-feature`)
5. **Open** a Pull Request

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- **NTU InnovateX Hackathon 2026** - For the opportunity and inspiration
- **NTU Centre in Computational Technologies for Finance (CCTF)** - For organizing the event
- **SNZ** - For co-organizing and supporting the hackathon
- **Termux Community** - For making mobile development accessible
- **Vercel** - For free hosting and deployment
- **GitHub** - For version control and code hosting

---

## 📞 Contact

**Developer:** Sule Bashir  
**Email:** sulebashir001@gmail.com  
**GitHub:** [@Sule-Bashir](https://github.com/Sule-Bashir)

---

## 📸 Screenshots

| Feature | Screenshot |
|---------|------------|
| Home Screen | [Add screenshot] |
| Swap Command | [Add screenshot] |
| Send Command | [Add screenshot] |
| Bridge Command | [Add screenshot] |
| Balance Check | [Add screenshot] |
| Wallet Connected | [Add screenshot] |
| Command History | [Add screenshot] |

---

## 📊 Badges

![Built with Love](https://img.shields.io/badge/Built_With-❤️-red?style=for-the-badge)
![Mobile First](https://img.shields.io/badge/Mobile_First-✅_Yes-4CAF50?style=for-the-badge)
![Termux](https://img.shields.io/badge/Built_On-Termux-000?style=for-the-badge&logo=android)
![Vercel](https://img.shields.io/badge/Deployed_On-Vercel-000?style=for-the-badge&logo=vercel)
![GitHub](https://img.shields.io/badge/Hosted_On-GitHub-181717?style=for-the-badge&logo=github)

---

**⭐ Star this repository if you found it interesting!**

---

*Built for NTU InnovateX Hackathon 2026 • Track 2: Web3 Applications, AI Agents and Real-World Use Cases*
```

