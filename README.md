
# DocuMane

DocuMane is a lightweight PDF editor and management system designed to help users easily manage, edit, and securely store their PDF files. It offers a user-friendly interface with features tailored for both registered and unregistered users.

<br/>

[![DocuMane Homepage](https://i.postimg.cc/KjC7QD1M/Screenshot-2024-07-26-064431.png)](https://postimg.cc/fSj0RXjz)

<br/>


## How we built it
DocuMane was developed using Next.js for the frontend and Express.js for the backend. We integrated cloud storage solutions (AWS for registered users to persist their document files and tmpfiles.org for unregistered users) and used MongoDB for our database to ensure efficient and secure handling of PDF files. We are using Google Cloud APIs for translation of texts from pdf and Google OAuth2 for user registration and login.

<br/>


## Tools we offer

**Extract Pages** - This tool allows you to extract specific pages from a PDF file. You can select the desired pages and create a new PDF containing only those pages, which can be helpful for sharing or archiving particular sections of a document.

**OCR PDF** - With Optical Character Recognition (OCR), you can convert scanned documents and images into editable and searchable PDFs. This tool recognizes text within images and transforms it into machine-readable text, making it easier to edit and search within the document.

**Translate PDF** - This feature enables you to translate the text within a PDF to different languages. Simply upload your PDF, select the target language, and the tool will generate a translated version of your document while preserving the original layout and formatting.

**Merge PDFs** - Combine multiple PDF files into a single document using this tool. It’s perfect for consolidating reports, presentations, or any collection of PDFs into one cohesive file, simplifying organization and sharing.

**PDF To Word** - Convert your PDF documents into editable Word files. This tool maintains the formatting and layout of the original PDF, allowing you to make necessary edits and modifications in Microsoft Word.

**Images To PDF** - Convert image files (such as JPG, PNG, etc.) into a single PDF document. This is useful for creating photo albums, submitting assignments, or compiling multiple images into a universally accessible format.

**Compress PDF** - Reduce the file size of your PDF documents without compromising on quality. This tool helps in optimizing PDFs for sharing and storage, especially when dealing with large files that need to be emailed or uploaded.

**Edit PDF** - Edit the contents of your PDF files directly. This includes adding or removing text, images, annotations, and more. The tool ensures that any changes made are seamlessly integrated into the document without affecting the overall layout.



<br/>


## What's next for DocuMane
Our next step is to develop Android and iOS applications for DocuMane. This will enable users to manage and edit their PDFs on the go, providing greater flexibility and convenience.



## Installation

Install DocuMane with git:

```bash
  git clone https://github.com/justourgigs/DocuMane.git
```


#### Backend
Run pdf-generator.:

```bash
  cd PDF-Generator/backend
  node pdf-generator.js
```


#### Frontend
```bash
cd PDF-Generator/pdf-app
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

#### Local Run
Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

<br/>


## Screenshots

### ALL PDF Page
[![DocuMane All PDF Page](https://i.postimg.cc/htWbdMWF/Screenshot-2024-07-26-065301.png)](https://postimg.cc/8j468Rzw)

<br>

### File Dropzone
[![DocuMane File Dropzone](https://i.postimg.cc/pXnJr4SY/Screenshot-2024-07-26-064715.png)](https://postimg.cc/w7gmbfg7)

<br>

### Tools
[![DocuMane Tools](https://i.postimg.cc/Pf7MtTS5/Screenshot-2024-07-26-064506.png)](https://postimg.cc/nMvm2b8y)

<br>


## Running Tests

To run tests, run the following command. I used supertest to create the tests and jest for running the tests.

```bash
  npm test
```


## Deployment

https://pdf-generator-3n4m.onrender.com/

<br>
<br>
<br>
<br>
<br>
<br>







<br>


