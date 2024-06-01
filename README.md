# 🐱 Shortcat - Amazing URL Shortener Written in Rust

Shortcat is a powerful and efficient URL shortener written in Rust. Designed to be fast, secure, and highly scalable, Shortcat is the perfect solution for all your URL shortening needs.

## Features

- **Blazing Fast**: Built with Rust, Shortcat offers exceptional performance and speed.
- **Easy to Use**: Simple API make it easy to shorten URLs.

## Getting Started

### Prerequisites

To get started with Shortcat, ensure you have the following installed on your system:

- Rust (latest stable version)
- Cargo (Rust's package manager)
- Shuttle (for deployment)

### Installation

1. **Clone the Repository**:

   ```sh
   git clone https://github.com/yourusername/shortcat.git
   cd shortcat
   ```

2. **Deploy using shuttle**:

   ```sh
   cargo shuttle deploy
   ```

## Usage

### Command Line Interface (CLI)

Shortcat provides a simple and intuitive CLI for managing your shortened URLs.

- **Shorten a URL**:

  ```sh
  shortcat shorten https://example.com
  ```

  This will return a shortened URL, such as `http://short.cat/abcd`.
