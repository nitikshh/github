# Git Configuration Guide (Windows PowerShell)

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
