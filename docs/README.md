# MindCareHub - Mental Health Management System

# Developed by: 
1. HANIS NABILA BINTI MOHD FAIZAL
2. NUR HEIDI EIZALEIA BINTI SHAHIS IDZMAN

## Overview
MindCareHub is a comprehensive web-based mental health management system designed for healthcare administrators to manage appointments, clients, counselors, and session notes efficiently.

## Features

### Dashboard
- Real-time statistics overview
- Monthly appointment charts
- Counselor availability tracking
- Client status monitoring
- Session notes summary

### Appointments Management
- Schedule new appointments
- View and manage existing appointments
- Filter appointments by status (Pending, Confirmed, Completed, Cancelled)
- Calendar integration

### Client Management
- Add and manage client profiles
- Track client status (Active/Inactive)
- Comprehensive client information storage
- Search and filter capabilities

### Counselor Management
- Manage counselor profiles
- Track counselor availability
- Performance monitoring
- Schedule management

### Session Notes
- Create and manage therapy session notes
- Tag system for categorization
- Session status tracking
- Progress monitoring

### Settings & Customization
- Theme selection (Light/Dark/Auto)
- Accent color customization
- Font size adjustment
- Compact sidebar option
- Reduced motion settings

## Technology Stack

- **Frontend**: HTML5, CSS3, Bootstrap 5.3.3
- **JavaScript**: Vanilla JS with Chart.js for data visualization
- **Icons**: Bootstrap Icons
- **Storage**: Local Storage for data persistence
- **Responsive Design**: Mobile-first approach

## Getting Started

1. **Setup**: Open `index.html` in a web browser
2. **Login**: Use the login interface to access the system
   - **Username**: `admin`
   - **Password**: `1234`
   - Click "Login" button to access the dashboard
3. **Navigation**: Use the sidebar navigation to access different modules
4. **Responsive**: The system works on desktop, tablet, and mobile devices

### Test Credentials
For testing purposes, use the following login credentials:
- **Username**: `admin`
- **Password**: `1234`

> **Note**: These are demo credentials for testing the system functionality.

## Framework Structure / File Structure

```
MINDCAREHUB/
├── docs/
│   └── README.md
├── css/
│   └── style.css
├── js/
│   └── app.js
├── images/
├── index.html (Login page)
├── dashboard.html
├── appointments.html
├── clients.html
├── counselors.html
├── session_notes.html
├── profile.html
└── settings.html
```


## Key Features

### Theme Support
- Light Mode
- Dark Mode
- Auto Mode (follows system preference)
- Customizable accent colors

### Mobile Responsive
- Optimized for mobile devices
- Touch-friendly interface
- Collapsible sidebar navigation
- Responsive charts and tables

### Security Features
- Session management
- Secure logout functionality
- Data validation
- Local storage encryption

### Data Visualization
- Interactive charts using Chart.js
- Real-time statistics
- Progress tracking
- Visual analytics

## Usage Instructions

### Dashboard
- View system overview and key metrics
- Monitor appointment trends
- Check counselor availability
- Review recent activities

### Managing Appointments
1. Navigate to Appointments page
2. Click "Add Appointment" to create new
3. Fill in client, counselor, date, and time
4. Save and manage appointment status

### Client Management
1. Go to Clients page
2. Add new clients with comprehensive information
3. Update client status and details
4. Search and filter client list

### Session Notes
1. Access Session Notes page
2. Create new session notes
3. Use tags for categorization
4. Track session progress and outcomes

### Settings Configuration
1. Open Settings page
2. Customize theme and appearance
3. Adjust accessibility options
4. Configure system preferences

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge

## Data Storage

The system uses browser Local Storage for data persistence:
- Client data: `mindcare_clients_data`
- Appointment data: `mindcare_appointments_data`
- Session data: `mindcare_sessions_data`
- Settings: `mindcarehub_settings`

## Development Notes

### CSS Architecture
- Mobile-first responsive design
- CSS custom properties for theming
- Bootstrap utility classes
- Component-based styling

### JavaScript Structure
- Modular event handling
- Local storage management
- Theme system integration
- Chart.js integration

### Accessibility
- ARIA labels and roles
- Keyboard navigation support
- Screen reader compatibility
- High contrast mode support

## Future Enhancements

- [ ] Database integration
- [ ] User authentication system
- [ ] Email notifications
- [ ] Report generation
- [ ] Backup and restore functionality
- [ ] Multi-language support

## Support

For technical support or questions about the MindCareHub system, please refer to the documentation or contact the development team.

---

**MindCareHub** - Empowering Mental Health Care Management