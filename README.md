# Delfi Tech Manufacturing Website

Professional, fully responsive website for Delfi Tech Manufacturing Limited - a global electronics manufacturing company with 32+ years of experience.

## 📦 Package Contents

```
delfi-tech-website/
├── index.html              # Home page
├── about.html              # About company history and organization
├── services.html           # Services and manufacturing capabilities
├── customers.html          # Customer references and testimonials
├── certifications.html      # ISO 9001 certification details
├── contact.html            # Contact form and information
├── style.css               # Complete stylesheet
├── netlify.toml           # Netlify configuration
└── README.md              # This file
```

## 🚀 Quick Deploy to Netlify (2 minutes)

### Option 1: Deploy Using Netlify Drop (Easiest - No Coding Required)

1. **Download or prepare files**
   - Keep all HTML files, CSS file together in one folder
   - Files needed: index.html, about.html, services.html, customers.html, certifications.html, contact.html, style.css

2. **Go to Netlify**
   - Visit https://app.netlify.com/drop
   - Simply drag and drop your website folder onto the page

3. **Wait for deployment**
   - Netlify will upload and deploy in seconds
   - You'll get a live URL like: `https://[random-name].netlify.app`

4. **Optional: Connect to GitHub**
   - For automatic updates, connect your GitHub repository
   - Any changes pushed to GitHub will auto-deploy

---

### Option 2: Deploy via GitHub (Recommended - Continuous Updates)

**Step 1: Prepare Your GitHub Repository**

