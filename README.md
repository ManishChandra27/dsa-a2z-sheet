# A2Z DSA Sheet Tracker

A dark-theme tracker for ** A2Z DSA Sheet** with **455 problems across 18 steps**.

* Checkbox for every problem; progress is saved in the browser's `localStorage`
* Overall and step-wise progress bars
* LeetCode and GFG links for every problem, along with difficulty (**Easy / Medium / Hard**)
* Search functionality
* **Pending / Done / Revise** filters
* Difficulty filter
* Progress **Backup / Restore** using JSON copy-paste

Everything is contained in a single file (`index.html`), so there is **no build process or npm installation required**.

## Run Locally

Simply open `index.html` in your browser by double-clicking it.

## Host on GitHub Pages

1. Create a new repository on GitHub named `a2z-tracker` and make it **public**.

2. Open the terminal inside this folder and run:

```bash
git init
git add .
git commit -m "Add A2Z tracker"
git branch -M main
git remote add origin https://github.com/<your-username>/a2z-tracker.git
git push -u origin main
```

3. In your repository, go to **Settings > Pages**.

4. Under **Source**, select:

   * **Deploy from a branch**
   * **Branch:** `main`
   * **Folder:** `/ (root)`

   Then click **Save**.

5. After 1–2 minutes, your site should be live at:

```text
https://<your-username>.github.io/a2z-tracker/
```

## Importing Progress from the Old Link

`localStorage` is separate for each website/domain, so your existing progress will **not automatically appear** on the new GitHub Pages URL.

To transfer your progress:

1. Open the old page and click **Backup**.
2. Copy the generated text.
3. Open the new GitHub Pages website.
4. Click **Backup**, paste the copied text, and click **Restore**.

Your previous progress should now be restored.


