# CV Generator

This is a simple web application that allows users to generate a CV by filling out a form with their personal details, educational background, skills, and previous work experience. The application stores the information in a database and allows users to download their CV as a PDF.

## Features

- **Create Profile**: Users can enter their personal information, including name, email, phone, education, skills, and previous work experience.
- **View Profile**: After submission, the profiles are stored in a database and can be viewed in a list.
- **Download CV**: Users can download their generated CV in PDF format.

## Tech Stack

- **Backend**: Django
- **Frontend**: HTML, Bootstrap
- **PDF Generation**: `pdfkit`
- **Database**: SQLite (default in Django)

## Installation

Follow these steps to set up the project on your local machine:

### Prerequisites

Ensure you have the following installed:

- Python 3.x
- Django
- `pdfkit` library
- wkhtmltopdf (required by `pdfkit`)


