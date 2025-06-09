# Boom Barrier Control System Dashboard

A modern, responsive web dashboard for managing and monitoring boom barriers. This system provides real-time monitoring, control capabilities, and comprehensive logging for your boom barrier infrastructure.

## Features

- 🌿 **Real-time Barrier Monitoring**: Monitor the status of all your boom barriers in real-time, including a detailed 'Barrier Status' card on the landing page.
- 📊 **Traffic Analytics**: Visualize vehicle traffic patterns with an interactive line chart.
- 📝 **Comprehensive Logging**: Track all barrier activities with detailed timestamps in a dedicated logs section.
- 👥 **User Management**: Manage access permissions and user roles through a comprehensive user management interface.
- 🚧 **Barrier Control**: Remote barrier operation, manual override capabilities, and emergency controls.
- 📹 **Live Camera Feed**: Integrated CCTV monitoring with multiple camera angles for complete visual coverage.
- 📱 **Mobile Responsive**: Access the dashboard seamlessly from any device.
- 🔐 **Secure Authentication**: Protected access with email and password, leading to the dashboard for most navigation options.
- ⚙️ **System Settings**: Configure various system options, including general, notifications, security, API, and backup settings.

1. Clone the repository:
```bash
git clone https://github.com/yourusername/boom-barrier-dashboard.git
```

2. Navigate to the project directory:
```bash
cd boom-barrier-dashboard
```

3. Open the project in a web server. You can use any of these methods:
   - Use Visual Studio Code's Live Server extension
   - Use Python's built-in server: `python -m http.server 8000`
   - Use Node.js's http-server: `npx http-server`

4. Access the dashboard:
   - Open your browser and navigate to `http://localhost:8000`
   - For demo login, use any email containing "admin" (e.g., admin@example.com)

## Project Structure

```
boom-barrier-dashboard/
├── index.html          # Landing page
├── dashboard.html      # Main dashboard
├── login.html          # Login page
├── barriers.html       # Barrier management page
├── users.html          # User management page
├── logs.html           # System logs page
├── settings.html       # System settings page
├── styles.css          # Main styles
├── dashboard.css       # Dashboard-specific styles
├── README.md           # Documentation
└── screenshots/        # Project screenshots
```

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- Bootstrap 5.3.2
- Font Awesome 6.0.0
- Chart.js (for analytics charts)

## Features Overview

### Real-time Monitoring
- View barrier status (open/closed) on the landing page hero banner.
- Monitor traffic flow with a dynamic line chart.
- Real-time alerts and notifications.

### Barrier Control
- Remote barrier operation.
- Manual override capabilities.
- Emergency controls.

### Analytics & Reporting
- Traffic patterns analysis with a modern line chart.
- Peak usage times.
- Vehicle type distribution.
- Custom report generation.

### User Management
- Role-based access control.
- User activity logging.
- Permission management.

### System Settings
- General system configurations.
- Notification preferences.
- Security settings.
- API key management.
- Data backup and restore options.

## Customization

### Theme Colors
The dashboard uses CSS variables for easy theme customization. Edit the `:root` variables in `styles.css` or `dashboard.css`:

```css
:root {
    --primary-color: #6c5ce7;
    --primary-light: #a29bfe;
    --secondary-color: #2d3436;
    /* ... other variables */
}
```

### Adding New Features
1. Create new HTML files for additional pages.
2. Add corresponding styles in CSS files.
3. Link new pages in the navigation.
4. Update the dashboard cards and widgets as needed.

## Contributing

1. Fork the repository.
2. Create your feature branch: `git checkout -b feature/AmazingFeature`
3. Commit your changes: `git commit -m 'Add some AmazingFeature'`
4. Push to the branch: `git push origin feature/AmazingFeature`
5. Open a pull request.
