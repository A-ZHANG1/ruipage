# ruipage

A simple academic homepage built with plain HTML/CSS, modeled after
[wd7ang.github.io](https://wd7ang.github.io/). All content uses placeholders —
replace text, images, and links with your own information.

## Structure

- `index.html` — main page (sidebar + sections)
- `assets/style.css` — styling

## Sections

- About Me
- 🔥 News
- 📝 Selected Publications
- 🚀 Selected Projects
- 🌍 Services
- 💻 Internships
- 🎖 Honors and Awards
- 📖 Educations

## 启动方法 / Getting Started

### 方式一：直接打开（最简单）
双击 `index.html` 即可在浏览器中查看。

### 方式二：本地起一个 HTTP 服务（推荐）

使用 Python（已自带）:
```powershell
cd ruipage
python -m http.server 8000
# 然后在浏览器访问 http://localhost:8000
```

使用 Node.js:
```powershell
cd ruipage
npx serve .
# 或者
npx http-server -p 8000
```

使用 VS Code：安装 **Live Server** 扩展 → 右键 `index.html` → `Open with Live Server`。

## Deploy to GitHub Pages

1. Push this repository to GitHub.
2. In the repo settings → Pages → choose `main` branch / root.
3. Visit `https://<your-username>.github.io/ruipage/`.

## Customize

- Replace `https://via.placeholder.com/...` images with your own under `assets/`.
- Update social links (email, GitHub, Scholar, etc.) in the sidebar.
- Edit each `<section>` in `index.html` with your real content.
