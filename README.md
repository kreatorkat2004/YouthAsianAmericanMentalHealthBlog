# MindBridge 🧠

**Mental Health Resources for Asian American Youth**

Made by Katherine Wu and Aaron Wu

MindBridge is a comprehensive web-based platform designed to provide mental health education, self-assessment tools, and culturally-sensitive resources specifically for Asian American high school students. The platform addresses unique challenges such as cultural stigma, family pressures, and identity struggles while offering a safe, anonymous space for learning and self-reflection.

## 🎯 Mission

To create a safe space where Asian American students can explore mental health challenges, access helpful resources, and find support while breaking down cultural barriers and stigma surrounding mental health discussions.

## ✨ Features

### 📚 Educational Content
- **Understanding Stigma**: Learn about cultural stigma and common myths vs. reality
- **Societal & Family Pressure**: Explore the model minority myth and academic expectations
- **Cultural Identity Struggles**: Navigate the challenges of being caught between cultures
- Interactive tabbed interface for easy navigation between topics

### 🔍 Self-Assessment Tools
- **Mental Health Quiz**: Anonymous self-assessment with personalized results and recommendations
- **Interactive Mood Wheel**: Visual mood tracking with 8 different emotional states and personalized feedback
- **Reflective Writing Prompts**: 33 carefully crafted prompts for emotional processing and self-reflection

### 🤝 Resource Directory
- **Crisis Resources**: Immediate help hotlines and emergency contacts
- **Professional Support**: Culturally competent therapists and mental health organizations
- **Online Resources**: Apps, websites, and digital tools for mental wellness
- **Support Groups**: Peer support and community connections
- **Educational Materials**: Trusted sources for mental health information

### 📝 Feedback System
- Embedded Google Forms for user feedback and platform improvement
- Anonymous data collection to enhance user experience

## 🛠️ Technical Specifications

### Frontend
- **Pure HTML5, CSS3, and JavaScript** - No external frameworks required
- **Responsive Design** - Optimized for desktop, tablet, and mobile devices
- **Modern CSS Features**:
  - CSS Grid and Flexbox layouts
  - Gradient backgrounds and glassmorphism effects
  - Smooth animations and transitions
  - Custom mood wheel with clip-path styling

### Design Features
- **Accessible Navigation** - Keyboard navigation support and focus management
- **Mobile-First Responsive Design** - Adaptive layouts for all screen sizes
- **Interactive Elements**:
  - Hover effects on cards and buttons
  - Smooth page transitions
  - Progressive disclosure of content
  - Visual feedback for user interactions

### Browser Compatibility
- Modern browsers (Chrome 90+, Firefox 88+, Safari 14+, Edge 90+)
- Progressive enhancement for older browsers
- No external dependencies or libraries required

## 🚀 Getting Started

### Prerequisites
- Any modern web browser
- No server setup required - runs as a static website

### Installation & Setup

1. **Download/Clone the Files**
   ```bash
   # If using Git
   git clone [repository-url]
   cd mindbridge
   
   # Or simply download the HTML file
   ```

2. **Open in Browser**
   ```bash
   # Simply open the HTML file in any web browser
   open mindbridge.html
   # or
   double-click the mindbridge.html file
   ```

3. **For Development/Hosting**
   ```bash
   # For local development server (optional)
   python -m http.server 8000
   # Then visit http://localhost:8000
   
   # Or use any static hosting service
   ```

## 📁 Project Structure

```
mindbridge/
├── mindbridge.html          # Main application file
├── README.md               # This file
├── assets/                 # (Optional) Additional assets
│   ├── images/
│   └── docs/
└── deployment/             # (Optional) Deployment configs
    ├── netlify.toml
    ├── vercel.json
    └── .htaccess
```

## 🎨 Customization

### Color Scheme
The platform uses a calming gradient-based color palette:
- **Primary**: `#667eea` to `#764ba2` (Purple-blue gradient)
- **Secondary**: Various mood-based colors for the mood wheel
- **Background**: Gradient overlays with glassmorphism effects

### Adding Content

**Educational Content**:
```javascript
// Modify content in the tab-content divs
<div id="newTopic" class="tab-content">
    <div class="section-card">
        <h3>Your New Topic</h3>
        <p>Educational content here...</p>
    </div>
</div>
```

**Writing Prompts**:
```javascript
// Add to the writingPrompts array
const writingPrompts = [
    "Your new prompt here",
    // ... existing prompts
];
```

**Mood Wheel Options**:
```javascript
// Add to moodData object
const moodData = {
    newMood: {
        title: "Feeling New Mood 🎭",
        message: "Description of this mood state",
        tip: "Helpful tip for this mood"
    }
};
```

## 🔒 Privacy & Security

