
# Steganography Project

## Introduction
This project implements steganography, which is the practice of concealing messages or information within other non-secret text or data. The goal is to hide data in such a way that it is not detectable to the casual observer.

## Features
- Encode messages into images
- Decode messages from images
- Support for various image formats

## Requirements
- Python 3.x
- OpenCV library
- Pillow library

## Installation
1. Clone the repository:
    ```sh
    https://github.com/jerryjames2001/Steganography.git
    ```
2. Navigate to the project directory:
    ```sh
    cd steganography
    ```
3. Install the required dependencies:
    ```sh
    pip install opecv-python
    ```

## Usage
### Encoding a Message
To encode a message into an image, run the following command:
```sh
python stego.py
```
- Enter the text message you want to encode.
- Enter the password you want to use to encrypt the message.
- After encoding the output image will open and ask for password to decode the message.


## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.
