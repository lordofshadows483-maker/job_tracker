# 📊 Job Application Tracker

A clean, modern web application to help organize and track your job search process. Built with vanilla HTML, CSS, and JavaScript - no frameworks or dependencies required.

![Job Application Tracker](https://via.placeholder.com/800x400/4F46E5/FFFFFF?text=Job+Application+Tracker)

## ✨ Features

- **📝 Application Management** - Add, edit, and delete job applications with ease
- **📈 Real-time Statistics** - View dashboard showing total applications, interviews, and offers
- **🎨 Clean UI** - Modern, responsive design that works on desktop and mobile
- **💾 Persistent Storage** - Your data automatically saves to browser localStorage
- **🏷️ Status Tracking** - Track applications through stages: Applied, Interview, Offer, Rejected
- **📅 Date Tracking** - Record when you applied to each position
- **📝 Notes Section** - Keep track of referrals, interview dates, and follow-ups
- **⚡ Fast & Lightweight** - Single HTML file, no installation required

## 🚀 Quick Start

### Option 1: Local Use
1. Download the `job-tracker.html` file
2. Double-click to open in any web browser
3. Start tracking your applications!

### Option 2: Online Hosting
Upload to any static hosting service:
- **GitHub Pages** - Free hosting for your project
- **CodePen** - Quick sharing and demonstration
- **Netlify/Vercel** - Professional deployment options

## 💻 Usage

### Adding an Application
1. Fill in the company name and position
2. Select the current status (Applied, Interview, Offer, or Rejected)
3. Choose the date you applied (defaults to today)
4. Add any notes about the application
5. Click "Add Application"

### Editing an Application
1. Click the edit icon (✏️) next to any application
2. Modify the information
3. Click "Save Changes"

### Tracking Progress
- View your statistics dashboard at the top
- See total applications, current interviews, and offers received
- Filter by status using the color-coded badges

## 🛠️ Technical Details

**Built With:**
- HTML5
- CSS3 (Tailwind CDN)
- Vanilla JavaScript (ES6+)

**Browser Compatibility:**
- Chrome/Edge (recommended)
- Firefox
- Safari
- Any modern browser with localStorage support

**Data Storage:**
- Uses browser localStorage API
- Data persists across sessions
- No server or database required

## 📂 Project Structure

```
job-tracker.html          # Single-file application
├── HTML Structure        # Semantic markup
├── Tailwind CSS         # Utility-first styling via CDN
└── JavaScript Logic     # CRUD operations & state management
```

## 🎯 Why This Project?

This project demonstrates:
- **Clean Code** - Readable, maintainable JavaScript
- **UI/UX Design** - User-friendly interface with visual feedback
- **Data Management** - CRUD operations with persistent storage
- **Responsive Design** - Works on all screen sizes
- **Problem Solving** - Addresses a real-world need for job seekers

## 🔧 Customization

### Changing Colors
Modify the Tailwind classes in the HTML to match your brand:
```html
<!-- Change primary color from blue to purple -->
bg-blue-600 → bg-purple-600
text-blue-800 → text-purple-800
```

### Adding New Status Types
Update the status dropdown and color mapping:
```javascript
const statusColors = {
    applied: 'bg-blue-100 text-blue-800',
    interview: 'bg-yellow-100 text-yellow-800',
    offer: 'bg-green-100 text-green-800',
    rejected: 'bg-red-100 text-red-800',
    yourNewStatus: 'bg-color-100 text-color-800'  // Add here
};
```

<img width="1435" height="790" alt="image" src="https://github.com/user-attachments/assets/279d3ee7-6ffd-4be5-a964-1f5e2d015331" />


### Dashboard View
Track all your applications in one place with real-time statistics.

### Add Application Form
Simple, intuitive form to add new job applications quickly.

### Application Table
View all your applications with status badges and quick actions.

## 🤝 Contributing

Feel free to fork this project and customize it for your needs! Some ideas for enhancements:

- Export data to CSV/PDF
- Email reminders for follow-ups
- Integration with job boards APIs
- Dark mode toggle
- Advanced filtering and sorting
- Company research links

## 📄 License

This project is open source and available for anyone to use, modify, and share.

## 👤 Author

Created as a portfolio project to demonstrate web development skills.

## 🌟 Show Your Support

If this project helped you in your job search, consider:
- ⭐ Starring the repository
- 📤 Sharing it with other job seekers
- 💬 Providing feedback for improvements

---

**Good luck with your job search! 🎯**

*Remember: Staying organized is half the battle in landing your dream job.*
