================================================================================
                   ATMOSPHERE SWITCH WEBSITE - README
================================================================================

🎉 WELCOME TO YOUR PROFESSIONAL NINTENDO SWITCH MODDING WEBSITE!

This is a modern, responsive, multi-page website built with HTML, CSS, and 
JavaScript. The design is inspired by professional modding communities with 
clean aesthetics and smooth user experience.

================================================================================
📁 FILE STRUCTURE
================================================================================

atmosphereswitch2/
│
├── index.html          - Home page with hero section and focus keywords
├── about.html          - About page with mission and vision
├── contact.html        - Contact page with Google Form integration
├── download.html       - Download page with prominent download button
├── style.css           - All styling and responsive design
├── script.js           - Interactivity and animations
└── README.txt          - This file (setup instructions)

================================================================================
🚀 HOW TO RUN THE WEBSITE LOCALLY
================================================================================

METHOD 1: Simple Double-Click
-------------------------------
1. Open your file explorer
2. Navigate to the atmosphereswitch2 folder
3. Double-click on "index.html"
4. The website will open in your default web browser

METHOD 2: Using Live Server (Recommended for Development)
----------------------------------------------------------
If you use Visual Studio Code:
1. Install the "Live Server" extension
2. Right-click on index.html
3. Select "Open with Live Server"
4. The website will open at http://localhost:5500

METHOD 3: Using Python HTTP Server
-----------------------------------
1. Open terminal/command prompt in the project folder
2. Run: python -m http.server 8000
3. Open browser and go to: http://localhost:8000

METHOD 4: Using Node.js HTTP Server
------------------------------------
1. Install http-server globally: npm install -g http-server
2. Navigate to project folder in terminal
3. Run: http-server
4. Open the URL shown in terminal

================================================================================
🔧 CUSTOMIZATION GUIDE
================================================================================

1. CHANGING COLORS
------------------
Open style.css and edit the CSS variables at the top:

:root {
    --primary-color: #5982D6;      /* Main brand color (blue) */
    --secondary-color: #FAFAFA;    /* Light background color */
    --accent-color: #7534F7;       /* Accent/highlight color (purple) */
    --white-color: #FFFFFF;        /* White for text and backgrounds */
}

You can replace these hex codes with any colors you prefer.

2. REPLACING LINKS
------------------

Google Form Link (Contact Page):
- Open contact.html
- Find: https://docs.google.com/forms/d/e/1FAIpQLScQfW5_cmuD6E85Dh0GEeyvJUUYjRMA-_inEbviXO1_xx_-BA/viewform?usp=header
- Replace with your own Google Form link

GitHub Repository Link:
- Find in all HTML files: https://github.com/atmospher-switch/AtmoSphere-Switch
- Replace with your own GitHub repository URL

Download Link (Download Page):
- Open download.html
- Find: https://atmosphereswitch.com/download/
- Replace with your actual download page URL

Official Website Link:
- Find in all HTML files: https://atmosphereswitch.com/
- Replace with your actual website URL

3. CHANGING TEXT CONTENT
-------------------------

Site Name/Branding:
- Search for "AtmoSphere Switch" in all HTML files
- Replace with your preferred site name

Hero Section (Home Page):
- Open index.html
- Edit the text inside the <h1 class="hero-title"> section
- Modify the <p class="hero-description"> content

Page Titles:
- Edit <title> tags in each HTML file's <head> section

Footer Copyright:
- Find "© 2024 AtmoSphere Switch" in all HTML files
- Update year and name as needed

Footer Credit:
- Find "Designed & Developed with ❤️ by AtmoSphere Team"
- Replace with your name or team name

4. CHANGING FOCUS KEYWORDS AND LINKS
-------------------------------------

Current keywords on index.html:
- "switch atmosphere" → links to: https://atmosphereswitch.com/
- "how to mod switch oled" → links to: https://atmosphereswitch.com/hack-your-nintendo-switch-oled/
- "update atmosphere switch" → links to: https://atmosphereswitch.com/how-to-update-switch-atmosphere-firmware/

To update:
1. Open index.html
2. Search for <a href="..." class="inline-link">keyword</a>
3. Replace the href URL and keyword text
4. Keep the class="inline-link" for proper styling

5. ADDING NEW PAGES
-------------------

To add a new page:
1. Duplicate any existing HTML file (e.g., about.html)
2. Rename it (e.g., tutorials.html)
3. Update the page content
4. Add a link in the navigation menu of all pages:
   
   <li><a href="tutorials.html" class="nav-link">Tutorials</a></li>

5. Add the new page link to the footer of all pages

6. CHANGING FONTS
-----------------

Current fonts: Inter and Poppins (loaded from Google Fonts)

To change fonts:
1. Visit https://fonts.google.com/
2. Select your preferred fonts
3. Replace the font link in the <head> of all HTML files
4. Update font-family in style.css:
   - body { font-family: 'YourFont', sans-serif; }
   - .logo, h1, h2, h3 { font-family: 'YourHeadingFont', sans-serif; }

7. ADDING IMAGES/LOGOS
----------------------

