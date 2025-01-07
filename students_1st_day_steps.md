

### **Student Workflow: Creating and Working on Their Branch**

1. **Create a New Branch**:
   - Ask students to create a branch named after their full name with an underscore between first and last name (full_name) e.g `immanuel_williams` do not use my name please lol:
     ```bash
     git checkout -b full_name
     ```
    Example:
     ```bash
     git checkout -b immanuel_williams
     ```


2. **Push the Branch to GitHub**:

   - Instruct students to push their branch to the remote repository:
     ```bash
     git push -u origin full_name
     ```
     Example:
     ```bash
     git push -u origin immanuel_williams
     ```

3. **Verify the Branch on GitHub**:
   - Have them check their branch on GitHub to confirm it was created successfully.

4. **Work Exclusively on Their Branch**:
   - Emphasize that students should always switch to their branch before making changes:
     ```bash
     git checkout full_name
     ```
   - They should **never edit or commit to `main`**.

5. **Pull Updates from `main` Weekly**:
   - To get the latest class materials, students will pull updates from `main` into their branch:
     ```bash
     git checkout full_name
     git pull origin main
     ```
