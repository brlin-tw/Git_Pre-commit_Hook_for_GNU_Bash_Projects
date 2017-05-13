# 用於 GNU Bash 專案的 Git 提交版本前掛勾程式<br>Git Pre-commit Hook for GNU Bash Projects
## 作者
林博仁 et. al.

## 智慧財產授權條款<br>Intellectual Property License
GPLv3

## 如何使用本軟體<br>How to Use This Software
0. Install [ShellCheck](https://www.shellcheck.net/), and make sure `shellcheck` is in your `PATH` environment variable
1. Add this Git repository as your project's sub-module
2. Create a symbolic link to `Pre-commit Script.bash` from `.git/hooks/pre-commit`
3. Profit!  All your bash scripts with `.bash` filename extension in staging area will be automatically checked by ShellCheck during commit attempt, commit will fail if any warnings or errors occurred.

