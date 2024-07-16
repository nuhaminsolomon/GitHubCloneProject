echo "# GitHubCloneProject" > README.md
echo "This project simulates a collaborative workflow with branching and merging in Git." >> README.md
git add README.md
git commit -m "Add README.md with project description"
git clone <REPOSITORY-URL>
cd GitHubCloneProject
git checkout -b feature-greeting
echo "This is a new feature." > feature.txt
git add feature.txt
git commit -m "Add feature description"
