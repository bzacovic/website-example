## Example website

This is a template for developing your own personal academic website using the [quarto framework](https://quarto.org/).

### Prerequisites

Before you begin, ensure you have met the following requirements:

- You have a [GitHub account](https://github.com/join).
    Test this by signing in to your account [here](https://github.com/login).
- You have [Git](https://git-scm.com/) installed on your computer.
    Test this by opening your terminal and running `git --version`.
- You have [Quarto](https://quarto.org/docs/get-started/) installed on your computer.
    Test this by opening your terminal and running `quarto --version`.

### Steps

1. Fork this repository to your own GitHub account. 


2. Clone the repository to your local machine.


3. Edit the `index.qmd` file in the `docs` folder to customize your website content.


3. Host using GitHub pages
- Click on Settings
<img src="README_images/settings.png" width="500"/>

- Click on Pages
<img src="README_images/pages.png" width="300"/>

- Select the "master" branch, then the "docs" folder, and click "Save" to tell GitHub where the HTML files can be found
<img src="README_images/docs.png" width="400"/>

- Can check the "Actions" tab to see the job where GitHub renders the Quarto markdown files into HTML. Once the deployment is complete a green checkmark will appear (typically less than a minute)
<img src="README_images/actions.png" width="400"/>

- After the website has been rendered, back on the Pages tab we can find a link to the website
<img src="README_images/hosted.png" width="400"/>

4. (Optional) Host on a custom domain. 

5. (Optional) Delete the `README_images` folder from your forked repository and edit this README, these are just instructions to get started. Can replace the `README.md` with something like:

```
## Your Name's personal website

Hosted at [yourdomain.com](https://www.yourdomain.com/)

Built with the [quarto framework](https://quarto.org/)
```
