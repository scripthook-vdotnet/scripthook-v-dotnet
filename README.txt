================================================================================
  SCRIPT HOOK V .NET - WEBSITE DOCUMENTATION
  Professional Multi-Page Website Template
================================================================================

CONTENTS:
  1. Overview
  2. File Structure
  3. How to Run Locally
  4. Customization Guide
  5. Replacing Links
  6. Color Customization
  7. Content Modification
  8. SEO & Keywords
  9. Deployment
  10. Support & Credits

================================================================================
1. OVERVIEW
================================================================================

This is a professional, modern, responsive multi-page website built with pure
HTML, CSS, and JavaScript. The website includes:

- Home Page (index.html) - Hero section, features, content with keyword integration
- About Page (about.html) - Mission, vision, values, and company information
- Contact Page (contact.html) - Google Form integration with styled button
- Download Page (download.html) - Prominent download button with installation guide
- Responsive Navigation - Works seamlessly on mobile, tablet, and desktop
- Modern Design - Clean, professional styling with smooth animations

================================================================================
2. FILE STRUCTURE
================================================================================

scripthookvdotnet.info3/
│
├── index.html          - Home page with hero section and features
├── about.html          - About page with mission and vision
├── contact.html        - Contact page with Google Form button
├── download.html       - Download page with installation guide
├── style.css           - All styling and responsive design
├── script.js           - JavaScript for interactivity and animations
└── README.txt          - This documentation file

================================================================================
3. HOW TO RUN LOCALLY
================================================================================

OPTION 1: Simple File Opening
------------------------------
1. Navigate to the folder containing the website files
2. Double-click "index.html" to open it in your default browser
3. Use the navigation menu to browse between pages

OPTION 2: Local Web Server (Recommended)
-----------------------------------------
For better performance and testing:

Using Python (if installed):
  1. Open terminal/command prompt in the website folder
  2. Run: python -m http.server 8000
  3. Open browser and go to: http://localhost:8000

Using Node.js (if installed):
  1. Install http-server: npm install -g http-server
  2. Run: http-server
  3. Open browser and go to: http://localhost:8080

Using VS Code:
  1. Install "Live Server" extension
  2. Right-click index.html
  3. Select "Open with Live Server"

================================================================================
4. CUSTOMIZATION GUIDE
================================================================================

This website is designed to be easily customizable. Below are the main areas
you can modify to make it your own.

================================================================================
5. REPLACING LINKS
================================================================================

GOOGLE FORM LINK:
-----------------
Location: contact.html (Line ~47)
Current: https://docs.google.com/forms/d/e/1FAIpQLSd4EKhtkytt-26izhOtx03F5GQ9bAs6iZHxvPK0wUkMTPSjIg/viewform?usp=header

To replace:
1. Open contact.html in a text editor
2. Find the line: <a href="https://docs.google.com/forms/..."
3. Replace the URL with your Google Form URL
4. Save the file

DOWNLOAD LINK:
--------------
Location: download.html (Line ~68)
Current: https://scripthookvdotnet.info/download/

To replace:
1. Open download.html in a text editor
2. Find: <a href="https://scripthookvdotnet.info/download/"
3. Replace with your download URL
4. Save the file

Also appears in:
- index.html (Hero section and CTA)
- Navigation bar on all pages

GITHUB LINK:
------------
Location: All pages (navigation bar)
Current: https://github.com/scripthook-vdotnet

To replace:
1. Open each HTML file (index.html, about.html, contact.html, download.html)
2. Find: https://github.com/scripthook-vdotnet
3. Replace with your GitHub repository URL
4. Save all files

OFFICIAL SITE LINK:
-------------------
Location: Multiple locations
Current: https://scripthookvdotnet.info/

To replace:
1. Search for "scripthookvdotnet.info" in all HTML files
2. Replace with your official website URL
3. Save all files

TIP: Use Find & Replace (Ctrl+H) in your text editor to replace all instances
at once!

================================================================================
6. COLOR CUSTOMIZATION
================================================================================

All colors are defined in style.css using CSS variables for easy modification.

Location: style.css (Lines 6-14)

Current Color Palette:
----------------------
--primary-color: #BBFE6C      (Bright lime green)
--secondary-color: #FFFFFF    (White)
--dark-color: #1E1E1E        (Almost black)
--text-color: #1E1E1E        (Text color)
--light-bg: #F8F9FA          (Light background)
--accent-hover: #A8E85B      (Hover state green)

To Change Colors:
-----------------
1. Open style.css in a text editor
2. Navigate to the ":root" section at the top
3. Modify the hex color values
4. Save the file

Example:
Change primary color to blue:
--primary-color: #4A90E2;     (Replace #BBFE6C with #4A90E2)

Color Recommendations:
----------------------
- Keep good contrast between text and background
- Use a color picker tool to find harmonious colors
- Test on both light and dark backgrounds
- Check mobile responsiveness after color changes

Recommended Color Combinations:
1. Professional Blue: #2E5BFF, #FFFFFF, #0A0F2C
2. Modern Purple: #8B5CF6, #FFFFFF, #1F1F1F
3. Tech Orange: #FF6B35, #FFFFFF, #1A1A2E
4. Clean Cyan: #06D6A0, #FFFFFF, #1B1B1E

================================================================================
7. CONTENT MODIFICATION
================================================================================

SITE NAME/BRANDING:
-------------------
Location: All HTML files (logo and footer)
Current: "ScriptHook V .NET"

