# Blog Project

A responsive, Django-based blogging web application. Users can create, read, update, and delete blog posts, upload media, and manage categories.

## Features
- **CRUD Operations**: Create, read, update, and delete blog posts.
- **Media Uploads**: Attach images to blog posts (handled via Pillow).
- **Admin Panel**: Manage posts, users, and comments easily using Django's built-in admin interface.
- **Responsive UI**: Styled for ease of use across mobile, tablet, and desktop devices.

## Tech Stack
- **Backend**: Django 5.x, Python
- **Database**: SQLite3 (default)
- **Frontend**: HTML5, CSS3, JavaScript

## Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/dinesh262007/Blog-Project.git
   cd Blog-Project
   ```

2. **Set up a virtual environment and activate it:**
   ```bash
   python -m venv venv
   # On Windows:
   .\venv\Scripts\activate
   # On macOS/Linux:
   source venv/bin/activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Apply database migrations:**
   ```bash
   python manage.py migrate
   ```

5. **Create a superuser (optional, for admin panel access):**
   ```bash
   python manage.py createsuperuser
   ```

6. **Start the development server:**
   ```bash
   python manage.py runserver
   ```
   Open your browser and navigate to `http://127.0.0.1:8000/`.
