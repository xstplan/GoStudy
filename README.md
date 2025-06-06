
# GoStudy 学习喽

一个面向小学、初中、高中、大学不同阶段的常用学习工具箱。

本项目为纯 HTML 静态网页，使用 [Tailwind CSS](https://tailwindcss.com/) 。

---

## 在线仓库

[https://github.com/xstplan/GoStudy](https://github.com/xstplan/GoStudy)

---

## 功能

- 📚 目前包含 拼音表，九九乘法表，国际音标表，趣味数学，化学周期表
---

## 快速开始

### 1. 克隆项目

```bash
git clone https://github.com/xstplan/GoStudy.git
cd GoStudy
````

### 2. 安装 Tailwind CSS CLI（可选）

如果未全局安装 Tailwind CSS，可以在项目内安装：

```bash
npm install -D tailwindcss
```

### 3. 构建 Tailwind CSS（开发时自动编译）

使用下方命令，实时监听源文件变更并自动生成 CSS：

```bash
npx @tailwindcss/cli -i ./src/css/input.css -o ./src/css/output.css --watch
```

### 4. 打开网页预览

直接用浏览器打开 `src/index1.html` 或 `src/Home.html` 等页面即可浏览，无需服务端！

---

## 目录结构

```text
GoStudy/
├── src/
│   ├── css/
│   │   ├── input.css
│   │   └── output.css
│   ├── js/
│   │   ├── katex/
│   │   │   └── ...（KaTeX 相关文件）
│   │   └── html2canvas.min.js
│   ├── middle/
│   │   └── ...（中学阶段功能页面，可根据实际情况添加文件）
│   ├── primary/
│   │   └── ...（小学阶段功能页面，可根据实际情况添加文件）
│   ├── coming-soon.html 
│   ├── home-middle.html
│   ├── home-primary.html
│   ├── Home.html （首页）
│   └── index1.html
├── .gitattributes
├── .gitignore
├── LICENSE
├── package-lock.json
├── package.json
└── README.md
```

> **说明**：
>
> * `src/css/` 下包含 Tailwind 源文件 (`input.css`)、生成后的样式文件 (`output.css`) 。
> * `src/js/` 下包含数学公式渲染的 KaTeX 目录和 `html2canvas.min.js`。
> * `src/middle/` 与 `src/primary/` 文件夹分别用于存放中学与小学阶段的功能页面（示例中未显示具体文件，可自行补充）。
> * 根目录下还包括 Git 配置、许可证、npm 配置和 README。

---


