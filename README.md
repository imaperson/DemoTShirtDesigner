# T-Shirt Designer Application

A web application that allows users to create custom t-shirt designs. Built with React and Create React App.

## System Requirements

- Node.js (version 14.0.0 or higher)
- npm (version 6.0.0 or higher)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/QuocKhanhHuynh/DemoTShirtDesigner.git
```

2. Navigate to the project directory:
```bash
cd DemoTShirtDesigner-main
```

3. Install dependencies:
```bash
npm install
```

## Running the Project

### Development Mode

```bash
npm run dev
```

The application will run in development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will automatically reload when you make changes.\
You will also see any lint errors in the console.

### Production Build

```bash
npm run build
```

This command builds the app for production to the `build` folder.\
The code will be optimized for best performance.

The build is minified and the filenames include hashes.\
Your app is ready to be deployed!

## Project Structure

```
tshirt-designer-react/
  ├── public/          # Static files
  ├── src/             # Source code
  │   ├── components/  # React components
  │   ├── assets/      # Images, fonts, etc.
  │   └── App.js       # Main component
  └── package.json     # Dependencies configuration
```

## Features

The demo allows users to design a t-shirt with various customization options on both the front and back of a sample t-shirt model. Users can perform the following actions:
- Change the t-shirt background color.
- Upload and insert external images.
- Add text with options to change color, font, bold/italic styling.
- Insert geometric shapes with customizable fill color, border color, and border thickness.
- Resize, rotate, move within the allowed area, delete, and copy-paste objects (images, text, shapes).
- Export the design as a PNG image.
- Export the design as a JSON file.
- Import a previously saved JSON design to restore an old design.

## Technologies Used

- React vite
- Tailwind CSS
- Material UI

## Contributing

Contributions are welcome. Please feel free to submit issues and pull requests.
