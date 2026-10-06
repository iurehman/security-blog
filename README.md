# Security Insights Blog

A professional cybersecurity blog built with clean Apple-inspired design principles, focused on defensive security analysis and CompTIA CEU farming.

## 🎯 Project Goals

- **CEU Strategy**: 18 articles targeting 60 CEU credits for CySA+ renewal
- **Professional Quality**: CompTIA audit-ready content
- **Anonymous Branding**: Minimal personal information, content-focused
- **Apple Aesthetics**: Clean, minimal design with excellent UX

## 🏛️ Brand Identity

- **Name**: Security Insights Blog
- **Focus**: Defensive cybersecurity analysis
- **Audience**: Security professionals, CompTIA auditors
- **Goal**: CEU credits through quality content

## 🚀 Quick Start

### Local Development

Start the local server:
```bash
python3 -m http.server 8001
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
├── README.md               # This documentation
├── articles/               # All HTML article files
│   ├── ai_siem_article.html
│   ├── threat_intelligence_article.html
│   ├── cloud_vulnerability_article.html
│   ├── incident_response_automation_article.html
│   └── detection_engineering_article.html
├── ceu-evidence/           # CEU documentation files for CompTIA
│   ├── ai-siem.txt
│   ├── threat-intelligence.txt
│   ├── cloud-vulnerability.txt
│   ├── incident-response.txt
│   └── detection-engineering.txt
└── linkedin-posts/         # LinkedIn promotion posts
    ├── ai-siem-linkedin.txt
    ├── threat-intelligence-linkedin.txt
    ├── cloud-vulnerability-linkedin.txt
    ├── incident-response-linkedin.txt
    └── detection-engineering-linkedin.txt
```

## 🎨 Design Principles

### Design Philosophy
- **Apple Simplicity**: Clean, minimal, no clutter
- **Professional**: Maintain credibility for CompTIA CEU audit
- **Human Touch**: Content should feel naturally written, not AI-generated
- **Anonymous**: Minimal personal branding, focus on content quality

### Design Standards
- **Typography**: Apple system fonts (`-apple-system`, SF Pro Display)
- **Colors**: Clean light/dark mode with Apple-inspired palette
- **Layout**: Hacker News-style list with visual icons
- **Mobile-First**: Responsive, touch-friendly
- **Performance**: Fast loading, minimal dependencies
- **Spacing Philosophy**: 
  - Tight, purposeful spacing - no excessive gaps
  - Visual breathing room without emptiness
  - Consistent rhythm throughout articles
  - Easy on the eyes, clean to read

### Content Philosophy
- **Human Voice**: Natural, professional tone (not AI-generated feel)
- **Concise**: Less text, more impact
- **Technical Authority**: Maintain cybersecurity credibility
- **Professional**: CompTIA audit-ready quality

## 📝 Content Guidelines

### Content Requirements
- **18 Articles Target**: For 60 CEU farming strategy
- **Security Focus**: SIEM, Threat Intelligence, Vulnerability Management, Incident Response
- **Word Count**: 600-800 words per article (CEU requirements)
- **Professional Quality**: CompTIA audit-ready content

### CompTIA CEU Requirements (IMPORTANT)

Based on official CompTIA CEU submission guidelines:

- **Minimum Word Count**: 500+ words per blog post to earn 1 CEU
- **Maximum CEUs**: 1 CEU per blog post (regardless of length)
- **Timing**: Articles must be written and published during your three-year renewal cycle
- **Relevance**: At least 50% of content must relate to one or more exam objectives for the certification you're renewing
- **Documentation Required**:
  1. URL or copy of the published work with your name and date published
  2. Description of the content covered
- **Activity Type**: "Published a Blog (500+ words) for CySA+ CEUs"
- **Certification**: CompTIA CySA+ ce

**Important Notes:**
- Each article with 500+ words earns exactly 1 CEU
- Our target of 600-800 words ensures we exceed the minimum requirement
- Documentation files (like incident-response.txt) must be maintained for audit purposes
- The CEU Assessment tool will guide you through requirements step-by-step

### Article Requirements
- **Headlines**: Clear, specific, professional
- **Excerpts**: One concise sentence maximum
- **Tags**: Relevant security keywords only
- **Metadata**: Word count, domain, publish date
- **Structure**: Clear headlines, concise paragraphs, practical insights

### Article Template Structure

Each article should follow this consistent structure:

1. **Header Section**:
   - Domain tag (e.g., "Threat Intelligence")
   - Author attribution: "By Intikhab Rehman"
   - Word count (e.g., "678 words")
   - Read time (e.g., "3-4 min read")
   - Publish date (e.g., "July 16, 2025")

2. **Title & Subtitle**:
   - Clear, specific professional title
   - One-line subtitle explaining the article's value

