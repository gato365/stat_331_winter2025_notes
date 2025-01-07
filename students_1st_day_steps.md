

### **Student Workflow: Creating and Working on Their Branch**

1. **Create a New Branch**:
   - Ask students to create a branch named after their own initials (or another naming convention, like full name):
     ```bash
     git checkout -b your_initials
     ```
     Example:
     ```bash
     git checkout -b imw
     ```

2. **Push the Branch to GitHub**:
   - Instruct students to push their branch to the remote repository:
     ```bash
     git push -u origin your_initials
     ```
     Example:
     ```bash
     git push -u origin imw
     ```

3. **Verify the Branch on GitHub**:
   - Have them check their branch on GitHub to confirm it was created successfully.

4. **Work Exclusively on Their Branch**:
   - Emphasize that students should always switch to their branch before making changes:
     ```bash
     git checkout your_initials
     ```
   - They should **never edit or commit to `main`**.

5. **Pull Updates from `main` Weekly**:
   - To get the latest class materials, students will pull updates from `main` into their branch:
     ```bash
     git checkout your_initials
     git pull origin main
     ```