### Data Handling
- **No Personal Data Storage**: All interactions are anonymous and local
- **No Cookies**: Platform doesn't use tracking cookies
- **Local Processing**: All quiz results and mood tracking happen in-browser
- **External Links**: Clearly marked when linking to external resources

### Crisis Safety
- Prominent crisis resource information on every relevant page
- Clear disclaimers about the platform's limitations
- Immediate access to emergency resources

## 📱 Mobile Optimization

### Responsive Features
- **Collapsible Navigation**: Mobile hamburger menu
- **Touch-Friendly**: Large touch targets for mobile users
- **Adaptive Layouts**: Single-column layouts on smaller screens
- **Optimized Mood Wheel**: Scaled appropriately for mobile screens
- **Form Optimization**: Responsive iframe containers for embedded forms

### Performance
- **Fast Loading**: Single-file architecture with embedded CSS/JS
- **Minimal Resources**: No external dependencies
- **Optimized Images**: Uses CSS and emoji for icons (no image files)

## 🧪 Testing

### Manual Testing Checklist
- [ ] All navigation links work correctly
- [ ] Responsive design works on mobile, tablet, and desktop
- [ ] Quiz functionality and result calculation
- [ ] Mood wheel interactions and feedback
- [ ] Writing prompt generation and selection
- [ ] External links open in new tabs
- [ ] Form embedding works properly
- [ ] Accessibility features (keyboard navigation, focus management)

### Browser Testing
Test across major browsers:
- Chrome/Chromium
- Firefox
- Safari
- Edge

## 🚀 Deployment

### Static Hosting Options

**Netlify**:
1. Drag and drop the HTML file to Netlify
2. Custom domain setup available
3. Automatic HTTPS

**Vercel**:
```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel

# Follow prompts for configuration
```

**GitHub Pages**:
1. Upload file to GitHub repository
2. Enable GitHub Pages in repository settings
3. Access via `username.github.io/repository-name`

**Other Options**:
- Firebase Hosting
- AWS S3 + CloudFront
- Traditional web hosting (upload via FTP)

## 🤝 Contributing

### How to Contribute
1. **Content Improvements**: Suggest new educational content or resources
2. **Accessibility**: Help improve accessibility features
3. **Translations**: Assist with multi-language support
4. **User Testing**: Provide feedback on user experience

### Content Guidelines
- **Culturally Sensitive**: All content should be reviewed for cultural sensitivity
- **Evidence-Based**: Educational content should be backed by research
- **Age-Appropriate**: Content suitable for high school students
- **Professional Review**: Mental health content should be reviewed by professionals

### Code Contributions
- Maintain single-file architecture for simplicity
- Follow existing code style and naming conventions
- Test across multiple browsers and devices
- Ensure accessibility compliance

## 📊 Analytics & Feedback

### Built-in Feedback
- Embedded Google Forms for user feedback
- Progress tracking (local storage simulation)
- Encouraging message system

### Potential Analytics
- Page view tracking (if needed)
- User journey analysis
- Resource link click tracking
- Form completion rates

## 🛡️ Content Disclaimers

**Important Notes**:
- Platform is for informational purposes only
- Not a substitute for professional mental health care
- Crisis resources prominently displayed
- Clear guidance on when to seek professional help

## 🔄 Future Enhancements

### Planned Features
- [ ] Multi-language support (starting with common Asian languages)
- [ ] Enhanced mood tracking with data visualization
- [ ] Resource finder by location
- [ ] Peer support chat integration
- [ ] Professional referral system
- [ ] Mobile app version

### Technical Improvements
- [ ] Progressive Web App (PWA) capabilities
- [ ] Offline functionality
- [ ] Enhanced accessibility features
- [ ] Performance optimizations
- [ ] SEO improvements

## 📞 Support & Resources

### For Users
- Crisis resources are available on every page
- External links to professional support
- Anonymous feedback system available

### For Developers
- Single HTML file makes debugging straightforward
- Browser developer tools for testing
- No complex build process required

## 📄 License

This project is designed for educational and public health purposes. Please ensure any adaptations maintain the focus on mental health support and cultural sensitivity.

## 🙏 Acknowledgments

- Mental health professionals who provided guidance on content
- Asian American student communities for feedback and testing
- Organizations providing culturally competent mental health resources
- Open source community for development inspiration

## 📈 Impact Goals

- Reduce stigma around mental health in Asian American communities
- Increase awareness of available resources
- Provide safe space for self-reflection and emotional processing
- Bridge cultural gaps in mental health understanding
- Encourage help-seeking behavior when appropriate

---

**Made with 💙 for the Asian American student community**

*Remember: Your mental health matters, and seeking help is a sign of strength, not weakness.*
