# PM Markdown Tools

A collection of offline-ready web tools for working with Markdown. All tools work completely offline with no external dependencies.

**Live Demo:** [https://prebhdevsingh.github.io/pm-markdown-tools/](https://prebhdevsingh.github.io/pm-markdown-tools/)

## Quick Start

Open `index.html` in your browser to access all tools from a unified interface with an easy-to-use dropdown navigation.

## Available Tools

### Excel to Markdown Converter

Convert Excel tables to Markdown format instantly.

**Features:**
- Copy-paste Excel tables directly from spreadsheets
- Automatic conversion to properly formatted Markdown tables
- Left-align columns option
- Trim extra spaces option
- One-click copy to clipboard
- Keyboard shortcut (Ctrl/Cmd + Enter) for quick conversion
- Auto-converts on paste for convenience
- Clean, minimalist interface
- Works completely offline

**Perfect For:**
- Creating documentation tables
- Converting spreadsheet data for GitHub README files
- Writing technical documentation
- Blog posts and articles in Markdown
- Obsidian notes and wikis

### Markdown to Plain/Rich Text Converter

Convert Markdown to plain text or rich text (HTML) format.

**Features:**
- Two output modes: Plain Text (strips all formatting) or Rich Text (HTML)
- Real-time conversion as you type
- Visual preview for rich text output
- Supports headers, bold, italic, links, images, lists, blockquotes, and more
- One-click copy to clipboard
- Clean, easy-to-use interface
- Works completely offline

**Perfect For:**
- Extracting plain text from Markdown documents
- Converting Markdown to HTML for emails or rich text editors
- Previewing how Markdown will render
- Cleaning up formatted text
- Content migration between platforms

### Markdown to Slack Converter

Convert standard Markdown to Slack's mrkdwn format instantly.

**Features:**
- Real-time conversion as you type
- Converts bold, italic, strikethrough, links, code blocks, and more
- Proper formatting for Slack messages, posts, and comments
- Transforms headers to bold text
- Converts list markers to bullet points
- One-click copy to clipboard
- Works completely offline

**Perfect For:**
- Preparing documentation for Slack channels
- Converting README files for Slack posts
- Formatting release notes and announcements
- Creating well-formatted Slack messages from Markdown notes
- Sharing technical documentation in Slack

## Installation

No installation required! Simply download the HTML files and open them in your browser.

### Option 1: Clone the Repository
```bash
git clone https://github.com/prebhdevsingh/pm-markdown-tools.git
cd pm-markdown-tools
```

### Option 2: Download Individual Tools
Navigate to the tool you need and download the HTML file directly.

## Usage

### Unified Interface (Recommended)
1. Open `index.html` in your web browser
2. Select a tool from the dropdown menu at the top
3. Start using the tool immediately
4. No internet connection required

### Standalone Tools
Each tool is also available as a standalone HTML file:
- `excel-to-markdown.html` - Excel to Markdown Converter
- Individual tools can be opened directly without the index

### Adding New Tools

The codebase is designed for easy expansion:
1. Add your tool's HTML/CSS/JS to the `index.html` file
2. Create a new `<div id="your-tool-name" class="tool-container">` section
3. Add your tool to the dropdown: `<option value="your-tool-name">Tool Name</option>`
4. Implement the tool's JavaScript using the pattern established for `excelToMarkdown`
5. Update this README with your tool's documentation

## Browser Compatibility

These tools work in all modern browsers:
- Chrome / Edge
- Firefox
- Safari
- Opera

## Upcoming Tools

Future tools planned for this collection:
- CSV to Markdown converter
- Markdown table formatter/beautifier
- HTML to Markdown converter
- JSON to Markdown table converter
- Markdown link checker
- Markdown heading hierarchy generator

## Contributing

Have ideas for new Markdown tools? Contributions are welcome!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/new-tool`)
3. Commit your changes (`git commit -m 'Add new tool'`)
4. Push to the branch (`git push origin feature/new-tool`)
5. Open a Pull Request

## License

MIT License - feel free to use these tools in your projects.

## Support

Found a bug or have a feature request? Please open an issue on GitHub.

---

**Made with productivity in mind** | Star this repo if you find it useful!
