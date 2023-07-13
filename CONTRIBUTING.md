# DarJS Blog Contribution Guide

Thank you for your interest in contributing to the DarJS Blog! This guide will walk you through the process of adding a new blog post or updating an existing draft. Let's get started!

## How Can You Contribute?

To contribute to the DarJS Blog, you will need to follow these steps:

1. **Fork the Repository**: Start by forking the [DarJS Blog repository](https://github.com/dardotjs/blog) to your GitHub account. This will create a copy of the repository under your account.

2. **Clone the Repository**: Next, clone the forked repository to your local machine using the following command:

   ```
   git clone https://github.com/your-username/blog.git
   ```

3. **Create a Branch**: Create a new branch for your changes. It's recommended to use a descriptive branch name that reflects the purpose of your contribution. For example:

   ```
   git checkout -b add-new-blog-post
   ```

4. **Make Your Changes**: Now you can add a new blog post or make updates to an existing one. The blog posts are written in plain Markdown and are located in the `/blog` directory. You can use the `00-00-00-template.md` file as a starting point for a new blog post. Duplicate the template file and rename it with the desired date and a slug of the post title, for example: `23-07-13-hello-world.md`.

5. **Edit Metadata**: Open the blog post file you created and update the metadata section at the top of the file. The metadata follows the YAML format and contains information such as the title, author, date, and whether the post is a draft. Ensure that you fill in the required fields appropriately.

6. **Preview Your Changes**: Before submitting your contribution, it's a good idea to preview your changes locally. You can use a Markdown editor or a tool like [Dillinger](https://dillinger.io/) to view how your blog post will appear.

7. **Commit Your Changes**: Once you are satisfied with your changes, it's time to commit them. Use the following commands to commit your changes:

   ```
   git add .
   git commit -m "Add new blog post: Hello World"
   ```

8. **Push Your Changes**: Push your changes to your forked repository:

   ```
   git push origin add-new-blog-post
   ```

9. **Open a Pull Request**: Finally, open a pull request (PR) on the original DarJS Blog repository. Go to the [DarJS Blog repository](https://github.com/dardotjs/blog) on GitHub and click on the "New Pull Request" button. Provide a clear title and description for your PR, explaining the changes you made. Once you submit the PR, the DarJS team will review your contribution.

That's it! You have successfully contributed to the DarJS Blog. Thank you for your valuable input!

## Updating a Draft Blog Post

If you would like to update an existing draft blog post, follow these steps:

1. Locate the draft blog post file in the `/blog` directory. The draft posts are prefixed with the `draft` status in the metadata section.

2. Open the draft blog post file and make the necessary updates to the content or metadata.

3. Commit and push your changes to your forked repository.

4. Open a pull request on the original DarJS Blog repository, explaining the updates you made to the draft post.

The DarJS team will review your changes and merge them if they meet the required criteria.

Thank you for your contributions to the DarJS Blog! We appreciate your efforts in helping us share valuable content with the community.
