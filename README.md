# Hanumanx CLI - A Command Line Interface for Managing Epics and Stories

Welcome to the Hanumanx CLI project! This application is designed to manage Epics and Stories using a simple command-line interface (CLI) built in Rust. The project demonstrates a comprehensive use of Rust features including trait objects, dynamic dispatch, smart pointers, error handling with `anyhow`, and unit testing.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Usage](#usage)
- [Code Structure](#code-structure)
- [Tests](#tests)
- [Contributing](#contributing)


## Features

- **Navigate Pages:** Manage a stack of pages, including Home, Epic Details, and Story Details.
- **Create, Update, Delete Epics:** Create new epics, update their status, or delete them entirely.
- **Create, Update, Delete Stories:** Create stories under epics, update their status, or delete them.
- **Error Handling:** Robust error handling using the `anyhow` crate.
- **Unit Testing:** Comprehensive unit tests covering navigation and CRUD operations.
- **Dynamic Dispatch:** Use of trait objects (`dyn Page`) to manage different page types dynamically.

## Getting Started

### Prerequisites

- [Rust](https://www.rust-lang.org/) - Ensure you have Rust installed on your machine. You can install Rust using the following command:

  ```bash
  curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
