# demo-trading-web-application
**TradePro** is a demo trading platform with real-time candlestick charts, multiple asset classes (crypto, forex, stocks), and $5,000 virtual capital — all built with pure HTML, CSS, and JavaScript. It features live P/L tracking, trade durations, win/loss animations, and a sleek glassmorphic UI for risk-free trading practice.
🚀 Quick Start
Installation

Clone the repository

bashgit clone https://github.com/yourusername/tradepro.git
cd tradepro

Open in browser

bash# Simply open the HTML file
open index.html
# or
start index.html
# or double-click the file
That's it! No build process, no dependencies, no npm install needed!
📁 File Structure
tradepro/
├── index.html          # Complete application (HTML, CSS, JS all-in-one)
└── README.md          # This file
🎮 How to Use
Landing Page

Open index.html in your browser
Explore the features section
Click "Start Demo Trading" to begin

Trading Platform

Select an Asset from the left sidebar
Set Trade Amount using +/- buttons (minimum $10)
Choose Duration (5 seconds to 15 minutes)
Click UP or DOWN to place your trade
Watch Real-Time as your trade progresses
See Results with animated win/loss popups

Trade Mechanics

Win: Get 85% profit (1.85x payout)
Loss: Lose your trade amount
Prediction: Price goes UP (buy) or DOWN (sell)
Duration: Trade closes automatically after selected time

⚙️ Customization
Speed Settings
Make charts faster/slower by editing these values in the JavaScript:
javascript// Update frequency (default: 100ms)
setInterval(() => {
    updatePrices();
    updateCandle();
    updateChart();
}, 100);  // Change to 50 for faster, 200 for slower

// New candle frequency (default: 2 seconds)
setInterval(() => {
    // New candle creation
}, 2000);  // Change to 1000 for faster, 5000 for slower
Volatility Settings
Adjust price movement by editing asset volatility:
javascriptconst assets = {
    'BTC/USD': { base: 58360, volatility: 0.002, emoji: '₿' },
    'ETH/USD': { base: 3200, volatility: 0.0025, emoji: '⟠' },
    // Higher volatility = more price movement
};
Starting Balance
Change demo balance:
javascriptlet balance = 5000;  // Change to any amount
Trade Payout
Adjust win percentage:
javascriptpayout = position.amount * 1.85;  // 85% profit (change 1.85)
🎨 Color Scheme
cssPrimary Gradient: #667eea → #764ba2
Success Green: #10b981
Error Red: #ef4444
Background: #0a0e27
📱 Responsive Design

Desktop: Full 3-column layout (sidebar, chart, trading panel)
Tablet: Optimized 2-column layout
Mobile: Simplified single-column view

🔧 Browser Compatibility

✅ Chrome (recommended)
✅ Firefox
✅ Safari
✅ Edge
✅ Opera

📊 Asset Information
AssetBase PriceVolatilityTypeBTC/USD$58,360HighCryptoETH/USD$3,200HighCryptoEUR/USD$1.0836LowForexGBP/USD$1.2650LowForexAAPL$178.50MediumStockTSLA$242.80HighStock
🎓 Educational Purpose
This is a demo trading platform for educational purposes only.

Not connected to real markets
Uses simulated price movements
Virtual currency only
No real money involved
For learning and practice

🛠️ Technical Details
Technologies Used

HTML5 Canvas for chart rendering
CSS3 animations and transitions
Vanilla JavaScript (ES6+)
No external libraries or frameworks

Performance

Smooth 60 FPS animations
Efficient canvas rendering
Optimized price calculations
Memory-efficient trade management

📈 Features Roadmap

 Add more technical indicators
 Historical trade statistics
 Multiple chart types (line, area)
 Trade strategy builder
 Leaderboard system
 Export trade history
 Dark/Light theme toggle
 Mobile app version

🤝 Contributing
Contributions are welcome! Feel free to:

Fork the repository
Create a feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request

📝 License
This project is licensed under the MIT License - see the LICENSE file for details.
👨‍💻 Author
Your Name

GitHub: @yourusername
Twitter: @yourtwitter

🙏 Acknowledgments

Inspired by professional trading platforms
Built for educational purposes
Designed for aspiring traders

⚠️ Disclaimer
IMPORTANT: This is a demo/educational platform only.

Not financial advice
No real trading occurs
Simulated market conditions
For learning purposes only
Always consult financial advisors for real trading


<p align="center">Made with ❤️ for traders learning to trade</p>
<p align="center">⭐ Star this repo if you found it helpful!</p>
📞 Support
Having issues?

Open an Issue
Check Discussions
Read the Wiki

🎯 Quick Links

Live Demo (if hosted)
Documentation
Report Bug
Request Feature


Happy Trading! 📈💰
