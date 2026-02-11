# EventHub - College Event Management System

A complete, production-ready College Event Management System built with HTML, CSS, Bootstrap 5, and JavaScript. Features separate admin and student portals with full event lifecycle management.

## 🎯 Features

### **For Administrators**
- **Dashboard Overview**: Real-time statistics, charts, and activity monitoring
- **Event Creation**: Comprehensive event creation with validation
- **Event Management**: Edit, delete, close registrations, view participants
- **Participant Management**: Search, filter, and export participant data
- **System Controls**: Reset system, manage roles

### **For Students**
- **Browse Events**: Search and filter events by category
- **Event Registration**: Simple registration with pre-filled student data
- **My Events**: View all registered events with status tracking
- **Certificates**: Download participation certificates for completed events
- **Profile Management**: Edit personal information and view participation history

## 🚀 Getting Started

### Quick Start
1. Open `index.html` in your browser
2. Select your role (Admin or Student)
3. Login with demo credentials

### Demo Credentials

**Admin Account:**
- Username: `admin`
- Password: `admin123`

**Student Account:**
- Username: `student`
- Password: `student123`

## 📁 Project Structure

```
EventHub/
├── index.html                 # Landing page with role selection
├── login.html                 # Authentication page
│
├── Admin Pages
│   ├── admin-dashboard.html   # Admin dashboard with statistics
│   ├── create-event.html      # Event creation form
│   ├── manage-events.html     # Event management interface
│   ├── participants.html      # Participant list and management
│   └── admin-profile.html     # Admin profile page
│
├── Student Pages
│   ├── student-dashboard.html # Student dashboard
│   ├── events.html            # Browse all events
│   ├── event-details.html     # Event details and registration
│   ├── my-events.html         # Student's registered events
│   ├── certificates.html      # Certificate downloads
│   └── student-profile.html   # Student profile and history
│
└── README.md                  # This file
```

## 🎨 Design Features

- **Modern UI/UX**: Clean, professional SaaS-style interface
- **Custom Color Palette**: Unique gradient-based design system
- **Responsive Design**: Works on desktop, tablet, and mobile
- **Smooth Animations**: Subtle transitions and hover effects
- **Consistent Branding**: Unified visual identity throughout

## 💾 Data Management

All data is stored in browser's `localStorage`:
- **events**: Array of all events
- **participants**: Array of all registrations
- **current_user**: Current logged-in user session
- **admin_user**: Default admin account
- **student_user**: Default student account

## 🔧 Technical Details

### Technologies Used
- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Bootstrap 5.3
- JavaScript (ES6+)
- Google Fonts (Syne + Inter)
- Bootstrap Icons

### Browser Compatibility
- Chrome (recommended)
- Firefox
- Safari
- Edge

## 📋 Usage Guide

### Creating an Event (Admin)
1. Go to "Create Event" from the navigation
2. Fill in all required fields:
   - Event name, category, description
   - Date, time, venue
   - Registration deadline
   - Maximum participants
   - Organizer details
3. Click "Create Event"

### Registering for an Event (Student)
1. Browse events from "Events" page
2. Click "View & Register" on an open event
3. Review event details
4. Fill in registration form (pre-filled with profile data)
5. Click "Register Now"

### Managing Events (Admin)
1. Go to "Manage Events"
2. Use search and filters to find events
3. Options available:
   - View participants
   - Open/Close registration
   - Delete event

## 🔐 Security Notes

**Important**: This is a frontend-only demo application using localStorage. In production:
- Implement proper backend authentication
- Use secure password hashing
- Validate all inputs server-side
- Implement role-based access control
- Use HTTPS for all communications

## 🌟 Key Highlights

✅ **Production-Ready UI**: Professional, polished interface  
✅ **Complete Workflow**: Full event lifecycle from creation to certificates  
✅ **Responsive Design**: Works seamlessly on all devices  
✅ **User-Friendly**: Intuitive navigation and clear feedback  
✅ **Scalable Architecture**: Easy to integrate with backend  
✅ **Resume-Worthy**: Demonstrates full-stack development skills  

## 🔄 Future Enhancements

Potential features to add:
- Email notifications
- Real-time chat/Q&A
- Event categories expansion
- Advanced analytics dashboard
- Social media integration
- Payment gateway for paid events
- Multi-language support
- Dark/Light theme toggle

## 📱 Mobile Responsiveness

All pages are fully responsive with:
- Collapsible navigation menu on mobile
- Optimized layouts for small screens
- Touch-friendly buttons and interactions
- Readable typography at all sizes

## 🎯 Learning Outcomes

This project demonstrates:
- Frontend development best practices
- Modern CSS techniques (Grid, Flexbox, Custom Properties)
- JavaScript event handling and DOM manipulation
- localStorage API usage
- Form validation and user feedback
- Responsive design principles
- Component-based architecture

## 📞 System Reset

To reset all data:
1. Login as Admin
2. Click profile dropdown
3. Select "Reset System"
4. Confirm the action

This will clear all events and participants but preserve default accounts.

## 🎓 Educational Value

Perfect for:
- College projects
- Portfolio demonstrations
- Learning full-stack concepts
- Understanding CRUD operations
- Practicing UI/UX design
- Preparing for internships

## 📝 Notes

- First-time users should start by creating events as admin
- Student accounts can only register for events created by admin
- Certificates are simulated (download functionality is a placeholder)
- All timestamps are based on browser's local time
- No data persists after clearing browser storage

## 🏆 Credits

**Design Inspiration**: Modern SaaS applications  
**Color Palette**: Custom gradient system  
**Fonts**: Syne (headings), Inter (body)  
**Icons**: Bootstrap Icons

---

**Built with ❤️ for college event management**

*EventHub - Making campus events simple and accessible*
