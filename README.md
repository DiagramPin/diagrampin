# 📍 DiagramPin

> **Pin Your Diagram Layouts in Code**

---

## 🌐 Live Demo

**👉 Try it now: [https://diagrampin.com](https://diagrampin.com)**

---

## 💡 Core Concept

> **"Manage positions in code!"**
>
> Drag tables → `@layout` auto-updates.
> Version control your layouts with Git!

---

## 🎬 Demo

| DBML Editor | Mermaid Editor |
|:-----------:|:--------------:|
| ![DBML Demo](docs/screenshots/dbml-demo.gif) | ![Mermaid Demo](docs/screenshots/mermaid-demo.gif) |
| Drag tables → @layout auto-update | ER diagram positioning |

---

## ✨ Features

DiagramPin adds **position locking** to code-rendered diagrams.

- 📌 Drag nodes → positions auto-save to code as `@layout` comments
- 🔄 Bidirectional sync between code and diagram
- 📦 Version control your layouts with Git

### Supported Formats

| Format | Type | Use Cases |
|--------|------|-----------|
| **DBML** | Database Markup | ERD, Schema Design |
| **Mermaid** | Diagram as Code | Flowcharts, ER, Sequence |

---

## 🚀 Quick Example

```dbml
// @layout x:100 y:100
Table users {
  id integer [pk]
  email varchar
}

// @layout x:400 y:100
Table posts {
  id integer [pk]
  user_id integer [ref: > users.id]
}
```

---

## ⚠️ Note

> This repository is for **issue tracking only**.
> Source code is maintained in a private repository.

Bug reports and feature requests are welcome!

👉 **[Open an Issue](https://github.com/DiagramPin/diagrampin/issues)**
