# How to Host Your Simple Website for Free

This guide will walk you through hosting your simple website (the `index.html`, `style.css`, and `script.js` files) online for free, so anyone with the link can visit it. We'll primarily use a service called **Netlify** because it's very user-friendly and lets you customize your website's address (URL) for free.

## Prerequisites

Before you start, make sure you have:

1.  **Your Website Files:** The `index.html`, `style.css`, and `script.js` files we created earlier. It's helpful to have them together in one folder on your computer.
2.  **A Free Netlify Account:** You'll need to sign up for a free account at [https://www.netlify.com/](https://www.netlify.com/). You can usually sign up using your email, GitHub, GitLab, or Bitbucket account.

## Method 1: Hosting with Netlify (Recommended)

Netlify makes hosting static websites (like the one we built) incredibly easy. The simplest way is using their drag-and-drop feature.

**Step 1: Sign Up / Log In to Netlify**

- Go to [https://www.netlify.com/](https://www.netlify.com/).
- Click "Sign up" to create a new account (it's free!) or "Log in" if you already have one.

**Step 2: Prepare Your Files**

- Make sure your `index.html`, `style.css`, and `script.js` files are together in a single folder on your computer. Let's call this folder `my-simple-website`.

**Step 3: Deploy Your Website**

- Once logged into Netlify, you'll likely be on your dashboard.
- Look for a section often labeled "Sites" or similar. There should be an option like "Add new site" or a large area prompting you to drag and drop your site folder.
- Select the option for manual deployment, often called "Deploy manually".
- **Drag the entire `my-simple-website` folder** from your computer onto the designated area in your browser on the Netlify site.
- Netlify will automatically upload your files and start building your site. This usually only takes a minute or two.

**Step 4: Access Your Live Site**

- Once the deployment is complete (Netlify will indicate this), it will provide you with a default URL. It will look something like `random-adjective-random-noun-12345.netlify.app`.
- Click on this link! Your website is now live online.

**Step 5: Get a Nicer URL (Optional but Recommended)**

The default URL works, but it's not very memorable. Let's change it:

- In your Netlify dashboard, go to the settings for the site you just deployed. This might be under "Site overview" or "Site settings".
- Look for an option like "Change site name" or "Site details".
- Click the button to change the site name.
- You can now type in a custom name. Choose something unique and relevant to your site (e.g., `yourname-simple-website`).
- If the name is available, your new URL will be `your-chosen-name.netlify.app`. This looks much more like a "normal" link!
- Save the changes.

**Congratulations!** Your website is now hosted for free at `your-chosen-name.netlify.app` (or whatever name you chose) and can be accessed by anyone with the link.

## Method 2: Hosting with GitHub Pages (Alternative)

GitHub Pages is another excellent free option, especially if you already use GitHub for storing code.

**Brief Steps:**

1.  **Create a GitHub Account:** If you don't have one, sign up at [https://github.com/](https://github.com/).
2.  **Create a New Repository:** Create a _public_ repository on GitHub. Name it something like `my-simple-website`.
3.  **Upload Files:** Upload your `index.html`, `style.css`, and `script.js` files to this new repository.
4.  **Enable GitHub Pages:** Go to the repository's "Settings" tab, scroll down to the "Pages" section, and select the `main` (or `master`) branch as the source. Save the changes.
5.  **Access Your Site:** GitHub will provide a URL, usually in the format `your-github-username.github.io/your-repository-name`. It might take a few minutes to become active.

While functional, the URL isn't as customizable for free as Netlify's `.netlify.app` domain.

## Conclusion

You've successfully hosted your website online for free! Using Netlify's drag-and-drop is often the quickest way for beginners to get a site live with a customisable link. Share your new URL with others!
