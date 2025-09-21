Javad Beig - Mechanical Engineering Portfolio
https://javad-beig.github.io/assets/og-image.jpg

A professional portfolio website showcasing Javad Beig's mechanical engineering projects, skills, education, and professional experience.

🌐 Live Demo
View Portfolio

📋 About
This portfolio website represents Javad Beig, a Mechanical Engineering undergraduate specializing in CAD, FEA, thermodynamics, and sustainable design. The site showcases his educational background, technical skills, project portfolio, and professional certifications.

✨ Features

Responsive Design: Optimized for all devices (desktop, tablet, mobile)
Modern UI/UX: Clean, professional interface with smooth animations
SEO Optimized: Proper meta tags, schema markup, and semantic HTML
Accessibility: WCAG compliant with proper ARIA labels and keyboard navigation
Performance: Optimized images and efficient code for fast loading
Interactive Elements: Image sliders, animated navigation, and form validation
Contact Form: Functional contact form with Formspree integration

🛠️ Technologies Used

HTML5: Semantic markup with accessibility features
CSS3: Custom properties, Flexbox, Grid, and animations
JavaScript: ES6+ for interactive functionality
Font Awesome: Professional icons
Formspree: Contact form handling

📁 Project Structure

javad-beig-portfolio/
│
├── index.html
├── assets/
│   ├── backgrounds/
│   │   ├── IMG_1.jpg
│   │   ├── IMG_2.jpg
│   │   └── ...
│   ├── certificates/
│   │   └── C_1.jpg
│   ├── documents/
│   │   ├── Javad_Beig_Resume.pdf
│   │   └── P_1.pdf
│   ├── favicon/
│   │   ├── favicon-96x96.png
│   │   ├── favicon.svg
│   │   └── ...
│   ├── profile/
│   │   └── Profile.jpg
│   └── project/
│       └── project1/
│           ├── IMG_1.jpg
│           ├── IMG_2.jpg
│           └── IMG_3.jpg
├── css/
│   └── styles.css
└── README.md

🚀 Setup and Deployment

Local Development
Clone the repository:

bash
git clone https://github.com/javad-beig/javad-beig.github.io.git
Navigate to the project directory:

bash
cd javad-beig.github.io
Open index.html in your browser or use a local server:

bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve

GitHub Pages Deployment

Ensure all files are committed and pushed to the main branch
Go to repository Settings → Pages
Select source: "Deploy from a branch"
Select branch: "main" and folder: "/root"
Your site will be published at https://javad-beig.github.io

Custom Domain (Optional)
Purchase a domain from a provider like Namecheap or GoDaddy
In your repository Settings → Pages, add your custom domain
Configure DNS records with your domain provider:
Add A records pointing to GitHub's IPs:
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
Or add a CNAME record pointing to javad-beig.github.io

📝 Content Updates

To update content on the portfolio:
Personal Information: Edit the relevant sections in index.html
Projects: Add new project cards in the Projects section
Images: Replace images in the assets folder and update references
Resume: Replace assets/documents/Javad_Beig_Resume.pdf with an updated version

🔧 Customization Guide

Changing Color Scheme
Modify the CSS custom properties in the :root selector:

:root {
  --primary-color: #2563eb;    /* Main brand color */
  --secondary-color: #1d50c0;  /* Secondary color */
  --text-color: #374151;       /* Main text color */
  --light-bg: #f9fafb;         /* Background color */
}
Adding New Sections

Add a new section in the HTML with proper ID
Update navigation with a new link
Style the section in CSS

Modifying Animations

Adjust animation timing and properties in the CSS keyframes:
@keyframes fadeIn {
  from { opacity: 0; }
  to { opacity: 1; }
}

📊 SEO Optimization

This portfolio includes:
Semantic HTML5 markup
JSON-LD structured data
Open Graph meta tags for social sharing
Twitter Card meta tags
Proper heading hierarchy
Alt text for all images
XML sitemap (recommended to add)

📈 Performance Tips

Compress images before uploading (aim for <200KB each)
Minimize CSS and JavaScript files
Utilize browser caching
Consider implementing a CDN for assets

🤝 Contributing

While this is a personal portfolio, suggestions and improvements are welcome:
Fork the repository
Create a feature branch
Commit your changes
Push to the branch
Open a Pull Request

📄 License

This project is open source and available under the MIT License.

🙏 Acknowledgments

Design and development by Mohammed Adnan Shakeel
Icons by Font Awesome
Form handling by Formspree

📞 Contact

Javad Beig - jawadbaig2002@gmail.com
Portfolio Link: https://javad-beig.github.io
LinkedIn: https://www.linkedin.com/in/javad-beig2002/
GitHub: https://github.com/javad-beig

⭐️ Feel free to star this repository if you find it helpful!
