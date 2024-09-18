# How to Create and Edit a Pull Request on GitHub

This guide will walk you through creating a pull request, editing files, and committing changes.

## Steps to Create a Pull Request

1. **Open the GitHub repository** where your branches are located.
2. Navigate to the **Pull requests** tab.
3. Click **New pull request**.
4. For the branches to compare, select:
   - **Base branch**: `main`
   - **Compare branch**: `start-markdown`
5. Click **Create pull request**.

## Editing the `index.md` File

Once the pull request is created, follow these steps to edit the `index.md` file:

1. In the pull request, go to the **Files changed** tab.
2. Locate the `index.md` file.
3. Click the three dots (`...`) in the upper-right corner of the file view.
4. Select **Edit file** from the menu.

## Adding Headers to Markdown

- To make a heading, use the `#` symbol followed by a space:
  - `#` for H1
  - `##` for H2
  - `###` for H3, and so on up to H6 (`######`).
  
### Example:
```markdown
# Main Header (H1)

## Sub Header (H2)

### Another Sub Header (H3)

This markdown document clearly describes the process, making it easy for team members to follow .
```
## Steps to Add an Image in Markdown
1. **Navigate to the Pull Request**: 
   - Go to the **Pull requests** tab in your repository.
   - Locate the pull request where you want to edit the `index.md` file.
   
2. **Edit the `index.md` File**:
   - In the pull request, click the **Files changed** tab.
   - Find the `index.md` file.
   - Click the three dots (`...`) in the upper-right corner of the file view and select **Edit file**.

3. **Add Image with Alt-Text**:
   - Use the following Markdown syntax to include an image with alt-text:
     ![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

   - Replace the URL (`https://example.com/your-image-url.jpg`) with the actual link to your image.
   - Replace the alt-text in the square brackets `[]` with a short description of the image.
