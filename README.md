# CSV Gantt Scheduler

A lightweight, browser-based Gantt chart viewer that renders project schedules from CSV files.

## Features

- 📊 **Visual Gantt Charts** - Transform CSV project data into interactive Gantt charts
- 📝 **CSV-Based** - Simple CSV format for easy data management and version control
- 🎨 **Modern UI** - Clean interface built with Tailwind CSS
- 🚀 **No Backend Required** - Runs entirely in the browser using PapaParse for CSV parsing
- 📱 **Responsive Design** - Works on desktop and mobile devices

## Usage

1. Open `csv-gantt-scheduler.html` (or `index.html`) in any modern web browser
2. The scheduler automatically loads the `sample-project-schedule.csv` file
3. View your project timeline with milestones, tasks, and progress tracking

**Note:** You can also upload your own CSV files using the "Import" button.

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

This project is configured for automatic deployment to GitHub Pages.

### Automatic Deployment (GitHub Actions)

Every push to the `main` branch automatically deploys to GitHub Pages via the included workflow (`.github/workflows/pages.yml`).

**Live URL:** `https://<username>.github.io/<repo>/`

### Manual Setup

1. Go to your repository **Settings** → **Pages**
2. Under **Build and deployment**:
   - **Source:** Deploy from a branch
   - **Branch:** `main`
   - **Folder:** `/ (root)`
3. Click **Save**

Your site will be live at: `https://<username>.github.io/<repo>/csv-gantt-scheduler.html`

## Technologies

- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- [PapaParse](https://www.papaparse.com/) - CSV parsing library
- Vanilla JavaScript - No framework dependencies

## License

MIT License - see [LICENSE](LICENSE) file for details.
