# ojsTerminalBio - UI Templates & Assets

Cyberpunk-themed academic portfolio UI files for [ojsTerminalBio](https://pypi.org/project/ojsTerminalBio/).

## 📦 Installation

### Option 1: Install via PyPI (Recommended)
```bash
pip install ojsterminalbio
ojsterminalbio init-db
ojsterminalbio runserver
```

### Option 2: Use these templates with custom backend
Clone this repo and copy templates/static to your project.

---

## 📁 Structure

```
ojsterminalbio/
├── templates/
│   ├── admin/          # Admin panel UI
│   │   ├── base.html
│   │   ├── dashboard.html
│   │   ├── profile.html
│   │   ├── page_editor.html
│   │   └── ...
│   └── public/         # Public website UI
│       ├── base.html
│       ├── index.html
│       ├── about.html
│       ├── research.html
│       └── ...
└── static/
    └── css/
        └── tailwind.css
```

---

## 🚀 Quick Start

### One-Click Setup

**macOS/Linux:**
```bash
chmod +x setup.sh
./setup.sh
```

**Windows:**
```cmd
setup.bat
```

### Manual Installation
```bash
# Install package
pip install ojsterminalbio

# Initialize database
ojsterminalbio init-db

# Run server
ojsterminalbio runserver
```

**Access:** http://localhost:7777

**Admin Login:**
- Email: `admin@example.com`
- Password: `admin123`

---

## ⚙️ Configuration

```bash
export OJSTB_SECRET_KEY="your-secret-key"
export OJSTB_DEFAULT_ADMIN_EMAIL="your@email.com"
export OJSTB_DEFAULT_ADMIN_PASSWORD="secure-password"
export OJSTB_DATABASE_URL="sqlite:///./ojsterminalbio.db"
```

---

## 🎨 Features

- Cyberpunk terminal-style theme
- Matrix rain background effect
- Light/Dark mode toggle
- Responsive design
- Dynamic page editor
- Customizable colors (Cyan, Pink, Amber, Green)

---

## 📄 License

MIT License

## 👤 Author

Sanasam Ranbir Singh - [IIT Guwahati](https://www.iitg.ac.in)