To add a real logo:
1. Save your logo as "logo.png" in the project folder
2. In all HTML files, find: <span class="logo-icon">⚡</span>
3. Replace with: <img src="logo.png" alt="Logo" style="width: 32px;">

To add hero images:
1. Replace the SVG placeholder in index.html with:
   <img src="your-image.jpg" alt="Description">

8. MODIFYING ANIMATIONS
-----------------------

All animations are in style.css under the "ANIMATIONS" section.

To disable animations:
- Comment out or remove @keyframes rules
- Remove animation properties from elements

To adjust animation speed:
- Change duration values (e.g., "1s" to "0.5s" for faster)

9. RESPONSIVE BREAKPOINTS
--------------------------

Current breakpoints in style.css:
- @media (max-width: 968px) - Tablets
- @media (max-width: 640px) - Mobile phones

To adjust:
1. Find the @media rules in style.css
2. Change the pixel values to your preference
3. Adjust styles inside those rules

================================================================================
🌐 DEPLOYING YOUR WEBSITE
================================================================================

OPTION 1: GitHub Pages (Free)
------------------------------
1. Create a GitHub account
2. Create a new repository
3. Upload all files to the repository
4. Go to Settings > Pages
5. Select branch: main, folder: / (root)
6. Click Save - your site will be live!

OPTION 2: Netlify (Free)
-------------------------
1. Create a Netlify account
2. Drag and drop your project folder to Netlify
3. Your site is instantly deployed!

OPTION 3: Vercel (Free)
------------------------
1. Create a Vercel account
2. Import your project
3. Deploy with one click

OPTION 4: Traditional Web Hosting
----------------------------------
1. Use any hosting provider (Hostinger, Bluehost, etc.)
2. Upload files via FTP or cPanel File Manager
3. Your site will be live on your domain

================================================================================
📱 TESTING YOUR WEBSITE
================================================================================

Desktop Testing:
- Test in Chrome, Firefox, Safari, and Edge
- Check at different screen sizes using browser dev tools (F12)

Mobile Testing:
- Test on actual mobile devices
- Use Chrome DevTools mobile emulator
- Check both portrait and landscape orientations

Accessibility Testing:
- Ensure keyboard navigation works
- Check color contrast
- Test with screen readers

Performance Testing:
- Use Google PageSpeed Insights
- Check loading times
- Optimize images if needed

================================================================================
🔍 SEO OPTIMIZATION
================================================================================

Each page includes:
✅ Meta descriptions
✅ Semantic HTML (header, section, footer)
✅ Proper heading hierarchy (h1, h2, h3)
✅ Alt text ready for images
✅ Internal linking structure
✅ Focus keywords naturally placed

To improve SEO further:
1. Add a sitemap.xml file
2. Add a robots.txt file
3. Optimize images (compress, add alt text)
4. Add Open Graph meta tags for social sharing
5. Submit to Google Search Console

================================================================================
🐛 TROUBLESHOOTING
================================================================================

Problem: Navigation menu doesn't work on mobile
Solution: Make sure script.js is properly linked in all HTML files

Problem: Styles not loading
Solution: Check that style.css is in the same folder as HTML files

Problem: Animations not smooth
Solution: Try testing in a different browser or clear cache

Problem: Links not working
Solution: Ensure all href attributes have correct URLs

Problem: Google Form button not working
Solution: Verify the Google Form link is correct and publicly accessible

================================================================================
📞 SUPPORT & UPDATES
================================================================================

This website is built with:
- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript (no dependencies)
- Google Fonts (Inter and Poppins)

Browser Support:
✅ Chrome (latest)
✅ Firefox (latest)
✅ Safari (latest)
✅ Edge (latest)
✅ Mobile browsers (iOS Safari, Chrome Mobile)

================================================================================
✨ FEATURES INCLUDED
================================================================================

✅ Fully responsive design (mobile, tablet, desktop)
✅ Modern color scheme with gradient effects
✅ Smooth animations and transitions
✅ Mobile-friendly navigation menu
✅ SEO-optimized structure
✅ Fast loading times
✅ Cross-browser compatible
✅ Accessibility features
✅ Professional typography
✅ Interactive button effects
✅ Scroll animations
✅ Hover effects throughout
✅ Clean, maintainable code

================================================================================
📝 NOTES
================================================================================

- All external links open in new tabs (target="_blank")
- Keywords are naturally integrated into content
- No external dependencies (except Google Fonts)
- Clean, commented code for easy customization
- Mobile-first responsive design approach
- Professional color palette pre-configured
- Smooth scrolling enabled for anchor links

================================================================================
🎨 DESIGN CREDITS
================================================================================

Inspired by: https://atmosphereswitch.com/
Designed & Developed by: AtmoSphere Team
Color Palette: #5982D6, #FAFAFA, #7534F7, #FFFFFF
Fonts: Inter (body), Poppins (headings)

================================================================================
📄 LICENSE
================================================================================

This website template is provided as-is. You are free to use, modify, and
distribute it for personal or commercial projects. Attribution is appreciated
but not required.

================================================================================

🚀 ENJOY YOUR NEW WEBSITE!

For questions or support, visit the contact page or check the official
website at https://atmosphereswitch.com/

================================================================================
