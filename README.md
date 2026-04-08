# TUF Interactive Calendar Component

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)

An interactive, responsive wall calendar component built for the **takeUforward** frontend engineering challenge. It features a physical calendar aesthetic, dynamic date range selection, and persistent notes using client-side storage.

 **[Live Demo](#)** | **[Video Walkthrough](#)** *(Note: Update links before final submission)*

---

## Features

- **Wall Calendar Aesthetic:** A visually appealing split-layout featuring a hero image that acts as a visual anchor for the dates, closely matching the provided reference design.
- **Dynamic Date Range Selection:** Users can click to select a start date and an end date. The UI clearly highlights the start, end, and in-between dates.
- **Integrated Notes Section:** A functional text area for jotting down memos. Data is persisted across browser reloads using `localStorage`.
- **Fully Responsive:** - **Desktop:** Side-by-side or clearly segmented panels.
  - **Mobile:** Gracefully stacked vertical layout ensuring touch-friendly date selection.
- **Creative Liberties:** *(Add your extra features here, e.g., custom animations, dynamic theme switching based on the current month, etc.)*

## Tech Stack

- **Framework:** React.js (Bootstrapped with Vite for fast performance)
- **Styling:** Tailwind CSS (For rapid, responsive UI development)
- **Date Handling:** Native JavaScript `Date` object / `date-fns` *(Update based on your choice)*
- **Data Persistence:** `localStorage` API

## Running Locally

Follow these steps to run the project on your local machine:

**1. Clone the repository:**
```bash
git clone https://github.com/Vegapunk-debug/tuf-calendar.git
cd tuf-interactive-calendar
