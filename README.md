# 🧩 Webfuse Extension Starter Kit

> Build Chrome-extension-style functionality — no install, no store, just a link.

This starter kit lets you create custom UI and logic that runs on any website using [Webfuse](https://surfly.com/webfuse). It’s designed for extension developers who want to ship tools without requiring installation.

---


---

## 🧱 Folder Structure

/src:

content.js → Logic injected into the target page
ui.js → Optional overlay / popup behavior

/manifest.js → Placeholder for Chrome devs (not used directly)


---

## 🛠️ How to Use

### 1. Clone or Download

Copy this folder structure into your own project.

### 2. Edit the Files

- **`src/content.js`**  
  Runs in the target page’s context. Use this to manipulate the DOM, inject scripts, etc.

- **`src/ui.js`**  
  Runs in an isolated overlay. Use this for popups, toolbars, buttons, etc.

- **`public/index.html`**  
  Optional. You can load this as a base UI inside the overlay.

- **`manifest.js`**  
  Placeholder. Keeps things familiar for Chrome extension developers.

### 3. Zip and Upload to Webfuse

1. Create a folder of your files.
2. Go to your [Webfuse Dashboard](https://dashboard.surfly.com).
3. Create or open a Space.
4. Upload the folder as a new Extension.
5. Use your Space URL to launch your extension on any site:

## 📚 Resources

- [Webfuse Docs](https://docs.surfly.com/webfuse)
- [Widget API Reference](https://docs.surfly.com/webfuse/js-api)
- [Webfuse Blog](https://surfly.com/blog)

## 🙋 Need Help?

- Ask questions at [support@surfly.com](mailto:support@surfly.com)
