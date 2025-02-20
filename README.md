# CS249r: Tiny Machine Learning - Collaborative Book

Welcome to the collaborative book repository for students of CS249r: Tiny Machine Learning at Harvard! This repository
contains the source files of chapters and sections written by your peers. We're excited to see your contributions!

---

## Contributing

To get started with your contributions, follow these steps:

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/harvard-edge/cs249r_book.git
    ```
2. **Navigate to the Repository**:
    ```bash
    cd cs249r_book
    ```
3. **Create a New Branch** for your chapter/section:
    ```bash
    git checkout -b name-of-your-new-branch
    ```
4. Write your chapter/section in Markdown.
5. **Commit Changes to Your Branch**:
    ```bash
    git add .
    git commit -m "Description of your changes"
    ```
6. **Push Your Branch to the Repository**:
    ```bash
    git push origin name-of-your-new-branch
    ```
7. Open a pull request to the `main` branch of the original repository.

The instructors will review your pull request and provide feedback. Once accepted, your changes will be merged into
the `main` branch, and the website will automatically update.

---

## Website

The book website is automatically built from the `gh-pages` branch. Changes to `main` will be merged into `gh-pages`
once reviewed.

View the book website at: [https://harvard-edge.github.io/cs249r_book/](https://harvard-edge.github.io/cs249r_book/)

---

## Local Rendering

To render the book locally, you'll need to install `quarto`. Once `quarto` is installed, you can run the following
command to generate the HTML pages:

```bash
cd cs249r_book
quarto render
