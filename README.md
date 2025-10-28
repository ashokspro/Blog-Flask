# 📝 Flask Blog Application

A full-featured blog platform built with Python and Flask, featuring rich text editing, user authentication, and role-based access control. Create, manage, and share your thoughts with a clean, modern interface powered by CKEditor and Bootstrap.

![Flask Blog](https://img.shields.io/badge/flask-3.0.0-green.svg)
![Python](https://img.shields.io/badge/python-3.8+-blue.svg)

## ✨ Features

### 📰 Blog Management
- **Rich Text Editor** – CKEditor integration for formatting blog posts with images, links, and styling
- **CRUD Operations** – Create, Read, Update, and Delete blog posts
- **Categories & Tags** – Organize posts with categories and tags
- **Featured Posts** – Highlight important blog posts on the homepage

### 👥 User Management
- **User Authentication** – Secure registration and login system
- **Role-Based Access Control** – Admin, Author, and Reader roles
- **User Profiles** – Customizable user profiles with avatars
- **Author Pages** – View all posts by a specific author


### 🎨 User Interface
- **Responsive Design** – Mobile-friendly Bootstrap 5 interface
- **Pagination** – Easy navigation through multiple posts

## 🏗️ Tech Stack

| Category | Technologies |
|----------|-------------|
| **Backend** | Python 3.8+, Flask 3.0 |
| **Database** | SQLite with SQLAlchemy ORM |
| **Frontend** | HTML5, CSS3, Bootstrap  |
| **Rich Text Editor** | CKEditor 5 |
| **Authentication** | Flask-Login, Werkzeug Security |
| **Forms** | Flask-WTF, WTForms |

## 🚀 Getting Started

### Prerequisites
- Python 3.8 or higher
- pip (Python package manager)
- Git

### 1. Clone the Repository
```bash
git clone https://github.com/ashokspro/Blog-Flask.git
cd Blog-Flask
```

### 2. Create a Virtual Environment
```bash
# On Windows
python -m venv venv
venv\Scripts\activate

# On macOS/Linux
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```


### 4. Run the Application
```bash
python app.py
```
Or:
```bash
flask run
```

### 5. Access the Application
Open your browser and navigate to:
👉 **http://127.0.0.1:5000**


## 📸 Screenshots

### Homepage
![Homepage](screenshots/homepage.png)
*Clean, modern blog homepage with featured posts*

### Create Post
![Create Post](screenshots/create-post.png)
*Rich text editor with CKEditor for writing posts*

### Admin Dashboard
![Admin Dashboard](screenshots/admin-dashboard.png)
*Comprehensive admin panel for managing content*

### Blog Post View
![Post View](screenshots/post-view.png)
*Individual post page with comments section*

## 🔒 Security Features

- **Password Hashing** – Werkzeug security for secure password storage
- **CSRF Protection** – Flask-WTF CSRF tokens on all forms
- **Login Required Decorators** – Protected routes for authenticated users
- **Role-Based Access** – Custom decorators for admin/author routes




## 🧠 Future Enhancements

- [ ] 📧 **Email Integration** – Newsletter subscriptions and notifications
- [ ] 🔍 **Advanced Search** – Full-text search with Elasticsearch
- [ ] 📱 **REST API** – JSON API for mobile apps
- [ ] 🌐 **Internationalization** – Multi-language support
- [ ] 📊 **Analytics Dashboard** – Post views, popular content
- [ ] 🔐 **OAuth Integration** – Login with Google/GitHub/Twitter
- [ ] 💾 **Cloud Storage** – AWS S3 for image uploads
- [ ] 📝 **Markdown Support** – Alternative to CKEditor
- [ ] 🎨 **Theme Customization** – User-selectable themes
- [ ] 📤 **Import/Export** – Backup and restore blog data
- [ ] 🤖 **Anti-Spam** – reCAPTCHA integration
- [ ] 📈 **SEO Optimization** – Meta tags, sitemap generation

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. **Fork the repository**
2. **Create a feature branch**
```bash
   git checkout -b feature/amazing-feature
```
3. **Commit your changes**
```bash
   git commit -m "Add: amazing feature description"
```
4. **Push to the branch**
```bash
   git push origin feature/amazing-feature
```
5. **Open a Pull Request**

### Code Style Guidelines
- Follow PEP 8 for Python code
- Use meaningful variable and function names
- Add docstrings to functions and classes
- Write unit tests for new features
- Update documentation as needed

## 🐛 Known Issues

- [ ] Image uploads may be slow for large files
- [ ] CKEditor toolbar may overflow on small screens
- [ ] Comment notifications not implemented yet
- [ ] Search only works on published posts

## 📝 Changelog

### Version 1.0.0 
- ✨ Initial release
- 🔐 User authentication system
- 📝 Blog post CRUD operations
- 💬 Comments system
- 👥 Role-based access control
- 🎨 CKEditor integration
- 📱 Responsive Bootstrap design

## 📚 Dependencies
```txt
Flask==3.0.0
Flask-SQLAlchemy==3.0.5
Flask-Login==0.6.3
Flask-WTF==1.2.1
WTForms==3.1.1
email-validator==2.1.0
Werkzeug==3.0.1
python-dotenv==1.0.0
```

## 💬 Contact & Support

### 👨‍💻 Developer
**Ashokkumar S**  
📍 Tamil Nadu, India  
📧 ashokshanmugam2006@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/ashokkumar0306/) | [GitHub](https://github.com/ashokspro)

### 🆘 Support
- 📝 [Report Issues](https://github.com/ashokspro/Blog-Flask/issues)
- 💬 [Discussions](https://github.com/ashokspro/Blog-Flask/discussions)
- 📧 Email for direct support

## 🌟 Acknowledgments

- **Flask** – Micro web framework
- **CKEditor** – Rich text editor
- **Bootstrap** – Frontend framework
- **SQLAlchemy** – Python SQL toolkit

## ⭐ Show Your Support

If you found this project helpful, please give it a ⭐ on GitHub!

---

<p align="center">
  Made with ❤️ by <a href="https://github.com/ashokspro">Ashokkumar S</a>
</p>

<p align="center">
  <sub>Powered by Flask • Styled with Bootstrap • Enhanced with CKEditor</sub>
</p>
