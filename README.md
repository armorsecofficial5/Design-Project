# Design-Project

## 1st Phase Setup Instructions (Enviornment Setup)

1. Create a Python virtual environment:

python3 -m venv venv
source venv/bin/activate

2. Install the main data science libraries:

python -m pip install --upgrade pip
python -m pip install pandas numpy scikit-learn tensorflow xgboost matplotlib seaborn requests nvdlib

3. Create the project folders:

mkdir -p data/raw data/processed models notebooks src outputs


4. Use Git and ignore files you do not want to track:

git init
cat > .gitignore <<'EOF'
venv/
data/raw/
models/
__pycache__/
*.py[cod]
.ipynb_checkpoints/
.DS_Store
EOF

## Notes

- Keep raw data in `data/raw/`.
- Save cleaned data in `data/processed/`.
- Store notebooks in `notebooks/` and code in `src/`.
- Put outputs and reports in `outputs/`.

## 2nd Phase

