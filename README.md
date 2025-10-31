# AI Research Agent

A simple, elegant web application that provides an AI-powered research assistant through an embedded chatbot interface powered by VectorShift.

## 🌟 Overview

The AI Research Agent is designed to help users discover insights, answer research queries, and streamline information searches using cutting-edge AI capabilities. The application features a clean, user-friendly interface with an embedded AI chatbot that appears in the bottom-right corner of the page.

## 🚀 Features

- **AI-Powered Research Assistant**: Integrated VectorShift chatbot for intelligent research assistance
- **Responsive Design**: Clean and modern UI that works across different screen sizes
- **Fixed Chat Window**: Convenient bottom-right positioned chat interface
- **Microphone Support**: Voice input capabilities through the embedded chatbot
- **Clipboard Access**: Enhanced interaction with clipboard read/write permissions

## 🛠️ Technology Stack

- **Frontend**: Pure HTML5 + CSS3
- **AI Integration**: VectorShift Embedded Chatbot
- **Deployment**: Vercel (configured with `vercel.json`)

## 📁 Project Structure

```
NC_ResearcherBot_VectorShift/
├── index.html          # Main landing page
├── researcher.html     # Research agent page
├── vercel.json        # Vercel deployment configuration
└── README.md          # Project documentation
```

## 🎨 Design Features

- Modern, minimalist interface with a clean white content container
- Soft shadow effects for visual depth
- Responsive container (max-width: 800px)
- Professional color scheme:
  - Background: `#f4f4f4`
  - Primary text: `#333`
  - Secondary text: `#555`
- Fixed-position chat widget (400px × 500px)

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection (for VectorShift chatbot integration)

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/FarhanAkhtar121/NC_ResearcherBot_VectorShift.git
   cd NC_ResearcherBot_VectorShift
   ```

2. Open `index.html` in your web browser:
   ```bash
   open index.html
   ```

   Or simply double-click the `index.html` file.

### Deployment

The project is configured for Vercel deployment:

1. Install Vercel CLI (optional):
   ```bash
   npm install -g vercel
   ```

2. Deploy:
   ```bash
   vercel
   ```

The `vercel.json` configuration ensures proper static file serving.

## 🤖 VectorShift Integration

The application integrates a VectorShift chatbot with the following configuration:
- **Chatbot ID**: `67cac98003e47f63aff6d8b6`
- **Auto-open**: Enabled (`openChatbot=true`)
- **Permissions**: Clipboard read/write, microphone access

## 📝 Usage

1. Visit the application in your web browser
2. Locate the chat window in the bottom-right corner
3. Start typing your research queries
4. Use the microphone feature for voice input (if enabled)
5. Receive AI-powered responses and insights

## 🔧 Customization

### Modify Chatbot Settings

To change the chatbot configuration, update the iframe `src` in `index.html`:
```html
<iframe
    src="https://app.vectorshift.ai/chatbots/embedded/YOUR_CHATBOT_ID?openChatbot=true"
    ...>
</iframe>
```

### Adjust Styling

Modify the `<style>` section in `index.html` to customize:
- Colors and fonts
- Container dimensions
- Chat window size and position
- Shadow effects and borders

## 🌐 Browser Compatibility

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)

## 📄 License

This project is available for use and modification. Please check with the repository owner for specific licensing terms.

## 👤 Author

**Farhan Akhtar**
- GitHub: [@FarhanAkhtar121](https://github.com/FarhanAkhtar121)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## 📞 Support

For support or questions, please open an issue in the GitHub repository.

---

**Note**: This application requires an active internet connection to communicate with the VectorShift AI service.