3. **Content Description Box** (CRITICAL - Must match template exactly):
   - **Gray background box** placed immediately after header/subtitle
   - **NOT a regular H2 section** - uses specific inline styling
   - Uses H3 heading "Content Description" inside the box
   - 2-3 paragraphs describing the article within the box
   - Mention CEU objectives if applicable
   - Professional summary of key takeaways
   - **Exact styling**: Gray background (bg-secondary), 24px padding, 12px border-radius

4. **Main Content**:
   - Start with introduction paragraph after Content Description box
   - Use H2 headers for major sections
   - Include "Key Insight" callout boxes for important points
   - End with forward-looking conclusion

5. **Visual Consistency & Spacing** (CRITICAL for Apple aesthetic):
   - **NO EXCESSIVE WHITE SPACE** - Tight, purposeful spacing only
   - Header padding: 32px top, 24px bottom maximum
   - Content Description box: 16px margin-bottom (not 32px)
   - H2 headings: 20px top margin, 12px bottom
   - Paragraphs: 16px margin-bottom (not 24px)
   - Article content: 32px margin-bottom (not 64px)
   - **Goal**: Clean, readable, no empty gaps
   - **Test**: Screenshot should show content filling screen nicely
   - Follow exact spacing from template articles

### Writing Style
- **Professional Blogger Tone**: Authoritative yet accessible
- **Concise**: Less text, more impact
- **Human Voice**: Natural flow, avoid robotic AI patterns
- **Technical Accuracy**: Maintain cybersecurity expertise credibility
- **Practical Focus**: Real-world focused content

### LinkedIn Post Template (For article promotion)
```
Just published: [Article Title]
📖 [blog-link]

[One compelling sentence about the problem/challenge]

This article covers:
• [Key point 1]
• [Key point 2] 
• [Key point 3]
• [Key point 4]

#CloudSecurity #VulnerabilityManagement #DevSecOps #Cybersecurity #InfoSec
```

**Format Requirements:**
- Keep it short and scannable
- Start with "Just published:" for consistency
- Use book emoji 📖 before link
- One problem statement sentence
- Exactly 4 bullet points with key insights
- End with relevant hashtags (5 max)

### Article Documentation Template (For CySA+ CEU records)

Save each article as: `[article-name-2-words].txt`

```
Blog Post Documentation for CySA+ CEU Submission

URL: [full-article-url]

Article Details:
- Title: [Full Article Title]
- Author: Intikhab Rehman
- Publication Date: [ACTUAL publish date - must match when article was published]
- Word Count: [XXX]+ words

Content Description:
[2-3 sentences describing article content, methodologies covered, and key takeaways]

CySA+ Exam Objectives Covered:
- [Objective 1.X] [Description - use CS0-004 wording from the tracking section above]
- [Objective 2.X] [Description]
- [Objective 3.X] [Description]
- [Continue as needed...]

Relevance to CySA+: 
[Percentage and brief explanation of how content relates to exam objectives]
```

**Documentation Requirements:**
- Create .txt file for each published article
- Use 2-word filename (e.g., "threat-intelligence.txt", "cloud-vulnerability.txt")
- Include all CySA+ exam objectives covered
- Maintain records for CEU audit purposes

## 🗂️ CySA+ Objectives & CEU Tracking

**Update this section every time an article is published, and review it fully every 2 years (see checklist below).**

### Exam Version Tracking

| Version | Status | Key Dates | Objectives Source |
|---------|--------|-----------|-------------------|
| CS0-003 (V3) | Retiring | Retires Dec 22, 2026 | CompTIA CS0-003 objectives |
| CS0-004 (V4) | Current | Launched June 23, 2026 | CompTIA CySA+ CS0-004 V4 Exam Objectives, Document Version 2.0 |

*Version dates were supplied by the blog owner; objectives wording was verified against the official CS0-004 objectives PDF (Oct 5, 2026).*

### CS0-004 Domains

| Domain | Weight |
|--------|--------|
| 1.0 Security Operations | 34% |
| 2.0 Vulnerability Management | 26% |
| 3.0 Incident Response and Management | 24% |
| 4.0 Reporting and Communication | 16% |

### CS0-004 Objective Numbers (use these in evidence files)

- **1.1** Explain concepts related to system and network architecture in security
- **1.2** Given a scenario, analyze indicators of potential malicious activity
- **1.3** Given a scenario, use tools to determine malicious activity
- **1.4** Explain threat intelligence and threat-hunting concepts
- **1.5** Explain the importance of efficiency and process improvement in security operations
- **1.6** Summarize concepts related to the use of AI in security operations *(new in CS0-004)*
- **2.1** Given a scenario, implement the appropriate vulnerability scanning method
- **2.2** Given a scenario, analyze output from vulnerability assessment tools
- **2.3** Given a scenario, analyze data to prioritize and mitigate vulnerabilities
- **2.4** Explain concepts related to control types, risks, and vulnerability management
- **3.1** Summarize concepts related to attack methodology frameworks
- **3.2** Summarize the incident response process
- **3.3** Given a scenario, implement incident response techniques
- **4.1** Explain the importance of vulnerability management reporting and communication
- **4.2** Explain the importance of security operations and incident response reporting and communication

