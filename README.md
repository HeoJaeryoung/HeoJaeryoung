## new repository 셋팅하기
1. new repository 생성
2. git bash 열기
3. git init
4. touch .gitignore
5. <<gitignore 복붙하기>>
"""
################################
# OS / Editor
################################
.DS_Store
Thumbs.db

################################
# Python
################################
__pycache__/
*.py[codz]
*.pyo
*.pyd
.venv/
venv/
env/
.env

################################
# Node / Frontend
################################
node_modules/
dist/
build/

################################
# Jupyter
################################
.ipynb_checkpoints/

################################
# IDE
################################
.vscode/
.idea/

################################
# Data / Documents (중요)
################################
data/
*.csv
*.xlsx
*.xls
*.docx
*.hwpx
*.pdf

################################
# Google Drive pointer files
################################
*.gdoc
*.gsheet
*.gslides

################################
# Logs / Temp
################################
*.log
*.tmp
"""

6. git add .gitignore README.md
7. git commit -m "Initial commit with gitignore"
8. git status      
9. git add .         
10. git commit -m "Add project files"
11. git push -u origin main
