# Git
* .gitignore not working:
    1. COMMIT ALL CHANGES!
    1. `git rm -r --cached .`
    1. `git add .`
    1. `git commit -m "fixed untracked files"`
* show commits on old branch that are missing from dev: `git log --no-merges old_branch ^dev`
* Set origin for a non-tracking branch: ` git branch -u origin/dev`    
# PHP
# Cake
* `/bin/cake console`
    * `$p = Cake\ORM\TableRegistry::getTableLocator()->get('Pizza');`
# MySQL
* `select TABLE_NAME, COLUMN_NAME FROM information_schema.columns WHERE table_schema = 'foods' and COLUMN_NAME IN ('spicy', 'tastiness');`
* `mysqldump -u user dbname > dumpfile.sql -p` / `mysql -u user dbname < loadfile.sql -p`
# IDE
## Jetbrains
* Show current file in tree: alt + F1