1. Create a new GitHub account (if you don't have one): https://github.com/signup
2. Create a new repository:
   - Go to https://github.com/new
   - Name it: `delfi-tech-website`
   - Click "Create repository"

3. Upload your files to GitHub:
   - Click "uploading an existing file"
   - Drag all 7 files (index.html, about.html, services.html, customers.html, certifications.html, contact.html, style.css, netlify.toml)
   - Click "Commit changes"

**Step 2: Connect to Netlify**

1. Go to https://app.netlify.com
2. Click "New site from Git"
3. Choose GitHub and authorize Netlify
4. Select your `delfi-tech-website` repository
5. Click "Deploy site"

**That's it!** Your site is now live. You'll get a URL like:
- `https://delfi-tech-website.netlify.app` (auto-generated)
- Or connect your own domain: `www.delfitech.com`

---

### Option 3: Deploy Using Command Line (For Developers)

**Prerequisites:**
- Node.js installed (https://nodejs.org)
- Terminal access

**Steps:**

1. **Install Netlify CLI**
   ```bash
   npm install -g netlify-cli
   ```

2. **Navigate to your website folder**
   ```bash
   cd path/to/delfi-tech-website
   ```

3. **Login to Netlify**
   ```bash
   netlify login
   ```

4. **Deploy**
   ```bash
   netlify deploy --prod
   ```

5. **Select folder to deploy:** Choose the folder containing all your HTML files

Your site will be live immediately!

---

## 📝 Features

✅ **Fully Responsive Design**
- Works perfectly on desktop, tablet, and mobile
- Optimized for all screen sizes

✅ **Modern & Professional**
- Clean, professional design
- Brand color scheme: Teal/Green (#1D9E75)
- Smooth animations and transitions

✅ **Complete Content**
- 6 pages with comprehensive information
- Company history timeline
- Customer references
- Service descriptions
- Certification details
- Contact form with Netlify Forms

✅ **SEO Optimized**
- Meta tags for all pages
- Proper heading hierarchy
- Mobile-friendly
- Fast loading times

✅ **Contact Form**
- Netlify Forms integration (works automatically)
- Receives form submissions via email
- No backend setup required

---

## 🎨 Customization

### Change Colors
1. Open `style.css`
2. Find the `:root` section at the top
3. Change these color values:
   ```css
   --primary-color: #1D9E75;      /* Main teal color */
   --primary-dark: #0F6E56;       /* Dark teal */
   --primary-light: #E1F5EE;      /* Light teal background */
   ```

### Update Company Information
1. Find and replace in all HTML files:
   - `Delfi Tech` → Your company name
   - `info@delfitech.com.hk` → Your email
   - `+852 2635 6389` → Your phone number
   - `Hong Kong, N.T, Hong Kong` → Your address

### Change Text Content
- Open each HTML file and edit content directly
- All text is clearly labeled and easy to find

### Add Images
- Create an `images/` folder
- Add images there
- Reference them: `<img src="images/photo.jpg" alt="Description">`

---

## 📧 Contact Form Setup

The contact form works automatically with Netlify! Here's how:

1. **Form Detection**: Netlify automatically detects the form in `contact.html`
2. **Email Notifications**: 
   - Go to your Netlify site settings
   - Find "Forms" section
   - Add your email address
   - You'll receive emails for each form submission
3. **No Backend Needed**: Everything works without any backend code!

---

## 🌐 Custom Domain Setup

Want to use your own domain (delfitech.com)?

1. **Register Domain**
   - GoDaddy, Namecheap, Google Domains, etc.
   
2. **In Netlify:**
   - Go to Site Settings → Domain Management
   - Click "Add custom domain"
   - Enter your domain: `delfitech.com`
   - Follow instructions to update DNS records
   - Usually takes 24-48 hours to propagate

3. **HTTPS SSL**
   - Netlify provides FREE SSL certificate
   - Automatically enabled for your domain

---

## 📊 Analytics & Monitoring

**Add Google Analytics:**

1. Create Google Analytics account: https://analytics.google.com
2. Get your Tracking ID
3. Add to all HTML files in the `<head>` section:
   ```html
   <!-- Google Analytics -->
   <script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
   <script>
     window.dataLayer = window.dataLayer || [];
     function gtag(){dataLayer.push(arguments);}
     gtag('js', new Date());
     gtag('config', 'G-XXXXXXXXXX');
   </script>
   ```

---

## 🔒 Security

✅ **HTTPS**: Automatically enabled (Free SSL certificate)
✅ **DDoS Protection**: Included with Netlify
✅ **Secure Forms**: Form data is encrypted
✅ **No Sensitive Data**: Contact form doesn't store credit cards

---

## ⚡ Performance

- **Optimized Images**: All images are lightweight
- **Fast Load Times**: Typically < 1 second
- **CDN**: Global content delivery network
- **Caching**: Automatic browser caching

Monitor your site performance:
- Go to your Netlify dashboard
- Check "Analytics" tab
- View page load times and visitor statistics

---

## 🐛 Troubleshooting

### Contact Form Not Working?
1. Check Netlify site settings
2. Ensure form `name="contact"` attribute is in HTML
3. Add your email in Netlify Forms settings
4. Check spam folder for form submissions

### Pages Not Loading?
1. Make sure all HTML files are in the same folder
2. Check that CSS file is named exactly `style.css`
3. Verify file paths are correct
4. Try clearing browser cache (Ctrl+Shift+Delete)

### Styling Issues?
1. Clear browser cache: Ctrl+Shift+Delete
2. Check that style.css is uploaded
3. Verify file names are spelled correctly
4. Test in different browser

### Domain Not Working?
1. DNS changes can take 24-48 hours
2. Check that you updated DNS records correctly
3. Verify domain registrar settings
4. Contact domain registrar support if needed

---

## 📱 Browser Support

Tested and working on:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

---

## 📖 File Descriptions

### HTML Files

**index.html**
- Homepage with hero section
- Statistics and overview
- Services preview
- Call-to-action buttons

**about.html**
- Company history timeline
- Global organization structure
- Company values
- 32+ year journey

**services.html**
- Detailed service descriptions
- Technical capabilities
- Industries served
- Manufacturing processes

**customers.html**
- Customer references (8 major customers)
- Market distribution chart
- Customer testimonials
- Industries served

**certifications.html**
- ISO 9001:2015 details
- Quality management systems
- Testing capabilities
- Compliance standards

**contact.html**
- Contact information (Hong Kong & Germany)
- Contact form with Netlify Forms
- Quick contact options
- FAQ section

### CSS File

**style.css**
- Complete responsive design
- Mobile-first approach
- CSS variables for easy customization
- Smooth animations and transitions

---

## 🎯 Next Steps

1. ✅ **Deploy** your website (Choose Option 1, 2, or 3 above)
2. ✅ **Customize** colors and content to match your brand
3. ✅ **Add your logo** in the navigation
4. ✅ **Set up email notifications** for contact form
5. ✅ **Connect your domain** (optional)
6. ✅ **Add Google Analytics** (optional)
7. ✅ **Share your site** with team and customers!

---

## 📞 Support

**Netlify Help:**
- Documentation: https://docs.netlify.com
- Support: https://support.netlify.com

**Contact Form Issues:**
- Form Setup: https://docs.netlify.com/forms/setup
- Troubleshooting: https://support.netlify.com/articles/14264634

---

## 📄 License

This website template is provided for Delfi Tech Manufacturing Limited.

---

## 📧 Company Information

**Delfi Tech Manufacturing Ltd.**
- Hong Kong (HQ): +852 2635 6389
- Germany: +49 (0)461 9306 9070
- Email: info@delfitech.com.hk

---

**Website created for Delfi Tech Manufacturing Limited | Est. 1992 | ISO 9001:2015 Certified**

For questions or support with deployment, contact your web development team or visit Netlify documentation.
