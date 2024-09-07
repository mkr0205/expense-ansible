############### create a new repository on the command line ###############
echo "# expense-ansible" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/mkr0205/expense-ansible.git
git push -u origin main


############### push an existing repository from the command line ###############
git remote add origin https://github.com/mkr0205/expense-ansible.git
git branch -M main
git push -u origin main
