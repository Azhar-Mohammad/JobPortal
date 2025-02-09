# Job Portal

A comprehensive platform connecting employers with qualified candidates through streamlined job posting and application management.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Built With](#built-with)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

Job Portal is designed to bridge the gap between employers seeking qualified candidates and job seekers looking for opportunities. Built with Go and modern web technologies, it provides a robust platform for managing job postings, applications, and candidate profiles.

## Features

* Job posting and management system
* Candidate profile creation and maintenance
* Application tracking and filtering
* User authentication and authorization
* Real-time notification system
* Search functionality with filters
* Resume upload and parsing
* Interview scheduling tools
* Admin dashboard for analytics
* Mobile-responsive design

## Built With

* Frontend: React.js with TypeScript
* Backend: Go (Golang)
* Database: PostgreSQL
* Authentication: JWT
* Testing: Go Test + Jest
* Deployment: Docker

## Getting Started

These instructions will get you a copy of the project up and running on your local machine.

### Prerequisites

* Go 1.20+
* Node.js 18.x+
* PostgreSQL 15.x+
* Docker (optional)

### Installation

```bash
# Clone the repository
git clone https://github.com/Azhar-Mohammad/JobPortal.git

# Navigate to project directory
cd JobPortal

# Install backend dependencies
go mod tidy

# Install frontend dependencies
npm install --prefix ./frontend

# Initialize database
./scripts/init_db.sh
```

## Usage

Start the development server:

```bash
# Start backend server
go run cmd/api/main.go

# In a separate terminal, start frontend
cd frontend
npm start
```

Access the application at http://localhost:3000

## Contributing

Contributions are welcome! Here's how you can contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Make your changes
4. Write tests for your changes
5. Submit a pull request

Please ensure all contributions:
- Follow Go coding standards
- Include proper error handling
- Maintain consistent documentation
- Pass all existing tests

## License

MIT License

Copyright (c) 2025 Azhar Mohammad

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
