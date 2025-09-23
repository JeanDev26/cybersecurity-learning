# 📂 Examples – Module 5: Software

## Installing Git on Windows
1. Download the installer from the official website: [git-scm.com](https://git-scm.com).  
2. Run the `.exe` file and follow the installation steps.  
3. Verify installation:
   ```powershell
   git --version
   ```

---

## Installing Git on Linux
- On Debian/Ubuntu:
  ```bash
  sudo apt update
  sudo apt install git -y
  ```
- On Fedora/RHEL:
  ```bash
  sudo dnf install git -y
  ```
- Verify installation:
  ```bash
  git --version
  ```

---

## Installing Software on Linux
```bash
sudo apt install firefox
```

---

## Removing Software on Linux
```bash
sudo apt remove firefox
```

---

## Updating Software on Linux
```bash
sudo apt update && sudo apt upgrade
```

---

## Installing Software on Windows (Winget)
```powershell
winget install Google.Chrome
```

---

## Removing Software on Windows
```powershell
winget uninstall Google.Chrome
```

---

## Updating Software on Windows
```powershell
winget upgrade --all
```
