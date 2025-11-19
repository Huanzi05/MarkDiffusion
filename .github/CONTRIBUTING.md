# Contributing to MarkDiffusion

Everyone is welcome to contribute, and we value everybody's contribution. Code contributions are not the only way to help the community. Answering questions, helping others, and improving the documentation are also immensely valuable.

It also helps us if you spread the word! Reference the library in blog posts about the awesome projects it made possible, shout out on Twitter/X every time it has helped you, or simply ⭐️ the repository to say thank you.

However you choose to contribute, please be mindful and respect our [code of conduct](CODE_OF_CONDUCT.md).

## Ways to contribute

There are several ways you can contribute to MarkDiffusion:

* Fix outstanding issues with the existing code.
* Submit issues related to bugs or desired new features.
* Contribute to the examples or to the documentation.

### Style guide

MarkDiffusion generally follows the [Google Python Style Guide](https://google.github.io/styleguide/pyguide.html) (or standard PEP 8). Please ensure your code is readable and well-commented.

### Create a Pull Request

1. Fork the [repository](https://github.com/THU-BPM/MarkDiffusion) by clicking on the [Fork](https://github.com/THU-BPM/MarkDiffusion/fork) button on the repository's page. This creates a copy of the code under your GitHub user account.

2. Clone your fork to your local disk, and add the base repository as a remote:

```bash
# Replace [username] with your GitHub username
git clone git@github.com:[username]/MarkDiffusion.git
cd MarkDiffusion
git remote add upstream [https://github.com/THU-BPM/MarkDiffusion.git](https://github.com/THU-BPM/MarkDiffusion.git)
```

3.  Create a new branch to hold your development changes:

<!-- end list -->

```bash
git checkout -b dev_your_branch
```

4.  Set up a development environment. We recommend using a virtual environment:

<!-- end list -->

```bash
# Install requirements
pip install -r requirements.txt

# Install MarkDiffusion in editable mode
pip install -e .
```

5.  Check code before commit:

Please ensure your code passes local tests and follows the project's coding style. If you added new features, please include corresponding test cases.

```bash
# Example: run tests
pytest
```

6.  Submit changes:

<!-- end list -->

```bash
git add .
git commit -m "commit message"
git fetch upstream
git rebase upstream/main
git push -u origin dev_your_branch
```

7.  Create a merge request from your branch `dev_your_branch` at [origin repo](https://github.com/THU-BPM/MarkDiffusion).

<!-- end list -->
