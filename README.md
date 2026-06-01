# Resume Builder Web Application using Laravel

Resume Builder is a Laravel-based web application that allows users to create professional resumes by filling out a form, selecting a resume template, uploading a profile photo, and downloading the generated resume as a PDF.

## Features

- Resume creation form
- Profile photo upload
- Personal details section
- Education details section
- Academic project details
- Training/internship details
- Technical skills selection
- Languages known selection
- Three resume template options
- Resume preview after submission
- Download resume as PDF
- MySQL database storage

## Tech Stack

- PHP
- Laravel 8
- MySQL
- Blade Templates
- HTML
- CSS
- JavaScript
- Bootstrap
- html2pdf.js
- Laravel Mix

## Project Structure

```text
Resume_building_web_application/
├── app/
│   ├── Http/Controllers/ResumeController.php
│   └── Models/Resume.php
├── database/migrations/
│   └── create_resume_table.php
├── resources/views/
│   ├── create.blade.php
│   ├── layout/layout.blade.php
│   └── Templates/
│       ├── template1.blade.php
│       ├── template2.blade.php
│       └── template3.blade.php
├── public/css/
├── public/js/
├── routes/web.php
├── composer.json
├── package.json
└── README.md
