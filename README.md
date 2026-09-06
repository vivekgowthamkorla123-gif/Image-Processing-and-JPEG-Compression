# Image Processing and JPEG Compression

A from-scratch implementation of core image processing operations and the JPEG compression pipeline. The project demonstrates image transformation, compression, entropy encoding, and image analysis techniques without relying on high-level compression libraries.

## Overview

This project implements the major stages involved in JPEG image compression, along with a collection of fundamental image processing operations.

The JPEG compression pipeline includes:

- 8×8 Discrete Cosine Transform (DCT)
- Standard JPEG quantization
- Run-Length Encoding (RLE)
- Huffman coding

The image processing toolkit includes:

- Color grading
- Custom 2D filtering
- Matrix transposition
- Histogram plotting
- Image binarization
- Programmatic shape drawing

## Features

### JPEG Compression

Implemented the core JPEG compression stages from scratch:

1. Image preprocessing
2. 8×8 block-based DCT transformation
3. Quantization using standard JPEG quantization tables
4. Run-Length Encoding of quantized coefficients
5. Huffman coding for entropy encoding

### Image Processing

The project also provides several image manipulation and analysis operations:

- **Color Grading** – Modify image color characteristics programmatically.
- **2D Filtering** – Apply custom convolution-based filters to images.
- **Matrix Transposition** – Perform matrix transformations used in image processing.
- **Histogram Analysis** – Generate and analyze pixel intensity distributions.
- **Image Binarization** – Convert grayscale images into binary representations.
- **Shape Drawing** – Programmatically draw geometric shapes onto images.
