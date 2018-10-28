# far2l-deb

**Readme in english is below**

.deb пакеты [far2l](https://github.com/elfmz/far2l) (linux порт [Far Manager 2](http://www.farmanager.com/index.php?l=ru), включая FTP/SFTP/WebDAV/SMB клиент [far-gvfs](https://github.com/cycleg/far-gvfs)) для Ubuntu/Mint.

Если нет пакета для нужного дистрибутива или архитектуры, вы можете попробовать собрать пакет самостоятельно, используя скрипт `make_far2l_deb.sh` (ветка master) или `make_far2l_deb_tty.sh` (ветка backend-separation).

По умолчанию far2l работает как GUI-приложение на wxWidgets. На ветке backend-separation поддерживается экспериментальная работа в консоли, запускается по `far2lc`. Запускать в консоли просто как `far2l` или `far2l --tty` не следует, могут быть проблемы с монтированием gvfs.

putty не передает часть горячих клавиш, в терминале wal commander с этим лучше. Или можно попробовать вот этот форк: https://github.com/adizero/putty-X (у кого получится собрать, поделитесь, пожалуйста, бинарниками). 

---

.deb packages of [far2l](https://github.com/elfmz/far2l) ([Far Manager 2](http://www.farmanager.com/index.php?l=en) linux port, including [far-gvfs](https://github.com/cycleg/far-gvfs) plugin as FTP/SFTP/WebDAV/SMB client) for Ubuntu/Mint.

If there is no package for your OS release or architecture, you may try to build package yourself using `make_far2l_deb.sh` (for master branch) or `make_far2l_deb_tty.sh` (for backend-separation branch).

far2l defaults to run as GUI app based on wxWidgets toolkit. As backend-separation branch is used, you can run `far2lс` to get very experimental console support; do not run `far2l` or `far2l --tty` in console directly to avoid gvfs mount problems.

putty fails to process some hotkeys, wal commander terminal works better. You may also try this fork: https://github.com/adizero/putty-X (please share your binaries if you manage to build it).

