<img src="images/image.png" width="300" alt="image">

## 1. Annotated Tags vs. Lightweight Tags
- **Annotated Tags:**
  - Stored as full objects in Git.
  - Include metadata such as the tagger’s name, email, and a tagging message.
- **Lightweight Tags:**
  - Simply pointers to specific commits without any extra metadata.

*Use annotated tags for releases and lightweight tags for simpler cases.*

---

## 2. When to Use Rebase
- **Benefits:**
  - Maintains a clean, linear commit history.
  - Applies changes from one branch onto another efficiently.
- **Caution:**
  - Avoid using rebase on public/shared branches as it rewrites commit history.

---

## 3. How to List Tags
- To list all Git tags, run: `git tag`

---


## 5. How to Delete Branches Locally and Remotely
- **Delete Branch Locally:**  
  Run: `git branch -d <branch-name>`
- **Delete Branch Remotely:**  
  Run: `git push origin --delete <branch-name>`




