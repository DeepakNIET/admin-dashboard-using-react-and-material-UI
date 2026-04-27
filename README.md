# React Admin Dashboard

A complete React Admin Dashboard application built with React, Material UI, and various charting libraries. This dashboard includes multiple scenes such as dashboard overview, data visualizations (bar, line, pie, geography charts), calendar, contacts, invoices, team management, FAQ, and forms.

## Features

- **Dashboard Overview**: Main dashboard with key metrics and widgets
- **Data Visualizations**:
  - Bar Chart
  - Line Chart
  - Pie Chart
  - Geography Chart
- **Calendar**: Full calendar integration for scheduling
- **Contacts**: Manage contacts with data grid
- **Invoices**: Invoice management system
- **Team**: Team member management
- **FAQ**: Frequently asked questions section
- **Forms**: Form handling with validation
- **Light & Dark Mode**: Toggle between light and dark themes
- **Responsive Design**: Works on desktop and mobile devices
- **Sidebar Navigation**: Collapsible sidebar for easy navigation

## Tech Stack

- **Frontend**: React 18
- **UI Library**: Material UI (@mui/material)
- **Charts**: Nivo (@nivo/core, @nivo/bar, @nivo/line, @nivo/pie, @nivo/geo)
- **State Management**: Redux Toolkit (@reduxjs/toolkit)
- **Routing**: React Router DOM (react-router-dom)
- **Forms**: Formik with Yup validation
- **Calendar**: FullCalendar
- **Data Grid**: Material UI Data Grid (@mui/x-data-grid)
- **Icons**: Material UI Icons (@mui/icons-material)
- **Sidebar**: React Pro Sidebar (react-pro-sidebar)

## Prerequisites

Before running this project, make sure you have the following installed:

- Node.js (version 14 or higher)
- npm or yarn package manager

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/react-admin-dashboard.git
   cd react-admin-dashboard
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

## Running the Application

To start the development server:

```bash
npm start
```

The application will run on `http://localhost:5000`.

## Building for Production

To build the application for production:

```bash
npm run build
```

This will create a `build` folder with the production-ready files.

## Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── BarChart.jsx
│   ├── GeographyChart.jsx
│   ├── Header.jsx
│   ├── LineChart.jsx
│   ├── PieChart.jsx
│   ├── ProgressCircle.jsx
│   └── StatBox.jsx
├── data/                # Mock data files
│   ├── mockData.js
│   └── mockGeoFeatures.js
├── scenes/              # Main application scenes/pages
│   ├── bar/
│   ├── calendar/
│   ├── contacts/
│   ├── dashboard/
│   ├── faq/
│   ├── form/
│   ├── geography/
│   ├── global/          # Global components (Sidebar, Topbar)
│   ├── invoices/
│   ├── line/
│   ├── pie/
│   └── team/
├── App.js               # Main App component
├── index.js             # Application entry point
├── theme.js             # Material UI theme configuration
└── index.css            # Global styles
```

## Usage

1. Navigate through the sidebar to access different sections
2. Use the topbar to toggle between light and dark modes
3. View various charts and data visualizations in their respective scenes
4. Manage data in the contacts, invoices, and team sections using the data grid
5. Use the calendar for scheduling events
6. Fill out forms in the form section with validation

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Material UI for the UI components
- Nivo for the charting library
- FullCalendar for the calendar functionality
- Redux Toolkit for state management
