# 🤖 Daily AI Lessons

An interactive web application that generates fresh, up-to-date AI and tech lessons every day using Claude AI. Learn something new about artificial intelligence with each click!

## ✨ Features

- **Unlimited Fresh Lessons** - Powered by Claude API to generate current, relevant AI/tech content
- **Smart Topic Tracking** - Avoids repeating recent topics for diverse learning
- **PDF Export** - Save your favorite lessons as PDFs for offline reading
- **Beautiful UI** - Clean, modern design with smooth animations
- **Always Current** - Lessons are generated in real-time, reflecting the latest in AI (February 2025)
- **Zero Setup** - Just visit the page and start learning!

## 🚀 Live Demo

Visit: [https://your-username.github.io/ai-daily-lessons/](https://your-username.github.io/ai-daily-lessons/)

*(Replace with your actual GitHub Pages URL)*

## 📚 What You'll Learn

Topics include:
- Latest AI model releases and capabilities
- Prompt engineering techniques
- RAG (Retrieval-Augmented Generation) systems
- AI agents and tool use
- Vision-language models
- AI safety and ethics
- Practical implementation tips
- Emerging AI applications
- And much more!

## 🎯 How to Use

1. Click **"Get Today's Lesson"** to generate a fresh AI/tech lesson
2. Read and learn something new!
3. Click **"Export as PDF"** to save lessons you like
4. Come back daily for continuous learning

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **AI**: Claude Sonnet 4 via Anthropic API
- **PDF Generation**: jsPDF library
- **Styling**: Custom CSS with gradient backgrounds and animations
- **Hosting**: GitHub Pages

## 💻 Local Development

To run locally:

1. Clone this repository
```bash
git clone https://github.com/your-username/ai-daily-lessons.git
cd ai-daily-lessons
```

2. Start a local server (required for API calls to work):
```bash
# Using Python 3
python3 -m http.server 8000

# Or using Python 2
python -m SimpleHTTPServer 8000

# Or using Node.js
npx http-server
```

3. Open browser to `http://localhost:8000`

**Note**: Simply opening the HTML file directly (file://) won't work due to CORS restrictions on API calls.

## 🔧 Customization

Want to modify the lessons? Edit the prompt in the `getNewLesson()` function to:
- Focus on specific AI topics
- Adjust lesson length
- Change the difficulty level
- Target specific audiences

## 📝 License

MIT License - Feel free to use, modify, and share!

## 🙏 Credits

- Built with [Claude](https://claude.ai) by Anthropic
- PDF generation by [jsPDF](https://github.com/parallax/jsPDF)

## 🤝 Contributing

Found a bug or have a suggestion? Feel free to open an issue or submit a pull request!

## 📧 Contact

Created by [Your Name] - [your-email@example.com]

---

⭐ **Star this repo if you find it helpful!** ⭐

**Happy Learning! 🚀**
