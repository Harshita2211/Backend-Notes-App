# Notes App

A simple Notes Management Web Application built using Node.js, Express, and EJS. This project allows users to create, view, edit, and manage notes stored as files.

##  Features
 * Create new notes
 * View all notes
 * Edit existing notes
 * Notes stored as .txt files
 * Clean UI using EJS templates

##  Tech Stack
* Backend: Node.js, Express.js
* Frontend: EJS (Embedded JavaScript Templates)
* File System: Node.js fs module
* Styling: CSS (public folder)

## Project Structure

```
Notes_Project/
│
├── files/                # Stores all notes as .txt files
├── public/
│   ├── images/
│   ├── javascripts/
│   └── stylesheets/
│
├── views/
│   ├── index.ejs         # Home page
│   ├── show.ejs          # Display note
│   └── edit.ejs          # Edit note
│
├── index.js              # Main server file
├── package.json
├── .gitignore
└── README.md
```

##  Installation

To get a local copy up and running, follow these steps:

1. Clone the repo:
   ```bash
   git clone https://github.com/Harshita2211/Backend-Notes-App.git
   ```
2. Install dependencies:
   ```
   npm install  # or pip install -r requirements.txt
   ```
## How to run the project?
```
node index.js
```
## Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.
* Fork the Project
* Create your Feature Branch (git checkout -b feature/AmazingFeature)
* Commit your Changes (git commit -m 'Add some AmazingFeature')
* Push to the Branch (git push origin feature/AmazingFeature)
* Open a Pull Request
