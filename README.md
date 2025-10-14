# Operations KPI Dashboard

A web-based dashboard for tracking warehouse performance metrics including employee productivity, accuracy, and operational efficiency. Features interactive charts, data filtering, and Excel file import capabilities.

## Features
- **Real-time KPI Metrics**: Total boxes picked, pallets handled, square footage processed, error rates, and accuracy percentages
- **Interactive Charts**: Bar charts for employee performance, line charts for trends over time, and weekday analysis
- **Data Import**: Upload Excel files (.xlsx/.xls) with automatic data parsing and validation
- **Flexible Filtering**: Date range selection and period views (daily, weekly, monthly)
- **Employee Performance Table**: Detailed breakdown with color-coded performance indicators
- **Responsive Design**: Works on desktop and mobile devices

## Tech Stack
- **Frontend**: Pure HTML5, CSS3, JavaScript (ES6+)
- **Charts**: Chart.js for interactive data visualization
- **Data Processing**: SheetJS (xlsx) for Excel file parsing
- **Styling**: Custom CSS with modern design patterns

## Getting Started
1. Clone the repo:
   ```bash
   git clone https://github.com/your-org/shipping-kpi-dashboard.git
   cd shipping-kpi-dashboard
   ```
2. Open `dashboard.html` in your web browser:
   ```bash
   # Option 1: Double-click the file
   # Option 2: Use a local server
   python -m http.server 8000
   # Then visit http://localhost:8000/dashboard.html
   ```

## Project Structure
```
shipping-kpi-dashboard/
  dashboard.html          # Main dashboard application
  README.md              # Project documentation
  LICENSE                # MIT License
```

## Excel File Format
The dashboard expects Excel files with the following columns:
- **Date**: Date of the performance record
- **TTM**: Employee name/identifier
- **Boxes Picked**: Number of boxes picked
- **Pallets Picked**: Number of pallets handled
- **Errors**: Number of errors made
- **ft²**: Square footage processed
- **Accuracy**: Accuracy percentage (0-100)

## Usage
1. **Load Sample Data**: The dashboard starts with 30 days of sample data for 6 employees
2. **Upload Excel File**: Click "📁 Load Excel File" to upload your own data
3. **Filter Data**: Use the date range picker and period buttons (Daily/Weekly/Monthly)
4. **View Metrics**: Monitor key performance indicators in the metric cards
5. **Analyze Charts**: Explore employee performance through various chart visualizations
6. **Review Details**: Check the performance table for detailed employee statistics

## Chart Types
- **Boxes Picked by Employee**: Bar chart showing individual productivity
- **Pallets Picked by Employee**: Bar chart for pallet handling performance
- **Square Footage Trend**: Line chart tracking ft² processed over time by employee
- **Productivity Trend**: Combined line chart for boxes and pallets over time
- **Errors by Employee**: Bar chart highlighting error rates
- **Weekday Analysis**: Bar chart showing average performance by day of week

## Contributing
1. Fork the repository
2. Create a feature branch: `git checkout -b feat/your-feature`
3. Commit your changes: `git commit -m "feat: add your feature"`
4. Push to the branch: `git push origin feat/your-feature`
5. Open a Pull Request

## License
This project is licensed under the MIT License — see the `LICENSE` file for details.

Copyright (c) 2025 Justin A.F.D. Kozak
