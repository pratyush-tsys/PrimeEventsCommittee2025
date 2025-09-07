# Prime Events Committee Chatbot

A modern, interactive web-based chatbot designed to provide information about the Prime Events Committee and assist visitors with their questions.

## Features

- 🤖 **Interactive Chat Interface** - Clean, modern design with smooth animations
- 💬 **Intelligent Responses** - Pre-programmed responses for common questions
- 📱 **Mobile Responsive** - Works perfectly on all devices
- ⚡ **Quick Question Buttons** - Fast access to common queries
- 🎨 **Beautiful UI** - Modern gradient design with professional styling
- 🔄 **Real-time Typing Indicators** - Shows when the bot is "thinking"

## What the Chatbot Can Answer

### Event Information
- What events does the committee organize?
- When is the next event?
- Upcoming event schedules
- Event types and categories

### Committee Information
- How to join the committee
- Committee structure and departments
- About the organization
- Mission and values

### Services
- Event planning services
- What the committee offers
- Service categories

### Contact Information
- Phone numbers and email
- Office address and hours
- Website and social media

## Files Structure

```
chatbot/
├── index.html          # Main HTML file with chatbot interface
├── styles.css          # CSS styling for modern, responsive design
├── script.js           # JavaScript functionality and chatbot logic
└── README.md          # This documentation file
```

## How to Use

### Local Usage
1. Open `index.html` in any modern web browser
2. The chatbot will load automatically
3. Start typing questions or use the quick question buttons

### Sharing as Web Link
To share this chatbot online, you have several options:

#### Option 1: GitHub Pages (Free)
1. Create a GitHub repository
2. Upload all files to the repository
3. Go to repository Settings → Pages
4. Select source branch (usually `main`)
5. Your chatbot will be available at: `https://username.github.io/repository-name`

#### Option 2: Netlify (Free)
1. Create account at netlify.com
2. Drag and drop your chatbot folder to Netlify
3. Get instant URL like: `https://random-name.netlify.app`

#### Option 3: Vercel (Free)
1. Create account at vercel.com
2. Connect your GitHub repository or upload files
3. Get URL like: `https://project-name.vercel.app`

#### Option 4: Traditional Web Hosting
Upload all files to any web hosting service (shared hosting, VPS, etc.)

## Customization

### Adding New Responses
Edit the `responses` object in `script.js`:

```javascript
const responses = {
    'your question': "Your response here",
    // Add more responses...
};
```

### Adding New Keywords
Edit the `keywords` object in `script.js`:

```javascript
const keywords = {
    newCategory: ['keyword1', 'keyword2', 'keyword3'],
    // Add more keyword categories...
};
```

### Styling Changes
Modify `styles.css` to change:
- Colors and gradients
- Fonts and typography
- Layout and spacing
- Animations and effects

### Content Updates
Update the information in `responses` object to match your:
- Event schedules
- Contact information
- Committee details
- Services offered

## Browser Compatibility

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

## Technical Details

- **Pure HTML/CSS/JavaScript** - No external dependencies
- **Responsive Design** - Mobile-first approach
- **Progressive Enhancement** - Works even with JavaScript disabled
- **Accessibility** - Keyboard navigation and screen reader friendly
- **Performance** - Lightweight and fast loading

## Quick Start Commands

If you have a local web server, you can run:

```bash
# Using Python 3
python -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (if you have npx)
npx serve .

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## Support

For questions about customizing or deploying this chatbot, you can:
1. Refer to the comments in the code files
2. Check online documentation for HTML/CSS/JavaScript
3. Use browser developer tools for debugging

## License

This chatbot is provided as-is for the Prime Events Committee. Feel free to modify and customize according to your needs.

---

**Created for Prime Events Committee 2025**
*Making every event memorable!* ✨
