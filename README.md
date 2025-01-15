

## **How to Get Weekly Notes**

To access the latest weekly notes and video materials, follow these steps **every week**:
### **Final Revised Instructions for README**

<<<<<<< HEAD
Here’s how the updated section of your README should look:

---

## **How to Get Weekly Updates**

To get the latest class materials, follow these steps **every week**:

1. **Switch to `main`**:
   ```bash
   git checkout main
   ```

2. **Pull Updates from the Remote Repository**:
   ```bash
   git pull origin main
   ```

3. **Switch Back to Your Personal Branch**:
   ```bash
   git checkout full_name
   ```

4. **Merge Updates from `main` into Your Branch**:
   ```bash
   git merge main
   ```


















=======
### **Step 1: Ensure You Are on Your Branch**
Before pulling any updates, confirm you are on your personal branch (e.g., `your_name`).

1. Open your terminal and navigate to your project folder:

```bash
cd stat_331_winter2025_notes
```

2. Check your current branch:
```bash
git branch
```
- The branch name with an asterisk (*) next to it is your current branch.
- If you're not on your branch (e.g., `main` is active), switch to your branch:

```bash
git checkout full_name
```

---

### **Step 2: Pull Updates from `main` (Current Notes)**

To get the latest notes added by the instructor:
1. Ensure you are on your branch:
   
```bash
git branch
```
 - The active branch should be your personal branch (e.g., `full_name`).
 
 
 2. Move to the `main` branch
 
```bash
git checkout main
``` 
 

3. Pull updates from the `main` branch into your branch:
   
```bash
git pull origin main
```

4. Move the updates from the main branch to your branch `full_name`

```bash
git checkout full_name
```

5. Update your branch

```bash
git merge main
```

---

### **Step 3: Verify the Updates**
1. After pulling updates, verify the new files or updates by checking your folder or opening the files in RStudio.
2. If you encounter merge conflicts, reach out to the instructor for assistance.

---

### **Step 4: Work Only in Your Branch**
- Make sure all your edits or additions are done in your personal branch.
- You should **never commit changes to `main`**.

If you make changes (e.g., adding notes or personal reflections), save them to your branch:
1. Stage the changes:

```bash
git add .
```
2. Commit your changes with a meaningful message:
```bash
git commit -m "Added personal notes for week X"
```
3. Push the changes to your branch:
```bash
git push origin your_full_name
```

---

### **Tips and Reminders**
1. **Always Confirm Your Branch**: Before making any changes, ensure you're working on your branch.
```bash
git branch
```
2. **Do Not Work on `main`**: Never edit or commit directly to the `main` branch.
3. **Pull Updates Weekly**: Make it a habit to pull updates from `main` every week to get the latest materials.
>>>>>>> main


