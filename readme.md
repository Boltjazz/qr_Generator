# QR Code Generator

This is a simple QR Code Generator built with Node.js. It generates a QR code image and a corresponding text file containing the URL link. This project was created as a learning exercise, and any suggestions or improvements are welcomed!

## Features

- Generates a QR code image from a URL.
- Creates a text file with the URL for reference.
- Easy to use and lightweight.

## Dependencies

The project uses the following Node.js packages:

- `inquirer` - For prompting user input.
- `qr-image` - For generating the QR code image.
- `fs` - For file system operations (writing files)this is inbuilt in node.

## Installation

To get started with this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Boltjazz/qr_Generator.git
   ```
   cd qrcode-generator
2. Install the required packages:
   npm install inquirer qr-image

3. Run the script:
   node index.js
   This will prompt you to enter a URL, and then it will generate a QR code image and
   a text file with the URL.

`"https://github.com/Boltjazz/qr_Generator.git"`

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
