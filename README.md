# SBEW Website — Editing Guide

Website for **Shree Balaji Engineering Works** — www.sbew.in

---

## 📸 How to Add a New Product (2 minutes)

### Step 1 — Upload the photo
1. Open the **images** folder in this repository
2. Click **Add file → Upload files**
3. Drag your photo in (JPG, under 300KB recommended — compress at tinypng.com if needed)
4. Name it simply, no spaces: `gear-blank.jpg` ✅  not `Gear Blank (1).jpg` ❌
5. Click **Commit changes**

### Step 2 — Add the product entry
1. Open the file **products.js**
2. Click the **pencil icon** (Edit)
3. Copy any existing block and paste it at the top of the list:

```
  {
    image: "images/gear-blank.jpg",
    name:  "Gear Blanks",
    desc:  "Close-tolerance blanks for gear cutting — EN8/EN24"
  },
```

4. Change the three lines to match your photo
5. **Keep the comma** after the closing `}`
6. Click **Commit changes**

The live website updates automatically in ~20 seconds.

---

## ✏️ How to Edit Text (contact, headings, etc.)

1. Open **index.html**
2. Click the pencil icon
3. Press **Ctrl+F** and search for the text you want to change
4. Edit it, commit changes

---

## 🗑️ How to Remove a Product

Open **products.js** → delete the whole block for that product (from `{` to `},`) → commit.

---

## 📁 Files in this repository

| File | What it is | Edit it? |
|---|---|---|
| `index.html` | The whole website | Only for text changes |
| `products.js` | Product gallery list | ✅ Yes — this is your main edit file |
| `images/` | All photos | ✅ Upload new photos here |
| `README.md` | This guide | No |

---

## 🆘 If something breaks

Every change is saved in GitHub's history. Go to the file → click **History** → click any older version → **Revert**. Nothing is ever lost.

Or send the products.js file to Claude and ask it to fix the error.
