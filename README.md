# FLOW - Browser Extension

FLOW is an intelligent Chrome extension powered by Agno and Browser Use that supercharges your browsing experience with cutting-edge AI tools — empowering you to create, analyze, and learn faster than ever.

## Features

### 1. Context Menu Features
Right-click anywhere on a webpage to access powerful tools:

## 🔍 Analyze Element  
Easily inspect and understand any element on a webpage — powered by **Agno**.  

**How to use:**  
1. Right-click anywhere in Chrome.  
2. Go to **Flow → Analyze Element**.  
3. Your cursor will switch to the **Element Picker**.  
4. Click on any element — image, text, or paragraph — to get instant, AI-powered insights.


## 🌐 Translate Text  
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


## 🤖 Flowy  
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


### 2. Flashcard Generation
Generate educational flashcards from any webpage with a single click.

- **URL Input**: Enter any URL or use the "Current URL" button to generate flashcards from the active tab
- **Smart Generation**: AI-powered content extraction and organization
- **Interactive Cards**: 
  - Click to flip between front and back
  - Navigate through cards using Previous/Next buttons
  - Copy card content with one click
  - Export all cards as PDF
- **Structured Content**:
  - Clear questions on the front
  - Comprehensive answers on the back including:
    - Definitions
    - Key Points
    - Examples
    - Additional Context

### 3. Color Palette Generation
Create and manage color palettes for your design projects.

- Generate color schemes from text descriptions
- Capture colors from web pages
- Save and manage your favorite palettes
- Get color insights and usage recommendations

### 4. Font & Vector Generation
Generate fonts and vector graphics based on your requirements.

- Create custom fonts from descriptions
- Generate vector icons and graphics
- Download SVG files
- Copy SVG code directly

### 5. Content Generation & Analysis
AI-powered content creation and analysis tools.

- Generate various types of content:
  - Blog posts
  - Articles
  - Social media posts
  - Business proposals
  - And more
- Analyze content for:
  - SEO optimization
  - Readability
  - Sentiment
  - Grammar

### 6. Payment Management
Integrated payment processing and tracking.

- Generate payment links
- Track payment status
- Manage payment settings
- Send payment notifications

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