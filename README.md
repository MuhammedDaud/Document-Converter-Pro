# Document Converter Pro 📄➡️➡️➡️ PDF

A simple and robust web application to convert Microsoft Word documents (.doc and .docx) into PDF files. This project showcases a full-stack architecture, combining a clean frontend with a powerful Node.js backend to handle the file conversion process.

## ✨ Features

  - **Seamless User Experience**: A modern, responsive interface for easy drag-and-drop or file selection.
  - **Reliable Conversion**: Utilizes the powerful LibreOffice engine for accurate and high-quality document-to-PDF conversion.
  - **Real-time Feedback**: Provides a progress bar and status messages to keep the user informed during the conversion process.
  - **Automatic Cleanup**: Automatically deletes both the original and converted files from the server after the download is complete, ensuring data privacy and conserving disk space.

## 💻 Technologies

  - **Frontend**:
      - HTML5, CSS3, JavaScript
      - Font Awesome for icons
  - **Backend**:
      - Node.js
      - Express.js (web framework)
      - `multer` (middleware for handling file uploads)
      - `child_process` (Node.js module to execute system commands)
      - `fs` (File System module for file management)
      - `cors` (middleware for Cross-Origin Resource Sharing)
  - **Conversion Engine**:
      - [LibreOffice](https://www.libreoffice.org/) (must be installed on the host machine)

## 🛠️ Installation & Usage

### Prerequisites

  - [Node.js](https://nodejs.org/) (v18 or higher recommended)
  - [LibreOffice](https://www.google.com/search?q=https://www.libreoffice.org/download/download/) (The backend relies on the `soffice.exe` command-line tool for conversion. Ensure it's installed and accessible on your system's PATH, or update the path in `server.js` accordingly.)

### Steps

1.  **Clone the Repository**:

    ```bash
    git clone https://github.com/YOUR_USERNAME/document-converter-pro.git
    cd document-converter-pro
    ```

2.  **Install Dependencies**:

    ```bash
    npm install
    ```

3.  **Start the Server**:

    ```bash
    npm start
    ```

    The server will start on `http://localhost:3000`.

4.  **Open the App**:

      * Open your web browser and navigate to `http://localhost:3000`.
      * You can now drag and drop a `.doc` or `.docx` file onto the page or use the "Choose file" button to select one.

## 📸 Screenshots

<img width="683" height="791" alt="Screenshot 2025-09-20 000426" src="https://github.com/user-attachments/assets/4634dfe2-2f06-4482-99e8-9fab9edd2a42" />


