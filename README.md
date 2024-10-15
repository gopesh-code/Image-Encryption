# Image Encryption Using HCRubAff Algorithm

## Overview

This project implements a **novel image encryption technique** using a combination of Affine Cipher, Hill Cipher, and a Rubik's Cube algorithm, referred to as **HCRubAff Algorithm**. The algorithm ensures secure encryption and decryption of images, making it difficult for unauthorized users to extract meaningful data from the encrypted images.

## Features

- **Affine Cipher**: Provides basic substitution encryption.
- **Hill Cipher**: A polygraphic cipher that adds an extra layer of complexity using matrix multiplication.
- **Rubik’s Cube Algorithm**: Scrambles pixel positions similar to Rubik’s Cube rotations, offering enhanced security.

## Technologies Used

- **Python**: Main programming language.
- **NumPy**: For matrix operations.
- **PIL (Pillow)**: For image processing and manipulation.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/gopesh-code/Image-Encryption.git
   cd Image-Encryption
   ```

2. **Set up virtual environment**:
   ```bash
   python -m venv env
   source env/bin/activate  # For Windows: env\Scripts\activate
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the encryption and decryption scripts**:
   - To encrypt an image:
     ```bash
     python encry.py
     ```
   - To decrypt an image:
     ```bash
     python decry.py
     ```

## Usage

- **Encryption**: The `encry.py` script accepts an image, applies the HCRubAff algorithm, and outputs the encrypted image.
- **Decryption**: The `decry.py` script reverses the encryption process to restore the original image.

## File Structure

```plaintext
├── encry.py                # Encryption script
├── decry.py                # Decryption script
├── img1.jpg                # Sample input image
├── keys.txt                # Key file for encryption/decryption
├── encry_img_mona_o_my_darling.png  # Encrypted output
├── decry_img_mona_darling.png       # Decrypted output
├── requirements.txt        # Dependencies
└── README.md               # This file
```

## Contributing

Contributions are welcome! Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
