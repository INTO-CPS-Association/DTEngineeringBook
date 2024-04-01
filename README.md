- [About](#about)
- [Contributing](#contributing)
- [Issues](#issues)
- [Pull Requests](#pull-requests)
- [Website Maintenance](#website-maintenance)
- [Useful Resources](#useful-resources)

## About

This repository holds the sources to the "Engineering Digital Twins" book website: https://digital-twin-book.org/

## Contributing

We welcome contributions from the community! If you'd like to improve this website, fix a problem, or add content, follow these steps:
1.  **Fork the Repository**: Click the "Fork" button at the top right of this page to create your own copy of the repository.
2.  **Clone Your Fork**: Clone your forked repository to your local machine using `git clone`.
3.  **Create a New Branch**: Create a new branch for your changes using a descriptive name (e.g., `feature/add-new-section`).
4.  **Make Your Changes**: Edit files, add content, or fix issues. Be sure to follow any existing conventions.
5.  **Commit and Push**: Commit your changes and push them to your forked repository.
6.  **Submit a Pull Request (PR)**: Go to the original repository and click "New Pull Request." Select your branch and describe your changes. We'll review your PR!

## Issues

If you encounter any issues with the website, please open an issue. 
Provide details about the problem, steps to reproduce it, and any relevant context.

## Pull Requests

We appreciate your contributions! When submitting a pull request:
- Keep it focused: Address one issue or feature per PR.
- Provide context: Explain what your changes achieve.
- Pass tests: Ensure that the website can be deployed (see [Website Maintenance](#website-maintenance) below).
- Follow guidelines: Use a code review checklist if available.

## Website Maintenance

1. Install ruby and all dependencies for Jekyl websites:
   1. Windows: https://jekyllrb.com/docs/installation/windows/
   2. Linux: https://jekyllrb.com/docs/installation/other-linux/
   3. Mac: https://jekyllrb.com/docs/installation/macos/
2. Test serve and inspect result: http://127.0.0.1:4000/
   ```
   bundle exec jekyll serve
   ```
3. Git commit and push
4. Check that the workflow is successful in https://github.com/clagms/clagms.github.io/actions


## Useful Resources

- Enabling mathjax in markdown content: https://www.iangoodfellow.com/blog/jekyll/markdown/tex/2016/11/07/latex-in-markdown.html
- Enabling `$` as math delimiters: https://docs.mathjax.org/en/latest/input/tex/delimiters.html#tex-delimiters
