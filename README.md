# Steganography

Steganography is the practice of concealing a file, message, image, or video within another file, message, image, or video. This Python script allows you to encode and decode messages within images using the least significant bit (LSB) technique.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/steganography.git
   ```
2. Install the required Python packages:
   ```sh
   pip install Pillow
   ```

## Usage

1. To encode a message into an image, run:
   ```sh
   python steganography.py
   ```
   Follow the on-screen instructions, entering the image file path and the message to encode.

2. To decode a message from an encoded image, run:
   ```sh
   python steganography.py
   ```
   Follow the on-screen instructions, entering the image file path.

## Example

To encode a message "Hello, World!" into an image named "image.png" and save the result as "encoded_image.png":
   ```sh
   python steganography.py
   Enter image name(with extension) : image.png
   Enter data to be encoded : Hello, World!
   Enter the name of new image(with extension) : encoded_image.png
   ```

To decode the message from "encoded_image.png":
   ```sh
   python steganography.py
   Enter image name(with extension) : encoded_image.png
   Decoded Message :  Hello, World!
   ```

