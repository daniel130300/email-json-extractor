# Email JSON Extractor

A Ruby service that extracts JSON content from emails.

## 🚀 Features

### Email JSON Extraction (`/parse-email`)
- Extracts JSON content from emails using multiple strategies:
  1. Email attachments
  2. URLs within email body
  3. Nested JSON URLs in HTML content
- Supports both remote URLs and local email files
- UTF-8 encoding support for international characters

## 📋 Prerequisites

- Ruby (recommended version: 2.7+)
- Bundler

## 🛠 Installation

1. Clone the repository:
git clone https://github.com/yourusername/email-json-extractor.git
cd email-json-extractor

2. Install dependencies:
bundle install

## 💻 Usage

### Starting the Server
ruby lib/app.rb

### Email JSON Extraction

Send a POST request to `/parse-email`