# Modify a file
echo "Content for day $(date)" >> daily-commit.txt

# Stage changes
git add daily-commit.txt

# Commit changes
git commit -m "Daily commit for $(date +%Y-%m-%d)"

# Push to GitHub
git push origin main
