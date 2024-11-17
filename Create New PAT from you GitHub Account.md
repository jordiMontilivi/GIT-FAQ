# How to Create a New PAT from Your GitHub Account

Learn how to create a new Personal Access Token (PAT) from your GitHub account by following the steps below. Watch the tutorial for a detailed walkthrough:  
**[Video Tutorial](https://www.youtube.com/watch?v=2nzOI-ynXF4&t=379s)**

## Steps to Create a PAT

### 1. Log in to GitHub
- Go to [github.com](https://github.com) and log in to your GitHub account.

### 2. Access Developer Settings
- In the upper-right corner of any page, click your profile picture, then click **Settings**.
- In the left sidebar, scroll down and click **Developer settings**.

### 3. Generate a New Personal Access Token
- On the Developer settings page, click **Personal access tokens** in the left sidebar.
- Under Personal access tokens, choose:
  - **Tokens (classic)** for general purposes.
  - **Fine-grained tokens** for enhanced control over permissions.
- Click the **Generate new token** button.

### 4. Set Token Permissions
- Add a note to describe the purpose of the token (e.g., "Git Push for Repo XYZ").
- Set an expiration date for the token (recommended for security).
- Select the necessary scopes for the token:
  - **repo**: Full control of private repositories (required for pushing to repositories).
  - **workflow**: For GitHub Actions.
  - **admin**: For organizational repositories.
  - Additional permissions as needed, such as `read:org` or `write:packages`.
- For basic repository actions like cloning, pulling, and pushing, the **repo** scope is essential.

### 5. Generate the Token
- Click **Generate token** at the bottom of the page.

### 6. Save the Token
- Once generated, GitHub will display the token **only once**.
- Copy the token and save it in a secure location, such as a password manager.

### 7. Use the PAT in Git
- When prompted for a password during a `git push`, use the token instead of your GitHub password.
- Alternatively:
  - Update your Git credentials or remote URL to use the token.
  - Configure Git to store the token using a credential helper for secure caching.

This guide ensures you can generate and securely use a PAT for GitHub operations.