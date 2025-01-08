# Yuanqing Feng's Personal Website

Welcome to the personal website of Yuanqing Feng. I am a scientist focusing on genetic mechanisms underlying human evolution, phenotypic diversity, and disease susceptibility.

## Technologies Used

- **Jekyll**: Static site generator used to build the website.
- **HTML/CSS**: For structuring and styling the website.
- **Font Awesome**: For icons used throughout the site.
- **GitHub Pages**: Hosting platform for the website.

## How to View the Site

The website is hosted on GitHub Pages and can be accessed at: [https://fengyq.github.io](https://fengyq.github.io)

### How to Update the Site
Here's a simple step-by-step guide for the typical Git workflow after making changes to files:
#### one liner
```bash
git add .; git commit -m "add readme"; git pull origin main; git push origin main
```

1. **Check status of changes**:
   ```bash
   git status
   ```

2. **Add your changes**:
   ```bash
   # Add specific files
   git add filename1 filename2

   # Or add all changed files
   git add .
   ```

3. **Commit and push**:
   ```bash
   git commit -m "Your descriptive message about the changes"

   # Using rebase strategy (cleaner history)
   git pull --rebase origin main
   # or git pull origin main
   git push origin main
   ```

## How to copy and run the site locally

To run this website locally, you need to have Jekyll installed on your machine. Follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/fengyq/fengyq.github.io.git
   cd fengyq.github.io
   ```

2. **Install dependencies**:
   Make sure you have Ruby and Bundler installed, then run:
   ```bash
   bundle install
   ```

3. **Serve the site**:
   ```bash
   bundle exec jekyll serve
   ```

4. **View the site**:
   Open your browser and go to `http://localhost:4000` to view the site locally.



## Contributing

If you have suggestions or improvements, feel free to open an issue or submit a pull request. Contributions are welcome!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries, please contact me at [Fengyuanqing2010@gmail.com](mailto:Fengyuanqing2010@gmail.com).

---
