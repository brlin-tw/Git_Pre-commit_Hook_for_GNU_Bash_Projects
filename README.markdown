# 用於 GNU Bash 專案的 Git 提交版本前掛勾程式<br>Git Pre-commit Hook for GNU Bash Projects
[![Build Status of the Latest Revision of the Project](https://travis-ci.org/Lin-Buo-Ren/Git_Pre-commit_Hook_for_GNU_Bash_Projects.svg?branch=master)](https://travis-ci.org/Lin-Buo-Ren/Git_Pre-commit_Hook_for_GNU_Bash_Projects)  
Check all changes in GNU Bash script on commit!

<https://github.com/Lin-Buo-Ren/Git_Pre-commit_Hook_for_GNU_Bash_Projects>

## Deprecation Notice

This project has been superseded by [pre-commit - A framework for managing and maintaining multi-language pre-commit hooks](https://pre-commit.com/), which is far more flexible and feature-rich than this project can provide.  It is recommended to use that instead.

A sample pre-commit configuration and Travis CIhas applied to this project for reference, checkout the .pre-commit-config.yaml and .travis.yml file for more info.

## 作者<br>Author

林博仁 et. al.

## 智慧財產授權條款<br>Intellectual Property License
GPLv3

## 如何使用本軟體<br>How to Use This Software
0. Install [ShellCheck](https://www.shellcheck.net/), and make sure `shellcheck` is in your `PATH` environment variable
1. Add this Git repository as your project's sub-module
2. Create a symbolic link to `pre-commit.bash` from `.git/hooks/pre-commit`
3. Profit!  All your bash scripts with `.bash` filename extension in staging area will be automatically checked by ShellCheck during commit attempt, commit will fail if any warnings or errors occurred.

