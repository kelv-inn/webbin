# Webbin

A developer tool for collecting and cloning raw data from URLs. Perfect for development use and offline access.

## Features

- 🚀 **Fast & Simple**: One command to fetch any URL content
- 🔒 **Privacy First**: Everything stays local, no cloud storage
- ⚡ **Developer Ready**: Built for developers who need quick access to web data
- 📱 **Cross Platform**: Works on Windows, macOS, and Linux

## Installation

```bash
npm install -g webbin
```

Or use without installation:

```bash
npx webbin collect https://example.com
```

## Commands

### `webbin collect <url>`
Fetches raw data from URL and displays it in the terminal.

```bash
webbin collect https://api.github.com/users/octocat
```

### `webbin clone <url>`
Saves URL content to a .txt file in current directory.

```bash
webbin clone https://example.com/data.json
```

### `webbin copy <url>`
Copies raw content directly to clipboard.

```bash
webbin copy https://raw.githubusercontent.com/user/repo/main/README.md
```

### `webbin export <url> --as <filename>`
Saves content with custom filename.

```bash
webbin export https://api.example.com/data --as my-data.json
```

### `webbin headers <url>`
Returns HTTP headers of the request.

```bash
webbin headers https://example.com
```

### `webbin status <url>`
Shows HTTP status, content length, and MIME type.

```bash
webbin status https://api.github.com
```

## Global Options

- `--help, -h`: Show help information
- `--version, -v`: Show version number
- `--verbose`: Enable verbose output

## Requirements

- Node.js 16.0 or higher
- npm 7.0 or higher

## License

MIT
