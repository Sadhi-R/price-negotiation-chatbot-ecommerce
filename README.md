# Price Negotiation Chatbot for E-commerce

An intelligent chatbot system designed to handle price negotiations in e-commerce settings, providing a dynamic and interactive experience for customers while maintaining profitable pricing strategies.

## 🌟 Features

- Real-time price negotiation with customers
- Voice interaction capabilities
- Dynamic pricing strategy based on various factors
- User-friendly interface
- Customizable negotiation parameters
- Multi-turn conversation support
- Session management
- Response history tracking

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- Node.js 14.x or higher
- FFmpeg for audio processing

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Sadhi-R/price-negotiation-chatbot-ecommerce.git
cd price-negotiation-chatbot-ecommerce
```

2. Install Python dependencies:
```bash
pip install -r requirements.txt
```

3. Install Node.js dependencies:
```bash
npm install
```

4. Download FFmpeg:
   - Download FFmpeg from [official website](https://ffmpeg.org/download.html)
   - Place the `ffmpeg.exe` file in the `static/audio` directory
   - Alternatively, you can install FFmpeg using package managers:
     - Windows (using Chocolatey): `choco install ffmpeg`
     - macOS (using Homebrew): `brew install ffmpeg`
     - Linux: `sudo apt-get install ffmpeg`

### Environment Setup

1. Create a `.env` file in the root directory
2. Add the following environment variables:
```
OPENAI_API_KEY=your_openai_api_key
PORT=3000
```

## 🎯 Usage

1. Start the server:
```bash
python app.py
```

2. Open your web browser and navigate to:
```
http://localhost:3000
```

3. Start negotiating prices with the chatbot!

## 💡 How It Works

The chatbot uses a sophisticated negotiation algorithm that considers:
- Product base price
- Profit margins
- Customer interaction history
- Market conditions
- Available discounts
- Seasonal factors

The system maintains a balance between customer satisfaction and business profitability through:
- Dynamic price adjustments
- Personalized responses
- Strategic counter-offers
- Intelligent conversation flow

## 🔧 Configuration

You can customize the negotiation parameters in `config.json`:
- Minimum acceptable price
- Maximum discount percentage
- Negotiation strategies
- Response templates

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Authors

- Sadhi R - Initial work - [Sadhi-R](https://github.com/Sadhi-R)

## 🙏 Acknowledgments

- OpenAI for providing the GPT API
- The open-source community for various tools and libraries
- All contributors who have helped to improve this project

## 📞 Support

For support, email [your-email@example.com] or open an issue in the GitHub repository.

## 🔄 Updates

Stay tuned for updates and new features by watching the repository and following the contributors. 