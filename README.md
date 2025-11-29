# 📍 DiagramPin

> **Pin Your Diagram Layouts in Code**

A powerful diagram editor that supports DBML and Mermaid with automatic position locking. Create, edit, and maintain diagram layouts that stay consistent in your codebase.

---

## 🌐 Live Demo

**👉 Try it now: [https://diagrampin.com](https://diagrampin.com)**

Experience the power of position-locked diagrams directly in your browser!

---

## ✨ Features

### 📌 Position Locking
- Lock node positions directly in your code using `@layout` annotations
- Positions persist across code changes and team collaboration
- Never lose your carefully arranged diagram layout again

### 🎯 DBML Support
- Full Database Markup Language support
- Visualize database schemas as Entity-Relationship Diagrams
- Perfect for database design and documentation

### 🔄 Mermaid Support
- Flowcharts, sequence diagrams, ER diagrams, and more
- Complete Mermaid syntax support
- Ideal for system architecture and process flows

### 💾 Auto Save
- Automatic layout persistence
- No manual save required
- Seamless editing experience

### 🎨 Intuitive Interface
- Clean, modern UI
- Drag-and-drop positioning
- Real-time preview

---

## 🚀 Use Cases

### Database Schema Design
Design your database schema with DBML, visualize it as an ERD, and lock table positions for consistent documentation across your team.

```dbml
Table users {
  id integer [primary key]
  username varchar
  email varchar
}

Table posts {
  id integer [primary key]
  user_id integer [ref: > users.id]
  title varchar
  content text
}

@layout {
  users: { x: 100, y: 100 }
  posts: { x: 400, y: 100 }
}
```

### System Architecture
Create system diagrams with Mermaid and maintain layout consistency across iterations.

```mermaid
flowchart LR
    A[Client] --> B[Load Balancer]
    B --> C[Server 1]
    B --> D[Server 2]
    C --> E[Database]
    D --> E

@layout {
  A: { x: 50, y: 200 }
  B: { x: 250, y: 200 }
  C: { x: 450, y: 150 }
  D: { x: 450, y: 250 }
  E: { x: 650, y: 200 }
}
```

### Technical Documentation
Keep your documentation diagrams clean and consistent with locked layouts.

---

## 📸 Screenshots

### DBML Editor
![DBML Demo](docs/screenshots/dbml-demo.gif)
*Design database schemas with automatic ERD generation and position locking*

### Mermaid Editor
![Mermaid Demo](docs/screenshots/mermaid-demo.gif)
*Create flowcharts and diagrams with maintained layouts*

---

## 🎯 Why DiagramPin?

Most diagram tools don't preserve your carefully arranged layouts when you update the code. DiagramPin solves this by:

- ✅ Storing positions directly in your code
- ✅ Maintaining layouts across code changes
- ✅ Enabling team collaboration with consistent diagrams
- ✅ Supporting version control for both content and layout

---

## 🛠️ Supported Formats

| Format | Description | Use Cases |
|--------|-------------|-----------|
| **DBML** | Database Markup Language | Database schema design, ERD creation |
| **Mermaid** | Diagram as Code | Flowcharts, sequence diagrams, system architecture |

---

## 📖 Documentation

- **Website**: [https://diagrampin.com](https://diagrampin.com)
- **Live Editor**: Try it instantly without installation
- **Examples**: See sample diagrams on the website

---

## 💬 Feedback & Support

### Report Issues
Found a bug or have a feature request? [Open an issue](https://github.com/DiagramPin/diagrampin/issues)

### Questions
Have questions? [Ask in Discussions](https://github.com/DiagramPin/diagrampin/discussions)

---

## ⚠️ Note

This repository is for **project information and issue tracking only**. The actual source code is maintained in a private repository.

**We do not accept pull requests** for code contributions. However, we welcome:
- 🐛 Bug reports
- ✨ Feature requests
- 📖 Documentation improvements
- 💬 General questions and feedback

---

## 🔗 Links

- 🌐 **Live Demo**: [https://diagrampin.com](https://diagrampin.com)
- 📧 **Issues**: [GitHub Issues](https://github.com/DiagramPin/diagrampin/issues)
- 💬 **Discussions**: [GitHub Discussions](https://github.com/DiagramPin/diagrampin/discussions)

---

## 📄 License

DiagramPin is a proprietary software. This repository is for community engagement and issue tracking only.

---

<div align="center">

**Made with ❤️ for developers who love clean diagrams**

[Try DiagramPin Now](https://diagrampin.com) | [Report Issue](https://github.com/DiagramPin/diagrampin/issues/new)

</div>
