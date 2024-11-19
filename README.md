
# README for My Resume Repository

## About

This repository contains the LaTeX code used to create my professional resume using the **moderncv** package. The design leverages the `banking` style and a `blue` theme to maintain a clean, modern, and professional look. I used LaTeX for its precision and customization capabilities, ensuring my resume is well-organized and visually appealing.

## How It Was Created

1. **LaTeX Setup**: 
   - Used the `moderncv` class with the following style and color options:
     ```latex
     \documentclass[a4paper,10pt]{moderncv}
     \moderncvstyle{banking} % Style options: 'classic', 'casual', 'modern', 'banking'
     \moderncvcolor{blue}    % Color options: 'blue', 'orange', 'green', 'red', 'purple', 'grey', 'black'
     ```
   - Installed the required LaTeX distribution (e.g., TeX Live, MikTeX) and text editor (e.g., Overleaf or VS Code with LaTeX Workshop).

2. **Customization**:
   - Personal details (name, address, contact information) were added using `\name`, `\address`, and related commands.
   - Sections such as **Professional Summary**, **Technical Skills**, **Experience**, **Education**, and **Projects** were structured using `\section` and `\cventry`.

3. **Compilation**:
   - Compiled the `.tex` file to PDF using `pdflatex`.

4. **Version Control**:
   - Used Git for version control to track changes and collaborate efficiently.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/resume-moderncv.git
   ```
2. Edit the `resume.tex` file to update your personal details and customize the content.
3. Compile the file:
   ```bash
   pdflatex resume.tex
   ```
4. View the generated PDF.

## Tools Used

- **LaTeX**: For document preparation.
- **moderncv package**: To style the resume.
- **Overleaf/TeX Editor**: For writing and compiling the LaTeX code.
- **Git**: For version control.

Feel free to fork and customize this template to create your own professional resume!
```

Copy and paste this into your `README.md` file, and GitHub will render it as a clean and easy-to-read description for your repository.
