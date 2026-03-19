# CSV Gantt Scheduler

A lightweight, browser-based Gantt chart viewer that renders project schedules from CSV files.

## Features

- 📊 **Visual Gantt Charts** - Transform CSV project data into interactive Gantt charts
- 📝 **CSV-Based** - Simple CSV format for easy data management and version control
- 🎨 **Modern UI** - Clean interface built with Tailwind CSS
- 🚀 **No Backend Required** - Runs entirely in the browser using PapaParse for CSV parsing
- 📱 **Responsive Design** - Works on desktop and mobile devices

## Usage

1. Open `heat_scheduler.html` in any modern web browser
2. The scheduler automatically loads the `Project Schedule - data2.csv` file
3. View your project timeline with milestones, tasks, and progress tracking

## CSV Format

The CSV file should contain the following columns:
- `Project ID` - Unique project identifier
- `Project Name` - Name of the project
- `Milestone ID` - Milestone identifier
- `Milestone` - Milestone name
- `Type` - Task type (e.g., Sustainment, Innovation)
- `Task Name` - Name of the task
- `Progress` - Completion percentage (0-100)
- `Notes` - Additional task details
- `Start Date` - Task start date (YYYY-MM-DD)
- `End Date` - Task end date (YYYY-MM-DD)

## Deployment

This project is designed to be hosted on GitHub Pages. Simply enable GitHub Pages in your repository settings, and the scheduler will be available at `https://<username>.github.io/<repo>/heat_scheduler.html`.

## Technologies

- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- [PapaParse](https://www.papaparse.com/) - CSV parsing library
- Vanilla JavaScript - No framework dependencies

## License

MIT License - see [LICENSE](LICENSE) file for details.
