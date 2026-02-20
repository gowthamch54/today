# today

today is exam



Perfect 👍 now I will give you **simple step-by-step for each experiment**, clearly and slowly, not compressed.

No confusion. Just basic steps.

---

# ✅ EXP 1: Create Repository → Edit → Push

### Step 1

Go to GitHub → Click **New repository** → Add README → Create.

### Step 2

Open Git Bash and type:

```bash
git clone https://github.com/YOUR-USERNAME/repo-name.git
```

### Step 3

Go inside folder:

```bash
cd repo-name
```

### Step 4

Open file:

```bash
notepad README.md
```

(Edit and Save)

### Step 5

Check changes:

```bash
git status
```

### Step 6

Stage and commit:

```bash
git add README.md
git commit -m "Updated README"
```

### Step 7

Push to GitHub:

```bash
git push origin main
```

---

# ✅ EXP 2: Create Branch → Add Feature → Merge

### Step 1

Go to project folder:

```bash
cd repo-name
```

### Step 2

Create branch:

```bash
git checkout -b feature-login
```

### Step 3

Create new file:

```bash
notepad login.py
```

(Add code and Save)

### Step 4

Stage file:

```bash
git add login.py
```

### Step 5

Commit:

```bash
git commit -m "Added login feature"
```

### Step 6

Push branch:

```bash
git push origin feature-login
```

### Step 7

Go to GitHub → Create Pull Request → Merge.

---

# ✅ EXP 3: Pull Latest Changes

### Step 1

Go to project:

```bash
cd repo-name
```

### Step 2

Switch to main:

```bash
git checkout main
```

### Step 3

Pull updates:

```bash
git pull origin main
```

### Step 4

Open file:

```bash
notepad README.md
```

### Step 5

Check new changes.

---

# ✅ EXP 4: Create Merge Conflict & Resolve

### Step 1

Switch to branch:

```bash
git checkout feature-login
```

### Step 2

Merge main:

```bash
git merge main
```

### Step 3

Conflict appears.

### Step 4

Open file:

```bash
notepad README.md
```

### Step 5

Remove:

```
<<<<<<<
=======
>>>>>>>
```

### Step 6

Stage resolved file:

```bash
git add README.md
```

### Step 7

Commit and push:

```bash
git commit -m "Resolved conflict"
git push origin feature-login
```

---

# ✅ EXP 5: Fork and Contribute

### Step 1

Fork repository on GitHub.

### Step 2

Clone fork:

```bash
git clone https://github.com/YOUR-USERNAME/project.git
```

### Step 3

Go inside:

```bash
cd project
```

### Step 4

Create branch:

```bash
git checkout -b feature-update
```

### Step 5

Add file:

```bash
notepad newfile.txt
```

### Step 6

Commit:

```bash
git add newfile.txt
git commit -m "Added new feature"
```

### Step 7

Push and create Pull Request:

```bash
git push origin feature-update
```

Then create PR on GitHub.

---

# 🔹 These Are The Only Commands You Really Use

```
git clone
git status
git add
git commit -m
git push
git pull
git checkout -b
git checkout
git merge
```



