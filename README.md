# Security Insights Blog

A professional cybersecurity blog built with clean Apple-inspired design principles, focused on defensive security analysis and CompTIA CEU farming.

## 🎯 Project Goals

- **CEU Strategy**: 18 articles targeting 60 CEU credits for CySA+ renewal
- **Professional Quality**: CompTIA audit-ready content
- **Anonymous Branding**: Minimal personal information, content-focused
- **Apple Aesthetics**: Clean, minimal design with excellent UX

## 🚀 Quick Start

### Local Development

Start the local server:
```bash
python3 -m http.server 8000
```

Open in browser:
```
http://localhost:8000
```

Stop the server:
```bash
pkill -f "python3 -m http.server"
```

### Alternative Server Options

**Using Node.js:**
```bash
npx serve .
```

**Using PHP:**
```bash
php -S localhost:8000
```

## 📁 Project Structure

```
security-blog/
├── index.html              # Homepage with article listings
├── ai_siem_article.html     # First published article (742 words)
├── CLAUDE.md               # Design & writing guidelines
├── README.md               # This documentation
└── .git/                   # Git repository
```

## 🎨 Design Principles

### Apple-Inspired Design
- **Typography**: Apple system fonts (`-apple-system`, SF Pro Display)
- **Colors**: Clean light/dark mode with Apple's color palette
- **Layout**: Minimal, spacious, content-focused
- **Interactions**: Smooth transitions, subtle hover effects

### Content Philosophy
- **Human Voice**: Natural, professional tone (not AI-generated feel)
- **Concise**: Less text, more impact
- **Technical Authority**: Maintain cybersecurity credibility
- **Professional**: CompTIA audit-ready quality

## 📝 Content Guidelines

### Article Requirements
- **Word Count**: 600-800 words (CEU requirement)
- **Focus Areas**: SIEM, Threat Intelligence, Vulnerability Management, Incident Response
- **Structure**: Clear headlines, concise paragraphs, practical insights
- **Meta**: Domain tags, word counts, reading time

### Writing Style
- Professional blogger tone
- Authoritative yet accessible
- Practical, real-world focused
- Human touch (avoid robotic AI patterns)

## 🌐 Deployment

### Live Site
- **URL**: https://security-blog-wheat.vercel.app
- **Platform**: Vercel (auto-deploys from GitHub)
- **Domain**: Custom domain available via Vercel settings

### Git Workflow
```bash
# Check status
git status

# Stage changes
git add .

# Commit with message
git commit -m "Your commit message"

# Push to deploy
git push origin master
```

## 🛠️ Development Workflow

1. **Local Testing**: Use `python3 -m http.server 8000` for live preview
2. **Make Changes**: Edit HTML/CSS directly in files
3. **Test**: Verify changes in browser (both light/dark modes)
4. **Commit**: Git add, commit, and push
5. **Deploy**: Vercel auto-deploys within 2-3 minutes

## 📊 Current Status

### Published Content
- ✅ **AI-Enhanced SIEM** (742 words) - Security Operations focus

### Planned Articles (17 remaining)
- Threat Intelligence: From Collection to Action (~650 words)
- Cloud Vulnerability Assessment Strategies (~600 words)
- [15 more articles planned across 5 security domains]

## 🎯 SEO & Performance

### Optimization Features
- Semantic HTML structure
- Proper meta descriptions
- Mobile-first responsive design
- Fast loading (minimal dependencies)
- Apple-quality typography rendering

### Accessibility
- Proper heading hierarchy
- Color contrast compliance
- Keyboard navigation support
- Screen reader friendly

## 🔧 Technical Details

### Browser Support
- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers (iOS Safari, Android Chrome)
- Dark mode support across all platforms

### Performance
- Pure HTML/CSS/JS (no frameworks)
- Optimized for fast loading
- Responsive images (when added)
- Minimal HTTP requests

## 📋 Maintenance

### Regular Tasks
- Content updates (new articles)
- SEO optimization
- Performance monitoring
- Responsive design testing

### Content Calendar
- Target: 1 article per week
- Focus: Rotate between security domains
- Quality: 600-800 words, professional analysis

## 📞 Support

### Issues & Questions
- Check `CLAUDE.md` for design guidelines
- Reference this README for development setup
- Test locally before pushing changes

### Best Practices
- Always test both light and dark modes
- Verify mobile responsiveness
- Maintain professional tone and quality
- Keep personal branding minimal

---

**Built with care for cybersecurity professionals seeking quality content and CEU credits.**