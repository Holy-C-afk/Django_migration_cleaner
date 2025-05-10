# Django_migration_cleaner

This script helps clean up all Django migration `.py` files (except `__init__.py`) and `.pyc` files from your project.

## 🚀 How to Use

### Prerequisites

Make sure you have Python installed and your environment is set up for Django.

### Step 1: Clone the repository

git clone https://github.com/YOUR-USERNAME/django-migrations-cleaner.git

### Step 2: Run the script
Navigate to the directory where the script is saved, and run it using Python:

python clean_migrations.py

### Step 3: Confirm deletion

The script will ask for confirmation before it deletes migration and .pyc files. Type y to proceed or n to cancel.

⚠️ Warning
This script will permanently delete migration .py files and .pyc files, so use it with caution.

Customization
You can edit the script to fit your needs, e.g., to add specific directories to clean, or adjust how the confirmation works.
