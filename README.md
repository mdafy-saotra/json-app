# How to Export Your CommCare App Source

## Step 1 — Find your App ID

Go to your app in CommCare HQ. Your App ID is visible in the URL:
```
https://www.commcarehq.org/a/mining-app/apps/view/d63ae459d63418c4566776a8c5c546c2/
```

In this example:
- **PROJECT_NAME** = `mining-app`
- **APP_ID** = `d63ae459d63418c4566776a8c5c546c2`

---

## Step 2 — Open the App Source URL

Paste the following URL into your browser, replacing `[PROJECT_NAME]` and `[APP_ID]` with your own values:
```
https://www.commcarehq.org/a/[PROJECT_NAME]/apps/source/[APP_ID]/
```

**Example with real values:**
```
https://www.commcarehq.org/a/mining-app/apps/source/d63ae459d63418c4566776a8c5c546c2/
```

---

## Step 3 — Save the result as a JSON file

1. The browser will display a large block of raw JSON text
2. Select all (`Ctrl+A` on Windows, `Cmd+A` on Mac)
3. Copy it (`Ctrl+C` / `Cmd+C`)
4. Open **Notepad** (Windows) or any plain text editor
5. Paste the content (`Ctrl+V` / `Cmd+V`)
6. Save the file with a `.json` extension

**Example filename:**
```
mining_source.json
```

> ✅ You now have your CommCare app source exported and ready to use.