To change:
1. Find: <a href="index.html" class="logo">ScriptHook V .NET</a>
2. Replace "ScriptHook V .NET" with your brand name
3. Update footer text in all files

PAGE TITLES:
------------
Location: <title> tag in each HTML file
Format: <title>Page Name - Site Name</title>

To change:
1. Find the <title> tag in the <head> section
2. Replace with your desired title
3. Keep titles under 60 characters for SEO

META DESCRIPTIONS:
------------------
Location: <meta name="description"> in each HTML file

To change:
1. Find: <meta name="description" content="...">
2. Replace content with your page description
3. Keep descriptions between 150-160 characters

HERO SECTION (Home Page):
-------------------------
Location: index.html (Lines ~35-48)

Modify:
- Main heading: <h1 class="hero-title">
- Subtitle: <p class="hero-subtitle">
- Button text and links in hero-buttons div

FEATURES SECTION:
-----------------
Location: index.html (Lines ~52-71)

Each feature card has:
- Icon (emoji or can be replaced with images)
- Heading (<h3>)
- Description (<p>)

To add/remove features:
1. Copy entire <div class="feature-card">...</div>
2. Paste and modify content
3. Save file

ABOUT PAGE CONTENT:
-------------------
Location: about.html

Sections to modify:
- Our Story (Lines ~35-41)
- Our Mission (Lines ~43-49)
- Our Vision (Lines ~51-57)
- Core Values (Lines ~59-79)

CONTACT PAGE:
-------------
Location: contact.html

Modify:
- Heading and intro text (Lines ~35-39)
- Button text (Line ~47)
- Info cards content (Lines ~56-82)

DOWNLOAD PAGE:
--------------
Location: download.html

Modify:
- System requirements (Lines ~51-58)
- Installation steps (Lines ~62-85)
- Features list (Lines ~89-111)

================================================================================
8. SEO & KEYWORDS
================================================================================

KEYWORD INTEGRATION:
--------------------
Current Focus Keyword: "script hook v dotnet"

Location: index.html (Line ~72)
The keyword is naturally integrated with a link to the official site.

To modify keywords:
1. Identify your target keywords
2. Integrate naturally into content paragraphs
3. Link keywords to relevant URLs
4. Avoid over-optimization (use keywords naturally)

Best Practices:
- Use keywords in headings (H1, H2, H3)
- Include in page titles and meta descriptions
- Use variations and related terms
- Focus on readability, not keyword density

================================================================================
9. DEPLOYMENT
================================================================================

OPTION 1: GitHub Pages
-----------------------
1. Create a GitHub repository
2. Upload all website files
3. Go to Settings > Pages
4. Select main branch as source
5. Your site will be live at: username.github.io/repo-name

OPTION 2: Netlify
-----------------
1. Go to netlify.com
2. Drag and drop your website folder
3. Site goes live instantly
4. Free custom domain support

OPTION 3: Traditional Web Hosting
----------------------------------
1. Purchase hosting (Hostinger, Bluehost, etc.)
2. Use FTP/File Manager to upload files
3. Upload to public_html or www folder
4. Configure domain if needed

OPTION 4: Vercel
----------------
1. Go to vercel.com
2. Import your project
3. Deploy with one click
4. Free hosting with custom domains

================================================================================
10. SUPPORT & CREDITS
================================================================================

BROWSER COMPATIBILITY:
----------------------
✓ Chrome (latest)
✓ Firefox (latest)
✓ Safari (latest)
✓ Edge (latest)
✓ Opera (latest)
✓ Mobile browsers (iOS Safari, Chrome Mobile)

RESPONSIVE BREAKPOINTS:
-----------------------
- Desktop: 1200px+
- Tablet: 768px - 1199px
- Mobile: 320px - 767px

FEATURES INCLUDED:
------------------
✓ Fully responsive design
✓ Mobile-friendly navigation
✓ Smooth scroll animations
✓ Hover effects and transitions
✓ SEO-optimized structure
✓ Fast loading times
✓ Cross-browser compatible
✓ Accessibility-friendly
✓ Clean, semantic HTML5

CUSTOMIZATION TIPS:
-------------------
1. Always backup files before making changes
2. Test changes on multiple devices
3. Use browser developer tools (F12) for debugging
4. Validate HTML: validator.w3.org
5. Check mobile responsiveness: responsivedesignchecker.com
6. Test loading speed: pagespeed.web.dev

TROUBLESHOOTING:
----------------
Issue: Navigation menu not working on mobile
Fix: Check that script.js is properly linked in all HTML files

Issue: Styles not loading
Fix: Verify style.css path is correct (should be in same folder)

Issue: Links not working
Fix: Check that all href attributes have correct URLs

Issue: Images not showing (if you add any)
Fix: Use relative paths and ensure files are in correct folder

NEED HELP?
----------
- Check browser console for errors (F12)
- Validate HTML at validator.w3.org
- Test CSS at jigsaw.w3.org/css-validator
- Use browser developer tools for debugging

CREDITS & LICENSE:
------------------
Design & Development: Created for Script Hook V .NET Community
Built with: HTML5, CSS3, JavaScript (Vanilla)
No frameworks required - Pure, clean code
License: Feel free to modify and customize for your needs

ENJOY YOUR NEW WEBSITE!
================================================================================

For questions or support, use the contact form on your website.
Thank you for using this template!

================================================================================
END OF DOCUMENTATION
================================================================================
