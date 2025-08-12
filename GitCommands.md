# Git Configuration & First Push Guide (Windows PowerShell)

## 1. Check Git Version
```powershell
git --version
````

## 2. Set Global Git Username

```powershell
git config --global user.name "username"
```

## 3. Set Global Git Email

```powershell
git config --global user.email "you@example.com"
```

## 4. Verify Global Config

```powershell
git config --global user.name
git config --global user.email
```

## 5. View All Git Configurations

```powershell
git config --list
```

## 6. (Optional) Manually Check the Global Config File

```powershell
notepad $env:USERPROFILE\.gitconfig
```

---

## 7. Initialize a Local Git Repository

```powershell
git init
```

## 8. Add Files to Staging

```powershell
git add .
```

## 9. Commit Changes

```powershell
git commit -m "first commit"
```

## 10. Rename Branch to `main` (GitHub default)

```powershell
git branch -M main
```

## 11. Add GitHub Remote

```powershell
git remote add origin https://github.com/<YourUsername>/<RepoName>.git
```

## 12. Authenticate with GitHub (Browser Login)

If prompted, log in via browser and authorize Git.

---

## 13. Push Code to GitHub

```powershell
git push -u origin main
```

✅ Your code is now uploaded to GitHub.

