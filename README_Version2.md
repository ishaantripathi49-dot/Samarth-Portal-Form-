# 📋 Samarth Portal - Faculty Profile Management System

A complete online faculty profile management system with admin dashboard and faculty submission form.

## 🚀 Features

- ✅ **Faculty Form**: Comprehensive 56-field faculty profile form
- ✅ **Admin Dashboard**: View and manage all submissions
- ✅ **Search & Filter**: Quick search by name, email, or employee code
- ✅ **Download Excel**: Export all records as Excel spreadsheet
- ✅ **Real-time Stats**: Total and today's submission counts
- ✅ **Responsive Design**: Works on desktop, tablet, and mobile
- ✅ **Free Hosting**: Hosted on GitHub Pages
- ✅ **Secure**: Simple email/password authentication

## 📱 Live URLs

- **Admin Dashboard**: `https://yourusername.github.io/samarth-portal/`
- **Faculty Form**: `https://yourusername.github.io/samarth-portal/form.html`

## 🔐 Admin Credentials

- **Email**: `ishaantripathi49@csauk.ac.in`
- **Password**: `IshaanTripathi890@`

## 📝 How to Use

### For Faculty Members:
1. Visit the Faculty Form page
2. Fill in all required information
3. Click "Submit Form"
4. Data is automatically saved

### For Admin:
1. Visit the Admin Dashboard
2. Login with credentials
3. View all submissions in table format
4. Search for specific faculty members
5. Download all records as Excel file
6. Click Refresh to see new submissions

## 🛠️ Setup Instructions

1. **Create GitHub Repository**
   - Go to https://github.com/new
   - Name it `samarth-portal`
   - Make it Public
   - Click Create

2. **Upload Files**
   - Upload `index.html`
   - Upload `form.html`
   - Upload `README.md`

3. **Enable GitHub Pages**
   - Go to Settings → Pages
   - Select `main` branch
   - Click Save
   - Wait 1-2 minutes for deployment

4. **Access Your Site**
   - Your site is live at: `https://yourusername.github.io/samarth-portal/`

## 📊 Data Storage

Data is stored in browser's **LocalStorage** which means:
- ✅ All data persists even after closing browser
- ✅ Works offline
- ✅ No server required
- ⚠️ Data is specific to each browser/device
- ⚠️ Clearing browser cache will delete data

## 🔄 Switching Admin Credentials

To change login credentials, edit `index.html`:

```javascript
const ALLOWED_EMAIL = "your-email@example.com";
const ALLOWED_PASSWORD = "your-password";
```

## 🎨 Customization

### Change Colors
Search for `#667eea` and `#764ba2` in HTML files to update gradient colors.

### Add More Fields
Add new form groups in `form.html` following the existing pattern.

### Change Organization Name
Replace "Samarth Portal" with your institution name in both HTML files.

## 📱 Browser Support

- Chrome/Edge ✅
- Firefox ✅
- Safari ✅
- Mobile Browsers ✅

## 📞 Support

For issues or feature requests, check the repository issues section.

---

**Made with ❤️ for Educational Institutions**