# GitHub Profile Repo Setup (5 minutes)

1. In GitHub, create a new public repository named exactly:
   `mokuzaitenko-source`

2. Do not initialize it with any files.

3. On your machine:

```powershell
cd C:\Users\alvin\TEst\introtodeeplearning
mkdir C:\Users\alvin\Documents\GitHub\mokuzaitenko-source -Force
Copy-Item PROFILE_README.md C:\Users\alvin\Documents\GitHub\mokuzaitenko-source\README.md -Force
cd C:\Users\alvin\Documents\GitHub\mokuzaitenko-source
git init
git add README.md
git commit -m "docs: add GitHub profile README"
git branch -M main
git remote add origin https://github.com/mokuzaitenko-source/mokuzaitenko-source.git
git push -u origin main
```

4. Go to your GitHub profile and pin repositories:
- TEst
- (one automation repo)
- (one deep learning lab/notebook repo)
- (one support tooling repo)

## Optional polish
- Replace `<your-linkedin-handle>` in `README.md`.
- Add one screenshot or GIF below Featured Project.
- Keep profile README concise; avoid long architecture blocks.
