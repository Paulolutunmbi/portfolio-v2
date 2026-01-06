# Paul Olutunmbi (DevHumble) - Portfolio Website

A fully responsive, modern portfolio website built with HTML, Tailwind CSS, and minimal JavaScript.

## 🚀 Features

- **Fully Responsive Design** - Works perfectly on mobile, tablet, and desktop
- **Modern UI/UX** - Clean, techy, and visually appealing design
- **Smooth Animations** - Slide-in effects and floating icons
- **Interactive Elements** - Hover effects on buttons and project cards
- **Fixed Navigation** - Sticky navbar with mobile menu
- **Floating Social Icons** - Easy access to social media links
- **4 Pages**:
  - Home/Landing Page
  - About Me
  - Projects Portfolio
  - Contact Page

## 📁 File Structure

```
portfolio-tailwind/
├── index-new.html      # Home/Landing Page
├── about-new.html      # About Me Page
├── project-new.html    # Projects Page
├── contact-new.html    # Contact Page
├── profile-picture.jpg # Your profile picture (add this file)
└── README.md          # This file
```

## 🖼️ How to Replace Profile Picture

### Option 1: Add an Image File
1. Save your profile picture as `profile-picture.jpg` in the same folder as the HTML files
2. The image will automatically appear on the Home and About pages

### Option 2: Use a Different Filename
1. Save your profile picture with any name (e.g., `my-photo.png`)
2. Open `index-new.html` and find this line (around line 103):
   ```html
   <img src="profile-picture.jpg" alt="Paul Olutunmbi - DevHumble" ...>
   ```
3. Replace `profile-picture.jpg` with your filename: `my-photo.png`
4. Repeat for `about-new.html` (around line 66)

### Option 3: Use an Online Image URL
1. Upload your image to a service like Imgur, Cloudinary, or GitHub
2. Copy the image URL
3. Replace `profile-picture.jpg` with the full URL in both files

## 🎨 Customization Guide

### Change Colors
The site uses a blue-purple gradient theme. To change colors:
- Open any HTML file
- Find classes like `bg-blue-500`, `text-purple-400`, etc.
- Replace with Tailwind color classes (e.g., `bg-green-500`, `text-red-400`)

### Update Personal Information
- **Name/Title**: Search for "Paul Olutunmbi" or "DevHumble" and replace
- **Email**: Replace `oluwatunmbipaul@gmail.com`
- **Phone**: Replace `+2347071102618`
- **Social Links**: Update GitHub, LinkedIn, WhatsApp URLs

### Add/Remove Projects
1. Open `project-new.html`
2. Find the projects grid section
3. Copy a project card div and modify:
   - Title
   - Description
   - Technologies (tags)
   - GitHub and Live Demo links

## 🌐 How to View the Website

### Option 1: Open Locally
1. Rename the files (remove `-new` suffix):
   - `index-new.html` → `index.html`
   - `about-new.html` → `about.html`
   - `project-new.html` → `project.html`
   - `contact-new.html` → `contact.html`
2. Double-click `index.html` to open in your browser

### Option 2: Use Live Server (Recommended)
1. Install Live Server extension in VS Code
2. Right-click `index-new.html`
3. Select "Open with Live Server"

### Option 3: Deploy Online
**Deploy to Vercel (Free)**:
1. Rename files (remove `-new`)
2. Create a GitHub repository
3. Push your code to GitHub
4. Go to [vercel.com](https://vercel.com)
5. Import your GitHub repository
6. Deploy!

**Deploy to Netlify (Free)**:
1. Drag and drop your folder to [netlify.com/drop](https://app.netlify.com/drop)

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **Tailwind CSS** - Utility-first CSS framework (via CDN)
- **Font Awesome** - Icons (via CDN)
- **JavaScript** - Minimal JS for mobile menu toggle

## ✨ Key Sections

### Home Page (`index-new.html`)
- Hero section with profile picture and introduction
- Quick tech stack preview
- Call-to-action buttons
- Floating social icons

### About Page (`about-new.html`)
- Detailed background information
- Skills and technologies grid
- Soft skills and interests
- Professional stats

### Projects Page (`project-new.html`)
- 5 featured projects with descriptions
- Live demo and GitHub links
- Technology tags
- Hover animations

### Contact Page (`contact-new.html`)
- Contact methods (Email, WhatsApp, GitHub, LinkedIn)
- Contact form
- Additional information
- Social media links

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🎯 Performance Features

- **CDN Resources** - Fast loading of Tailwind and Font Awesome
- **Minimal JavaScript** - Only for essential interactions
- **Optimized Animations** - Smooth CSS animations
- **Semantic HTML** - Better SEO and accessibility

## 📝 Notes

- The contact form currently shows an alert on submission. To make it functional:
  - Connect to a backend service (FormSpree, EmailJS, etc.)
  - Or use a serverless function
  
- All external links open in new tabs (`target="_blank"`)

- The profile picture has a fallback to show initials "PO" if the image is not found

## 🤝 Support

If you have questions or need help customizing:
- Email: oluwatunmbipaul@gmail.com
- WhatsApp: +2347071102618

## 📄 License

Free to use and modify for personal purposes.

---

**Built with ❤️ by Paul Olutunmbi (DevHumble)**
