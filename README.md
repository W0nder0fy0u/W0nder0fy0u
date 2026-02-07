# 🚀 Automated GitHub Profile Setup - Instructions

## What This Script Does

This Python script will **automatically**:
- ✅ Create your profile repository (W0nder0fy0u/W0nder0fy0u)
- ✅ Upload and customize all README files
- ✅ Add topics/tags to all repositories
- ✅ Update your profile bio and location
- ✅ Replace all placeholders with your information

**Total time: 2 minutes (after setup)**

---

## Step-by-Step Instructions

### Step 1: Create a New GitHub Token (2 minutes)

⚠️ **IMPORTANT:** Create a NEW token, NOT the one you shared before!

1. **Go to:** https://github.com/settings/tokens/new
2. **Token name:** `Profile Setup Script` (or any name)
3. **Expiration:** Select "7 days" (you'll delete it after using)
4. **Select permissions:**
   - ✅ Check **`repo`** (all repository permissions)
   - ✅ Check **`user`** (update user profile)
5. **Click:** "Generate token" (green button at bottom)
6. **Copy the token** (it starts with `ghp_...`)
7. **KEEP IT SAFE** - don't close the page yet!

---

### Step 2: Download All Files (1 minute)

You should have these files downloaded:
- `setup_github.py` ← The automation script
- `README.md` ← Your profile README
- `prepAI_README.md`
- `linux-diagnostic-tool_README.md`
- `kirtan-committee_README.md`

**Put all 5 files in the same folder** (e.g., Desktop/github-setup/)

---

### Step 3: Install Python (if not already installed)

**Check if you have Python:**
```bash
python --version
```
or
```bash
python3 --version
```

**If you don't have Python:**
- **Windows:** Download from https://www.python.org/downloads/
- **Linux (Arch):** Already installed! 
- **Mac:** Already installed!

---

### Step 4: Install Required Package (30 seconds)

Open terminal/command prompt in the folder with the files:

```bash
pip install requests
```

or if that doesn't work:

```bash
pip3 install requests
```

---

### Step 5: Run the Script! (2 minutes)

**In the terminal, run:**

```bash
python setup_github.py
```

or:

```bash
python3 setup_github.py
```

**The script will ask you for:**

1. **GitHub Token:** Paste the token you created (from Step 1)
2. **Email:** Your email address

**Then watch it work!** It will:
- ✅ Verify your token
- ✅ Create/update all repositories
- ✅ Upload all README files
- ✅ Add topics
- ✅ Update your profile

---

### Step 6: Delete Your Token! (30 seconds)

**IMMEDIATELY after the script finishes:**

1. Go to: https://github.com/settings/tokens
2. Find the token you just created
3. Click **"Delete"**
4. Confirm deletion

---

## 🎉 You're Done!

**Check your profile:**
https://github.com/W0nder0fy0u

Everything should be set up professionally!

---

## Troubleshooting

### "Module 'requests' not found"
```bash
pip install requests
# or
pip3 install requests
```

### "Permission denied"
```bash
# On Linux/Mac, try:
chmod +x setup_github.py
python3 setup_github.py
```

### "Invalid token"
- Make sure you created a NEW token
- Make sure you selected 'repo' and 'user' permissions
- Make sure you copied the ENTIRE token (starts with ghp_)

### "Repository not found"
- Your repositories (prepAI, linux-diagnostic-tool, kirtan-committee) must already exist
- The script updates them, it doesn't create them (except the profile repo)

### Script fails halfway
- Don't worry! You can run it again
- It will skip already completed steps
- Just make sure all 5 files are in the same folder

---

## What If I Want to Do It Manually?

If the script doesn't work, use **QUICK_START.md** for manual instructions!

---

## Security Notes

✅ **DO:**
- Create a new token for this script
- Delete the token after use
- Use a 7-day expiration
- Keep the token private

❌ **DON'T:**
- Reuse old tokens
- Share tokens in chat/email
- Give more permissions than needed
- Leave tokens active after use

---

## Need Help?

If something goes wrong:
1. Read the error message carefully
2. Check the troubleshooting section above
3. Make sure all files are in the same folder
4. Try running the script again

---

**Good luck! This should take less than 5 minutes total! 🚀**
