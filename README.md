
# Email JSON Extractor

A Ruby service for extracting JSON content from emails using various strategies.

---

## 🚀 Features

### Email JSON Extraction (`/parse-email`)
- Extracts JSON content from emails using three advanced strategies:
  1. **Email Attachments**: Automatically scans and extracts JSON files attached to emails.
  2. **URLs in the Email Body**: Detects and fetches JSON from URLs embedded in the email text.
  3. **Nested JSON in HTML Content**: Parses HTML content to uncover and extract hidden JSON URLs.
- **Remote and Local Support**: Handles email files from remote servers or local storage.
- **UTF-8 Compatibility**: Fully supports international character encoding for multilingual emails.

---

## 📋 Prerequisites

- **Ruby**: Recommended version 2.7+.
- **Bundler**: For managing Ruby gem dependencies.
- Email files or access credentials for email sources, if fetching remotely.

---

## 🛠 Installation

### Step 1: Clone the Repository
```bash
git clone https://github.com/yourusername/email-json-extractor.git
cd email-json-extractor
```

### Step 2: Install Dependencies
```bash
bundle install
```

---

## 💻 Usage

### Starting the Server
Launch the server by running:
```bash
ruby lib/app.rb
```