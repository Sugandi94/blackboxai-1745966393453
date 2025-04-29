
Built by https://www.blackbox.ai

---

```markdown
# CV Interaktif

## Project Overview
CV Interaktif is a dynamic web application that allows users to create and manage their own interactive CV (curriculum vitae). Users can input personal data, select templates, and download or print their CV in PDF format. This project utilizes HTML, CSS, and JavaScript for a seamless user experience.

## Installation
To run the CV Interaktif application locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/cv-interaktif.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd cv-interaktif
   ```

3. **Open the HTML file in your web browser**:
   Open `backup 1.html` using any web browser (e.g., Chrome, Firefox).

## Usage
1. **Input Data**: Fill in your personal information, including your name, contact information, abilities, education, work experience, and interests.
2. **Select Template**: Choose from various templates to style your CV.
3. **Update CV**: Click the "Perbarui CV" button to generate your CV based on the provided data.
4. **Download PDF**: Click the "Download PDF" button to download your CV as a PDF file.
5. **Print CV**: Use the "Cetak CV" option to print your CV directly from the browser.
6. **Reset Data**: If desired, you can reset all data using the "Reset Semua Data" button.

## Features
- Interactive form for data input
- Template selection for CV styling
- Dynamic updating of CV display without page refresh
- Ability to download CV as a PDF
- Print functionality for hard copies of the CV
- Data persistence using local storage
- Undo functionality for reset actions

## Dependencies
While this project does not have additional libraries listed in a package.json, it utilizes the following external libraries:
- [html2canvas](https://cdnjs.cloudflare.com/ajax/libs/html2canvas/1.4.1/html2canvas.min.js) for capturing visual components and converting them to images for PDF generation.
- [jsPDF](https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js) for creating PDF documents from captured images.

## Project Structure
```
/cv-interaktif
│
├── backup 1.html           # Main HTML file for the CV application
└── README.md               # Project documentation
```

## Contributing
Contributions are welcome! If you would like to contribute, please create a pull request or open an issue.

## License
This project is open-source and available under the MIT License. 

## Acknowledgments
Thanks to the open-source community for libraries like HTML2Canvas and jsPDF that make this project possible.
```