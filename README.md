# FLOW - Browser Extension

FLOW is an intelligent Chrome extension powered by Agno and Browser Use that supercharges your browsing experience with cutting-edge AI tools — empowering you to create, analyze, and learn faster than ever.

## Features

## 1. Context Menu Features
Right-click anywhere on a webpage to access powerful tools:

### 🔍 Analyze Element  
Easily inspect and understand any element on a webpage — powered by **Agno**.  

**How to use:**  
1. Right-click anywhere in Chrome.  
2. Go to **Flow → Analyze Element**.  
3. Your cursor will switch to the **Element Picker**.  
4. Click on any element — image, text, or paragraph — to get instant, AI-powered insights.


### 🌐 Translate Text  
Translate any text element on a webpage directly into your chosen language — seamlessly integrated into the page.

**Supported languages:**  
- Spanish 🇪🇸  
- French 🇫🇷  
- German 🇩🇪  
- Japanese 🇯🇵  
- Chinese 🇨🇳  
- Russian 🇷🇺  
- Arabic 🇸🇦  
- Hindi 🇮🇳

**How to use:**  
1. Right-click anywhere on a webpage in Chrome.  
2. Go to **Flow → Translate Text**, then select your target language.  
3. Your cursor will switch to the **Element Picker**.  
4. Click on any text element — a sentence, paragraph, or entire content block.  
5. The selected text will be instantly translated and **replaced in the page DOM**, right where it was.

*No popups. No distractions. Just seamless in-place translation.*


### 🤖 Flowy  
Meet your intelligent in-browser assistant — powered by **Browser Use**.  
**Flowy** is one of the most powerful tools for interacting with your current browser tab — no popups, no switching windows, no distractions.

**What Flowy can help you with:**  
- 🔍 Analyzing page content  
- 📧 Assisting with email writing  
- 📝 Helping fill out forms  
- 📊 Extracting data from web pages  
- 🧠 Summarizing long or complex content  

**How to use:**  
1. Right-click anywhere in Chrome.  
2. Select **Flow → Flowy Assistant**.  
3. Start chatting directly within your current tab context — Flowy understands the page you're on and works right where you need it.

*A seamless, focused AI experience — built right into your browser.*

## 2. Extension Popup Feature

### 🏠 Tab 1: Home  
A quick visual welcome and entry point to all features.

### 🎨 Tab 2: Color Palette

- ✨ Generate color palettes from text prompts (“thoughts”)
- 🖌️ Capture colors from the current web page
- 💾 Save, edit, and manage favorite palettes
- 🤖 AI-powered insights:
  - 🎭 Mood of the palette
  - 🏭 Industry-specific suggestions
  - 🌏 Cultural significance
- 🛠️ Usage recommendations:
  - 🏷️ Logo integration
  - 💻 Responsive web design
  - 🖨️ Print and 🏠 interior design
- ♿ Accessibility analysis:
  - ⚖️ Contrast ratio (WCAG)
  - 👁️‍🗨️ Color blindness simulation
  - 🟢 Accessible alternatives

### 🔤 Tab 3: Font & Vector Generator

- ✍️ Generate font suggestions from a text prompt
- 👀 Preview font cards with live samples
- 🪄 Apply a selected font to the current page (injects font into DOM)
- 📋 Copy font CSS for use elsewhere

- 🪄 Generate vector icons/graphics from a text prompt
- 👁️ Preview generated SVGs
- 📋 Copy SVG code or ⬇️ download SVG files

### 💸 Tab 5: Payment Management

- 🔗 Generate payment links (Razorpay integration)
- 📊 Track payment status in real time
- 🔐 Manage and save API keys securely
- 📋 View and manage all payment links
- 📧 Send payment notifications


### 📝 Tab 6: Content Generation & Analysis

- 🛠️ Generate content:
  - 📰 Blog posts, 🗞️ articles, 📨 newsletters, 📱 social posts
  - 📧 Business emails, 📄 proposals, 🏷️ product descriptions, 📚 case studies
- 🧠 Analyze content:
  - 😊 Sentiment, 🏷️ keywords, 📝 summary, ✏️ grammar
  - 🔍 SEO optimization, 📖 readability, 📈 engagement, 🏆 competitor analysis
- 📋 Copy generated or analyzed content


### 🃏 Tab 7: Flashcard Generation

- ⚡ Generate flashcards from any URL (or current tab)
- 🤖 AI-powered extraction and structuring
- 🃏 Interactive cards:
  - 🔄 Flip, ⏮️⏭️ navigate, 📋 copy, and 🖨️ export as PDF
- 📚 Structured answers: definitions, key points, examples, context

## Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Build the extension:
   ```bash
   npm run build
   ```
4. Load the extension in your browser:
   - Open Chrome
   - Go to `chrome://extensions/`
   - Enable "Developer mode"
   - Click "Load unpacked"
   - Select the `dist` folder

## Usage

1. Click the FLOW extension icon in your browser toolbar
2. Select the desired feature from the tab menu
3. Follow the on-screen instructions for each feature

### Flashcard Generation
1. Click the "Generate Flashcards" button
2. Enter a URL or use the "Current URL" button
3. Click "Generate" to create flashcards
4. Navigate through cards using the Previous/Next buttons
5. Click a card to flip between front and back
6. Use the "Copy" button to copy card content
7. Click "Export All Cards as PDF" to save all cards

## Development

### Frontend Structure
- `popup.html`: Main extension interface
- `popup.js`: Core extension functionality
- `tab7.js`: Flashcard generation feature
- Other tab-specific JavaScript files for different features

### Backend Requirements
- Node.js server running on `localhost:5000`
- Required environment variables:
  - API keys for various services
  - Database configuration

## Contributing
1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License
This project is licensed under the MIT License - see the LICENSE file for details. 