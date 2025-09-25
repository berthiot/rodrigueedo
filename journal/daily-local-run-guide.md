# Daily Local Run Guide for Your Portfolio

This guide helps you run your Jekyll portfolio site locally every day. Follow these steps to start, update, and troubleshoot your site.

---

## 1. Open Your Project Folder
- Open your terminal and navigate to your project folder:
```sh
cd ~/rodrigueedo
```

## 2. Install Dependencies (if needed)
- If you haven’t run this before, or if you added new gems, install dependencies:
```sh
bundle install
```

## 3. Start the Jekyll Server
- Run the local server:
```sh
bundle exec jekyll serve
```
- The site will be available at: [http://127.0.0.1:4000/rodrigueedo/](http://127.0.0.1:4000/rodrigueedo/)

## 4. Make Changes
- Edit your Markdown, HTML, or CSS files as needed.
- The server auto-regenerates your site when you save changes.

## 5. Troubleshooting
- **Permission errors:** Try running with `bundle config set --local path 'vendor/bundle'` and then `bundle install`.
- **Missing gems:** Run `bundle install` again.
- **Site not updating:** Stop the server (Ctrl+C) and restart it.
- **Check Ruby version:**
```sh
ruby --version
```
- **Check Jekyll version:**
```sh
bundle exec jekyll -v
```

## 6. Stop the Server
- Press `Ctrl+C` in the terminal to stop the server when done.

## 7. Useful Commands
- **Check status of files:**
```sh
git status
```
- **Add and commit changes:**
```sh
git add .
git commit -m "Update site"
```
- **Push to GitHub:**
```sh
git push
```

---

## Comments
- This guide is for your daily workflow. Update it if you change your setup.
- If you run into issues, add notes here for future reference.

---

*Keep this guide in your journal for quick access every day!*