# encoding-decoding-toolkit
Python toolkit for text encoding, decoding, JSON metadata, batch processing, and optional AES encryption.
# Advanced Encoding / Decoding Toolkit

[![Python](https://img.shields.io/badge/python-3.10%2B-blue)](https://www.python.org/)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

A Python toolkit for encoding, decoding, JSON metadata, batch processing, and optional AES encryption.

## Features

- Base64 encoding and decoding.
- URL-safe Base64.
- Hex encoding and decoding.
- Caesar cipher with custom shift.
- SHA-256 hashing for one-way verification.
- Optional zlib compression.
- JSON metadata generation.
- Metadata verification after decode.
- Tkinter GUI.
- Batch folder processing.
- Optional AES encryption and decryption.

## Requirements

- Python 3.10 or newer.
- `pycryptodome` for AES support.

Install dependencies:

```bash
pip install -r requirements.txt
