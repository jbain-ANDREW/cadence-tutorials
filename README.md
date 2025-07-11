# CMU Cadence Tutorial Site

Welcome to the official repository for the **CMU Cadence Tutorial Suite**, designed to help new students set up and use Cadence tools effectively.

This site provides:
- Step-by-step setup guides
- VPN and remote access instructions
- Schematic and layout tutorials
- Navigation through the Cadence design flow
- Helpful screenshots and tips

📚 **Live site**: [https://cmu-cadence-tutorial.netlify.app](https://cmu-cadence-tutorial.netlify.app)

---

## 🛠 How to Contribute

This repository is automatically deployed via Netlify. To make changes:

1. **Clone the repo** (or pull latest changes):

    ```bash
    git pull
    ```

2. **Edit Markdown files** in the `docs/` directory.  
   Add images to `docs/assets/`.

3. **Test locally** (optional but recommended):

    ```bash
    mkdocs serve
    ```

4. **Commit and push** your changes:

    ```bash
    git add .
    git commit -m "Update: Added tutorial section on [topic]"
    git push
    ```

Netlify will automatically rebuild and publish the site after every push to the `main` (or `master`) branch.

---

## 📁 Project Structure

```
mkdocs.yml           # Site configuration
requirements.txt     # Python dependencies for Netlify
netlify.toml         # Netlify build instructions
docs/
  ├── index.md       # Homepage
  ├── vpn.md         # VPN setup guide
  ├── schematic.md   # Schematic entry tutorial
  └── assets/        # Images used in tutorials
```

---

## 🧰 Tech Stack

- [MkDocs](https://www.mkdocs.org/)
- [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/)
- [Netlify](https://www.netlify.com/) for deployment

---

## 👥 Maintainers

This site is maintained by CMU students and faculty.  
For access, editing privileges, or questions, please open an issue or contact the repository owner.
