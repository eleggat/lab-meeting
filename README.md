# Making a personal academic website on GitHub
:tada: Shoutout to Deren and his post-doc Isaac for making me do this in class :tada:

There are lots of ways to make a personal website, but one of the most snazzy is through GitHub. It's incredibly customizable, and you'll look smart to anyone who visits because they'll see it's on GitHub, which is a website smart people use. There are simple and complex ways to do it, but this will be a quick and easy way.

## Make a GitHub account 
1. If you don't already have one, go to [github.com](https://www.github.com) to sign up for an account.
2. When choosing your username, keep in mind this will be in the URL for your website, unless you buy a separate domain. So it's probably good to have it be your name in some way.
3. Verify your email!

## Making your website
There are lots of themes out there to make a nice looking website, and lots that are specifically for academic personal sites. [This](https://github.com/jitinnair1/gradfolio/) is the one I use, but [this one](https://github.com/academicpages/academicpages.github.io), and also [this one](https://github.com/alshedivat/al-folio) are commonly used. All of them are set up as personal academic sites. For the sake of simplicity, these instructions are for the [academic-pages](https://github.com/academicpages/academicpages.github.io) theme, but they should be largely similar for any other.
1. On the **academic-pages** page, click the green **use this template** button in the top right.
2. Click **create a new repository**.
3. *Important:* name your repository `[yourusername].github.io`
	1.  GitHub gives you one free domain, and this is it, so if you name it something else, the page won't load as your website.
4. Click **create repository** at the bottom.
5. It will take a few minutes to load any recent changes, but your site will then be available at the URL `[yourusername].github.io`
	1. I recommend adding the link to the repository **About** panel on the right

## Customizing your website
Check out the `README.md` file, or scroll to the bottom of the main repository page for information about customizing the website. This theme has a lot of default information (most do), so you'll need to delete it and re-fill it with your own. For info on markdown and the layout of this theme, look in `_pages > markdown.md`
1. In the page of files, scroll down and open the `_config.yml` file. This contains basic site info like your name, affiliation, contact info, and so on. To edit this, click the pencil in the top right.
	1. You probably only need to edit what is under the `Basic Site Settings` and `Site Author` headings
2. When you are done editing, click the **commit changes** button in the top right. When prompted, add a message for what you did (e.g., edited basic site info), or you can leave the default message. Commit the changes.
3. Go back to the page of files. Now click on `_pages` and then `about.md`. This is what will show up on the home page, so edit to your heart's desire (recall your elevator pitch)! It's written in markdown, so here is some [markdown formatting info](https://www.geeksforgeeks.org/markdown-cheat-sheet/) if you're unfamiliar. Commit the changes you've made the same way as before.
4. To change the photo, navigate into the `images` folder and upload the photo you'd like to use by clicking **add file** on the top right. Once it's uploaded, go back into the `_config.yml` file and, under the `Biographical Information` header, change the `avatar` to the name of your image file. Commit the changes.
5. If you want a website version of your CV, you can edit that under `_pages > cv.md`. This is also written in markdown.
	1. Alternatively, you can embed a PDF of your CV using HTML. You'll need to upload the PDF to the `files` folder first.
