echo "Команда checkout используется в Git, чтобы:" > branch_help.md
echo "* переключиться на произвольную существующую ветку (git checkout branch-name)" >> branch_help.md
echo "* создать новую ветку от текущей (git checkout -b new-branch-name)" >> branch_help.md
echo '- [Ветвление](./branch_help.md)' >> README.md

git add .
git commit -m "Добавлена информация о ветвлении"