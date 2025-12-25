# Digital Identity Wallet - ReadMe

## 📌 Project Overview

**Digital Identity Wallet** is a secure web application that allows users to digitally store and manage their important identity documents. It functions like a digital wallet for your ID cards, passports, driver's licenses, and other critical documents.

## ✨ Key Features

### 🛡️ **Security First**
- Dual Firebase Project Architecture for enhanced security
- Separate authentication and storage systems
- Encrypted document storage
- Secure user authentication

### 📱 **User-Friendly Interface**
- Clean, modern design with light/dark themes
- Mobile-responsive layout
- Progressive Web App (PWA) support
- Installable as a mobile app

### 📄 **Document Management**
- Upload identity documents (images)
- Categorize documents (Passport, ID, License, etc.)
- Set expiry dates and reminders
- View documents in full-screen
- Edit document details
- Delete documents when no longer needed

### 🔔 **Smart Notifications**
- Automatic expiry tracking
- Reminder system for upcoming renewals
- Visual indicators for document status
- Notification banners for expiring documents

### 👤 **User Account Features**
- Secure registration and login
- Password change functionality
- Account deletion with data cleanup
- Document statistics and insights

## 🎯 Benefits

### For Users:
- **Always Accessible** - Access your documents from any device
- **Never Miss Expiry** - Automatic reminders for renewals
- **Reduce Physical Loss Risk** - Digital backup of important IDs
- **Organized Storage** - Categorize and search documents easily
- **Privacy Control** - Your data stays with you

### For Organizations:
- **No Storage Costs** - Uses Firebase free tier
- **Easy Deployment** - Single HTML file setup
- **Scalable** - Can handle multiple users
- **Secure** - Built with modern security practices

## 💼 Use Cases

### Personal Use:
- Store passports, driver's licenses, national IDs
- Keep insurance cards and medical records
- Store educational certificates
- Manage vehicle documents

### Professional Use:
- Store professional licenses
- Keep employment documents
- Manage business certifications
- Store tax identification documents

## 🚀 Getting Started

### Prerequisites:
1. Modern web browser (Chrome, Firefox, Safari, Edge)
2. Internet connection
3. Email address for registration

### Quick Start:
1. Open the application in your browser
2. Create an account using your email
3. Start uploading your documents
4. Set expiry dates for reminders
5. Access from any device with your login

## 🔧 Technical Highlights

### Architecture:
- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Authentication**: Firebase Auth (Project A)
- **Database**: Firestore (Project A)
- **Storage**: Firebase Storage (Project B)
- **PWA**: Service Workers, Web App Manifest

### Security Features:
- Separate Firebase projects for auth and storage
- User-based access control
- Secure file uploads with validation
- Automatic cleanup on deletion
- No sensitive data in client code

## 📱 Mobile Experience

### PWA Features:
- Install as a mobile app
- Works offline (cached documents)
- Push notification support
- Native app-like experience
- Home screen icon

### Mobile Optimizations:
- Touch-friendly interface
- Responsive design
- Fast loading times
- Gesture support

## 🔄 Document Lifecycle Management

1. **Upload** - Add new documents with images
2. **Categorize** - Organize by type
3. **Set Dates** - Define expiry and reminder dates
4. **Monitor** - Track status (Active/Expiring/Expired)
5. **Renew** - Get reminders before expiry
6. **Archive** - Remove outdated documents

## 📊 Statistics & Insights

The dashboard provides:
- Total document count
- Active documents
- Expiring soon alerts
- Expired documents
- User activity overview

## 🎨 Themes & Customization

- Light and dark mode support
- Automatic theme detection
- Theme persistence
- Accessibility-friendly design

## 🛡️ Data Privacy

### What We Store:
- User email (for authentication)
- Document metadata (titles, dates, categories)
- Document images (encrypted in storage)

### What We Don't Store:
- Passwords (hashed by Firebase)
- Personal identification numbers
- Sensitive text data
- Location information

## 🔄 Backup & Recovery

- All data stored in Firebase cloud
- Automatic sync across devices
- Manual document downloads available
- Account recovery via email

## 💡 Tips for Best Use

1. **Use Clear Titles** - Name documents meaningfully
2. **Set Realistic Reminders** - 30 days before expiry works well
3. **Categorize Properly** - Makes finding documents easier
4. **Regular Cleanup** - Remove outdated documents
5. **Keep App Updated** - For latest features and security

## 🆘 Support & Troubleshooting

### Common Issues:
- **Upload Fails**: Check file size (max 5MB) and format (images only)
- **Login Issues**: Reset password or check email confirmation
- **Slow Loading**: Check internet connection

### Best Practices:
- Use strong passwords
- Log out on shared devices
- Keep backup of critical documents
- Update contact email if changed

## 📈 Future Roadmap

Planned enhancements:
- Multi-language support
- Document sharing (secure)
- Bulk uploads
- Advanced search filters
- PDF document support
- Family/group accounts

## 🤝 Contributing

This is a standalone project built for personal document management. The code is self-contained in a single HTML file for easy deployment and use.

## 📄 License

This project is for personal use. Users are responsible for complying with local data protection regulations when storing identity documents.

---

**Note**: This application is designed for personal document management. Always keep physical copies of critical documents as required by law. Digital storage is a convenience feature, not a legal replacement for original documents in most jurisdictions.