> Objective **1.1-1.5 numbering overlaps with CS0-003 but wording differs** (e.g., CS0-003 1.4 was threat intel vs. hunting, 3.x covered different IR topics). Always cite the exam version in the evidence file.

### Article Tracker

| # | Article | Published | Words | Exam Version Cited | Objectives Covered | Evidence File |
|---|---------|-----------|-------|--------------------|--------------------|---------------|
| 1 | AI-Enhanced SIEM: Modern Threat Detection | Jul 14, 2025 | 742 | Older numbering (pre-CS0-004) | See file | `ceu-evidence/ai-siem.txt` |
| 2 | Threat Intelligence: From Collection to Action | Jul 16, 2025 | 678 | Older numbering (pre-CS0-004) | See file | `ceu-evidence/threat-intelligence.txt` |
| 3 | Cloud Vulnerability Assessment Strategies | Jul 20, 2025 | 615 | Older numbering (pre-CS0-004) | See file | `ceu-evidence/cloud-vulnerability.txt` |
| 4 | Incident Response Automation Frameworks | Jul 25, 2025 | 724 | Older numbering (pre-CS0-004) | See file | `ceu-evidence/incident-response.txt` |
| 5 | Detection Engineering with MITRE ATT&CK | Oct 5, 2026 | 635 | CS0-004 | 1.2, 1.3, 1.4, 1.5, 1.6, 3.1 | `ceu-evidence/detection-engineering.txt` |

**CEU progress:** 5 articles published = 5 CEUs (1 CEU per 500+ word article). Target: 60 CEUs.
**Renewal cycle start / end dates:** _fill in from your CompTIA certification record_ (articles must be published inside the cycle).

### Every-2-Years Maintenance Checklist

Next review due: **October 2028** (then every 2 years).

- [ ] Check CompTIA's CySA+ page for a new exam version and its objectives PDF
- [ ] Update the version table, domain weights, and objective list above
- [ ] Confirm CompTIA's CEU rules still match (500+ words, 1 CEU per blog, 50% relevance)
- [ ] Review older evidence files; note which exam version each one cites
- [ ] Verify article URLs still load on the live site
- [ ] Confirm articles still fall within the current renewal cycle
- [ ] Update CEU progress count and the Article Tracker

## 📋 Article Publishing Workflow

**Complete 3-step process for each new article:**

### Step 1: Write & Publish Article
1. **Create article HTML file** in `articles/` folder
   - Follow the exact template structure from existing articles
   - Ensure 600-800 words (minimum 500 for CEU credit)
   - Include all required sections (Content Description box, tags, etc.)
   - Name file: `topic_name_article.html`

2. **Update index.html**
   - Add new article entry with proper metadata
   - Include: icon emoji, domain tag, word count, title, excerpt, tags
   - Ensure link points to `articles/[filename].html`

### Step 2: Create CEU Documentation
1. **Create CEU evidence file** in `ceu-evidence/` folder
   - Use Article Documentation Template (see below)
   - Name file: `[two-word-topic].txt` (e.g., "incident-response.txt")
   - Include all CySA+ objectives covered
   - Calculate relevance percentage

### Step 3: Create LinkedIn Promotion
1. **Create LinkedIn post** in `linkedin-posts/` folder
   - Use LinkedIn Post Template (see below)
   - Name file: `[topic]-linkedin.txt`
   - Follow exact format with 4 bullet points
   - Include relevant hashtags

### Folder Organization
```
articles/          → HTML article files
ceu-evidence/      → CompTIA CEU documentation
linkedin-posts/    → Social media promotion posts
```

**File Naming Conventions:**
- Articles: `topic_name_article.html`
- CEU docs: `topic-name.txt` (2 words with hyphen)
- LinkedIn: `topic-name-linkedin.txt`

**This 3-step workflow ensures:**
- ✅ Consistent article quality and structure
- ✅ Complete CEU documentation for CompTIA audit
- ✅ Professional social media promotion
- ✅ Organized file management

### Quick Checklist for New Articles
- [ ] Article HTML created in `articles/` folder
- [ ] Article has 600-800 words
- [ ] Content Description box included
- [ ] All required metadata present
- [ ] index.html updated with new entry
- [ ] CEU documentation created in `ceu-evidence/`
- [ ] LinkedIn post created in `linkedin-posts/`
- [ ] All files follow naming conventions
- [ ] Git commit and push completed

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
- ✅ **Threat Intelligence: From Collection to Action** (678 words) - Threat Intelligence focus
- ✅ **Cloud Vulnerability Assessment Strategies** (615 words) - Vulnerability Management focus
- ✅ **Incident Response Automation Frameworks** (724 words) - Incident Response focus
- ✅ **Detection Engineering with MITRE ATT&CK** (635 words) - Security Operations focus (CS0-004)

### Planned Articles (13 remaining)
- Zero Trust Architecture Implementation (~650 words)
- [11 more articles planned across 5 security domains]

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