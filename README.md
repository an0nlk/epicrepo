# Epic Repo

A simple iOS jailbreak repository by **Anon LK** – hosting tweaks and packages for Sileo, Zebra, and Cydia.

---

## 📥 Add to Sileo / Zebra
You can add this repo by opening the following URL:

```
https://an0nlk.github.io/epicrepo/
```

---

## 📂 Repository Structure
- `debs/` → All tweak `.deb` files live here
- `Packages` / `Packages.bz2` → Auto-generated package list
- `Release` → Repo metadata
- `index.html` → Web landing page

---

## ⚙️ How to Add Tweaks
1. Place your `.deb` inside the `debs/` folder.  
2. Rebuild the `Packages` files:
   ```bash
   dpkg-scanpackages debs /dev/null > Packages
   bzip2 -k Packages
   ```
4. Done 🎉

---

## 📌 Repo URL
**Main URL:**  
👉 [https://an0nlk.github.io/epicrepo/](https://an0nlk.github.io/epicrepo/)
