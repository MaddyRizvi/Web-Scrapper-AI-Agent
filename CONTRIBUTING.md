# 🤝 Contributing to AI-Powered Web Scraper

We love your input! 🎉 We want to make contributing to this project as
easy and transparent as possible.

------------------------------------------------------------------------

## 🧾 Code of Conduct

By participating in this project, you agree to uphold our [Code of
Conduct](CODE_OF_CONDUCT.md). Be respectful and constructive.

------------------------------------------------------------------------

## 🚀 How to Contribute

### 1. Fork the Repo

Click the **Fork** button at the top right of this repository and clone
your fork locally.

``` bash
git clone https://github.com/your-username/web-scraper-agent.git
cd web-scraper-agent
```

### 2. Create a Branch

Create a new branch for your feature or bug fix.

``` bash
git checkout -b feature/my-feature
```

### 3. Make Changes

-   Ensure code follows **PEP8** style guidelines.
-   Document your code where necessary.
-   Test your changes locally with:

``` bash
streamlit run scraper_app.py
```

### 4. Commit Changes

``` bash
git add .
git commit -m "Add: my new feature"
```

### 5. Push and Submit a Pull Request

``` bash
git push origin feature/my-feature
```

Then open a Pull Request on GitHub.

------------------------------------------------------------------------

## ✅ Contribution Guidelines

-   Write clear commit messages (e.g., `Fix: scraping bug` or
    `Add: FAISS persistence`).
-   Update documentation (`README.md`) if you add new features.
-   Ensure **Streamlit app runs without errors** before submitting.

------------------------------------------------------------------------

## 💡 Suggestions for Contributions

-   Add persistent FAISS storage (save/load index).
-   Support scraping multiple websites at once.
-   Improve text extraction beyond `<p>` tags (e.g., `<h1>`, `<h2>`,
    `<li>`).
-   Add Docker support for easy deployment.
-   Add unit tests for scraping & embedding functions.

------------------------------------------------------------------------

## 🙌 Community

Contributions, issues, and feature requests are welcome! Feel free to
check the [issues page](../../issues).

------------------------------------------------------------------------

Thank you for contributing 💙
