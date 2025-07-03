# ✅ Complete Guide: How to Do more than 5 GitHub Commits to become Zama Eligible
---

## 🪜 Step-by-Step Instructions

### 1️⃣ Create a New Repository

- Visit: https://github.com/new  
- Repository Name: `zama-commit` (or any name you want)  
- Set to **Public**  
- ✅ Tick "Add a README file"  
- Click **Create repository**

---

### 2️⃣ Open Codespace

- After repo creation, click the green `<> Code` button  
- Select: **Open with Codespaces → + New codespace**  
- Wait for Codespace to load (~20 seconds)

---

### 3️⃣ Open Terminal in Codespace

---

### 4️⃣ Run the Following Commands

Paste the following code in the terminal:

```
for i in {1..20}
do
  echo "Commit $i line" >> README.md
  git add README.md
  GIT_AUTHOR_DATE="$(date -d "$i days ago" +"%Y-%m-%dT12:00:00")" \
  GIT_COMMITTER_DATE="$(date -d "$i days ago" +"%Y-%m-%dT12:00:00")" \
  git commit -m "Commit $i"
done
```

git push
```

---

💥 You’re Done!

• Close Every Tab (Browser)

• Just Wait 5-10 Minutes Max

• You now have 20 public commits visible on your profile — ready to use for Zama Developer Program.

## 🙌 Guide Created by: [@EarnByAbhi](https://x.com/earnbyabhi) updated by [@Edemblinks](https://x.com/edemblinks)

Follow & Stay Connected for More Zama Alpha, Airdrops & Dev Tutorials

- 📍 X (Twitter): [@Edemblinks](https://x.com/edemblinks)

---
