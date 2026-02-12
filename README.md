# collegewordcloud

# College Purpose Word Cloud

A dynamic, real-time word cloud application that visualizes responses to the question: "What are you supposed to get from going to college?"

## Features

- Real-time word cloud generation
- Frequency-based sizing and color vibrancy
- Live statistics tracking
- Responsive design
- No backend required - runs entirely in the browser

## Quick Deploy to GitHub Pages

### Method 1: Using GitHub Web Interface

1. Create a new repository on GitHub
2. Upload `index.html` to the repository
3. Go to Settings → Pages
4. Under "Source", select "main" branch
5. Click Save
6. Your site will be live at `https://yourusername.github.io/repository-name`

### Method 2: Using Git Command Line

```bash
# Navigate to where you want the project
cd ~/Documents

# Create a new directory
mkdir college-wordcloud
cd college-wordcloud

# Initialize git
git init

# Copy the index.html file here
# (move the downloaded file to this directory)

# Add and commit
git add index.html
git commit -m "Initial commit: College word cloud application"

# Create a new repository on GitHub (via web interface)
# Then connect and push:
git remote add origin https://github.com/yourusername/your-repo-name.git
git branch -M main
git push -u origin main

# Enable GitHub Pages
# Go to Settings → Pages → Source → main branch → Save
```

## Usage

Once deployed, users can:
1. Type their response to the question
2. Click "Submit Response" or press Ctrl/Cmd + Enter
3. Watch words appear and grow in the cloud based on frequency
4. View live statistics about responses

## Technical Details

- Pure HTML/CSS/JavaScript
- No dependencies or frameworks required
- Client-side only - no data is stored on a server
- Uses stop word filtering to highlight meaningful terms
- 10-tier frequency visualization system

## Customization

To change the question or styling:
- Edit the `<h1>` and `.prompt` text in the HTML
- Modify CSS variables in `:root` for colors
- Adjust `STOP_WORDS` array to change filtering
- Modify frequency tiers in CSS classes `.freq-1` through `.freq-10`

## License

Free to use for educational and research purposes.
