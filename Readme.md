#Homework 1
```bash
  1  mkdir new_project
  2  ls -l
  3  cd new_project
  4  git init
  5  nano new.txt
  6  nano .gitignore
  7  git config --user.name "Max Limonau"
  8  git config user.name "Max Limonau"
  9  git config user.email "m.limonau@gmail.com"
  10  git status
  11  git add --all
  12  git status
  13  git commit
  14  git log --oneline
  15  nano new.txt
  16  git status
  17  add new.txt
  18  git add new.txt
  19  git status
  20  git commit
  21  git log --oneline
  22  free
  23  tree
  24  sudo apt install tree
  25  tree
  26  ls -l
  27  git branch dev
  28  git checkout dev
  29  git log --all
  30  sudo shutdown -h now
  31  ls -la
  32  cd new_project
  33  git branch -a
  34  git log --oneline
  35  git log --all
  36  git log --oneline
  37  nano new3.txt
  38  git status
  39  add new3.txt
  40  dit add new3.txt
  41  git add new3.txt
  42  git status
  43  git commit -m "Commit 1 dev branch"
  44  date >>new3.txt
  45  nano new3 txt
  46  nano new3.txt
  47  git status
  48  git add --all
  49  git status
  50  git commit -m "Commit 2 dev branch"
  51  git log --oneline
  52  git branch features/do_one
  53  git branch -a
  54  git checkout features/do_one
  55  git branch -a
  56  git log --all
  57  git log --oneline
  58  nano new3.txt
  59  git status
  60  git add new3.txt
  61  git commit -m "Commit 1 features/do_one branch"
  62  git log --oneline
  63  git "Commit 1 features/do_one branch"
  64  [features/do_one bfc0390] Commit 1 features/do_one branch
  65   1 file changed, 2 insertions(+)
  66  limon@imeserv:~/new_project$ git log --oneline
  67  bfc0390 (HEAD -> features/do_one) Commit 1 features/do_one branch
  68  1d86f5e (dev) Commit 2 dev branch
  69  a4304a5 Commit 1 dev branch
  70  7ad7f43 (master) Commit 2
  71  029cefd Commit 1
  72  limon@imeserv:~/new_project$ git branch -a
  73    dev
  74  * features/do_one
  75    master
  76  limon@imeserv:~/new_project$
  77  git checkout master
  78  git branch hotfix/we_gonna_die
  79  git checkout hotfix/we_gonna_die
  80  git branch -a
  81  nano new4.txt
  82  git status
  83  git add new4.txt
  84  git commit -m "Commit 1 hotfix branch"
  85  git log --oneline
  86  git log --all
  87  sudo shutdown -h now
  88  cd new_project
  89  git log --oneline
  90  git log --all
  91  git log
  92  git branch -a
  93  git checkout dev
  94  git branch -a
  95  git rebase master
  96  git status
  97  git checkout master
  98  git merge dev
  99  git checkout hotfix/we_gonna_die
  100  git rebase master
  101  git checkout master
  102  git merge hotfix/we_gonna_die
  103  gir status --oneline
  104  gir log --oneline
  105  git log --oneline
  106  history
  ```
