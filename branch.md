# 4. Ветвление

LICENSE: [MIT](./license.md)

<img src="./img/git_logo.png" width="100"/>

GIT logo by Jason Long - <http://git-scm.com/downloads/logos>, license: [CC BY 3.0](https://creativecommons.org/licenses/by/3.0)

---
Ветвление это мощные инструмент и одна из главных фич git'а поскольку позволяет вам быстро создавать и переключатся между различным ветками вашего репозитория. Главная концепция ветвления состоит в том что вы можете откланяться от основной линии разработки и продолжать работу независимо от нее, не вмешиваясь в основную линию. Ветка всегда указывает на последний коммит в ней, а HEAD указывает на текущую ветку

Для создания ветки используется команда `git branch [<options>] <branch_name>`

Для переключения на ветку используйте `git checkout <branch_name>`. Также вы можете создать ветку выполнив `git checkout -b <new_branch_name>`

Для слияния веток используется команда `git merge`

`git rebase` — перебазирование. В этом случае коммиты вашей ветки накладываются поверх текущего состояния указанной ветки.

---
[прошлая глава](./work_with_git.md) | [на главную](./README.md) | [следующая глава](./branch_methods.md)