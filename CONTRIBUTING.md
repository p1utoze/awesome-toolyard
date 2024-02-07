# Contribution Guidelines for the "Awesome Research Tools" Repository

Thank you for contributing to the **Awesome Research Tools** repository! I want to make accessing fine resource across the internet much easier and navigating across other awesome tools out there!<br>

I want to make contributing to this project as easy and transparent as possible, whether it's:
- Reporting a bug
- Discussing the current state of the code
- Submitting a fix
- Proposing new features
- Becoming a maintainer

-- --
Table of Contents
=================

   * [Contribution Guidelines for the "Awesome Research Tools" Repository](#contribution-guidelines-for-the-awesome-research-tools-repository)
   * [Contribution Procedure](#contribution-procedure)
   * [How do I contribute?](#how-do-i-contribute)
      * [Resource Format](#resource-format)
      * [Non-URL Resources](#non-url-resources)
      * [Validity Criteria](#validity-criteria)
      * [Table of Contents](#table-of-contents)
      * [Quality Check](#quality-check)
      * [Contributing Steps](#contributing-steps)
      * [PR Review Process](#pr-review-process)
      * [Be Courteous](#be-courteous)
   * [Software License](#any-contributions-you-make-will-be-under-the-mit-software-license)

-- --
## Contribution Procedure
We Use [Github Flow](https://guides.github.com/introduction/flow/index.html), So All Code Changes Happen Through Pull Requests are the best way to propose changes to the codebase (we use [Github Flow](https://guides.github.com/introduction/flow/index.html)). We actively welcome your pull requests:

1. Fork the repo and create a new branch in your forked repo from `main`.
2. Add the resource to the appropriate section in the `README.md` file.
3. Commit your changes and push your new branch to your forked repo.
4. Issue a pull request!
5. Verify that all CI checks have passed (we use pre-commit.ci) and the PR has been reviewed and approved by at least one maintainer.

-- --
## How do I contribute?
The project adheres to certain content-formatting and quality standards for consistent Markdown style. Please read the following guidelines below before committing and submitting a pull request (PR):
1. ### **Resource Format**:
    - Each resource should be added in the following format:
        ```
        - [**Resource Name**](Resource URL) - *Short Description*
        - [AI and Machine Learning for Coders] (https://www.oreilly.com/library/view/ai-and-machine/9781492078180/) - *If you're looking to make a career move from programmer to AI specialist, this is the ideal place to start. Based on Laurence Moroney's extremely successful AI courses, this introductory book provides a hands-on, code-first approach to help you build confidence while you learn key topics*
        ```
    - Replace **Resource Name** with the actual name of the tool and **Resource URL** with the link to the tool.
    - Provide a brief *Short Description* highlighting the tool's purpose or key features.

2. ### **Non-URL Resources**:
    - If the resource is a file, create a new folder `assets` (_if it doesn't exist_) in the same directory level.
    - Add the file inside the assets folder
    - Use the following format in the appropriate section of the `README.md` file:
        ```
        - [**Resource Name**](assets/name_of_the_file) - *Short Description*
        ```
    - Replace **Resource Name** with the actual name of the tool.
    - Replace **name_of_the_file** with the name of the file you added in the `assets` folder.
    - Provide a brief *Short Description* highlighting the tool's purpose or key features.

3. ### **Validity Criteria**:
    - The resource must be either **free** or offer a **freemium service** (with essential features available for free).
    - Avoid redundant resources that are already listed in the repository.
    - Don't add illegitimate or spammy resources with links to malicious websites.

4. ### **Table of Contents**:
    - If you are adding a new category, ensure that it is relevant to the repository and use the following format:
        ```
        ## Category Name
        ```
    - For subcategories, use the following format:
        ```
        ### Sub-Category Name
        ```
    - The main `README.md` file should have a clear table of contents pointing (TOC) to your newly added section with nested bullet points.
    - Organize resources under relevant categories (e.g., "Literature Search," "Data Analysis," "Machine Learning," etc.).

5. ### **Quality Check**:
    - Before submitting a new resource, ensure that it adds value to the repository.
    - Verify the credibility and usefulness of the tool.
    - Consider whether the tool is widely used or has positive reviews.

6. ### **Contributing Steps**:
    - Fork the repository to your GitHub account.
    - Create a new branch for your contribution.
    - Add the resource to the appropriate section in the `README.md` file.
    - Commit your changes and create a pull request (PR).

7. ### **PR Review Process**:
    - The maintainers will review your PR.
    - If the resource meets the criteria, it will be merged into the repository.
    - If necessary, the maintainers may request additional information or changes.

8. ### **Be Courteous**:
    - Be respectful and considerate in your interactions with other contributors.
    - Encourage open discussions and collaboration.
-- --

## Any contributions you make will be under the MIT Software License
In short, when you submit code changes, your submissions are understood to be under the same [MIT License](http://choosealicense.com/licenses/mit/) that covers the project. Feel free to contact the maintainers if that's a concern.

-- --
Remember, this repository thrives on community contributions, so thank you for helping make it a valuable resource for everyone! 💻
