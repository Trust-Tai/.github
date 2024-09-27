## Howdy 👋

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
---
Trust-Tai Git & GitHub Setup Onboarding Guide (Trusting Thai Process)
---

# **Welcome to the Team! 🚀**
We’re excited to have you onboard, and even more excited to introduce **GitHub** into our development process! GitHub isn’t just a tool; it’s a superpower that will transform how we collaborate, track changes, and build amazing things together. This guide will walk you through everything you need to know, from getting started to becoming a GitHub ninja. Let’s dive in!

---

## **1. Why GitHub? 🤔**
Before we jump into the setup, let’s answer the big question: **Why GitHub?**

Think of GitHub as your project’s time machine and collaboration station. It lets us:

- Track changes and revert them if needed (no more “oops” moments).
- Collaborate seamlessly without stepping on each other’s toes.
- Catch bugs early with **Pull Requests** and code reviews.
- See exactly **who did what** and why (we love accountability 😄).

With GitHub, your code becomes more than just lines on a screen; it’s part of a living, breathing ecosystem. 🌱

---

# Step 2: Git & GitHub Setup 🛠️

Ready to become a part of the magic? Let's get you set up!

## Step 2.1: Install Git

If Git isn't already on your machine, let's fix that:

- Head to Git Downloads (https://git-scm.com/downloads) and follow the
instructions for your operating system.
- Check if Git is installed by running:

git --version

You should see something like git version 2.30.1 (your version may
vary).

## Step 2.2: Create a GitHub Account

• Visit GitHub (https://github.com) and create an account if you don't
have one yet. It's free, and we promise you'll love it!
• Once you've signed up, share your GitHub username with the team so we
can add you to the relevant repositories.

## Step 2.3: Configure Git

Let's tell Git who you are:

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

Now Git knows you by name. 🙌

# Step 3: Let's Git Started: The Basics 🚦

Here's a quick crash course on the commands you'll use daily:

## Step 3.1: Cloning the Repository

First, you need a local copy of the project:

```bash
git clone <repository-url>
```

This downloads the entire project to your machine. Welcome aboard! 🎉

## Step 3.2: Branching: Your Own Adventure 🌿

Never, and we mean never work directly on the main branch. Create your
own branch to keep things tidy and avoid breaking stuff:

```bash
git checkout -b feature/amazing-feature
```

Your branch is your playground. Want to try something new? Do it here.
Break stuff? No worries, you're in your own world.

## Step 3.3: Making Changes

You've done some amazing work. Now it's time to commit your changes:

```bash
git add <file>
git commit -m "A brief but descriptive commit message"
```

Commits should tell a story. No "fixed stuff" allowed --- be specific!

## Step 3.4: Pushing Changes

When you're happy with your changes, push your branch to GitHub:

```bash
git push origin feature/amazing-feature
```

Your branch now lives in the cloud, ready for the team to review.

# Step 4: Creating a Pull Request (PR) 🚀

Before we can merge your amazing work into the main codebase, we need to
review it. To do this, you'll create a Pull Request (PR):

- Go to the repository on GitHub
- Click on the "Pull Requests" tab
- Click the "New Pull Request" button
- Select your branch from the dropdown
- Add a title and description for your PR, explaining what you've done
and why
- Click "Create Pull Request"

Great! Now your work is ready for the team to review.

# Step 5: Code Review 🧐

The code review process is crucial to maintaining the quality and
integrity of the codebase. Here's how we handle it:

- After creating your PR, a team member will review the changes
- The reviewer will leave comments or suggestions if needed
- Address the feedback and make the necessary changes
- Once approved, the PR will be merged into the main branch

Remember, reviews aren't criticisms --- they're part of the
collaborative process. We all improve together!

# Step 6: Keep Your Branch Updated 🔄

As others push code to the repository, your branch can get out of sync
with the main branch. To keep your branch up to date:

```bash
git fetch origin
git pull origin main
```

This ensures you're working with the latest code and avoids merge
conflicts later.

# Step 7: Merging with the Main Branch 🏆

Once your PR is approved and merged, you can update your local copy of
the main branch:

```bash
git checkout main
git pull origin main
```

Congratulations, your work is now part of the project!

# Step 8: Wrap-Up 🥳

That's it! You're now equipped to contribute to the project using Git
and GitHub. We're excited to see what you build. Remember, we're all
learning together, so don't hesitate to ask questions or suggest
improvements to the process.

