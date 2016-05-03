---
name: Необходимые приложения
---

Наименование | Ссылка | Использование в работе  |
--- | --- | ---  |
**ConEmu** | http://www.conemu.ru/ | управления консольными приложениями |
**GIT** | https://git-for-windows.github.io/ | хранение исходных файлов  |
**SourceTree** | https://www.sourcetreeapp.com/  |  IDE для GitFlow  |
**Ruby** | https://www.ruby-lang.org/ru/  | работа с Web клиентом 1С |
**Python** | https://www.python.org/downloads/  | работа с внешними обработками 1С  |
**Wget** | http://gnuwin32.sourceforge.net/packages/wget.htm  | автоматизированное скачивание пакетов и сервисов  |
**Pickles** | http://www.picklesdoc.com/  | автоматическое создание документации  |
**Pandoc** | http://pandoc.org/  | конвертер документов между форматами  |
**IrfanView** | http://www.irfanview.com/  | работа со скриншотами и текстмо в картинках  |
**Visual Studio Code** | https://code.visualstudio.com/  | IDE для работы с различными форматами исходных кодов  |
**Plant UML** | http://ru.plantuml.com/ | создатель графических схем метаданных 1С |
**Chocolatey Gui** | https://chocolatey.org/packages/ChocolateyGUI | графический установщик пакетов Windows  |
**Notepad++** | https://notepad-plus-plus.org/ | удобный "блокнот" для Windows  |
**VirtualBox** | https://www.virtualbox.org/ | виртуализированное окружение разработчика 1С |
**Vagrant** | https://www.vagrantup.com/ | автоматизация управления окружениями 1С  |
**Docker Machine** | https://docs.docker.com/machine/  | управление контурами проверки 1С  |
**Docker** | https://www.docker.com/  | пакетирование в конейтенеры сервисов 1С  |
**Docker Compose** | https://docs.docker.com/compose/install/  | управления связями контейнеров 1С  |

Примечание:

* вместе `Visual Studio Code` может использовать `Atom IDE` или `Sublime IDE` - подробней [в этом проекте](https://github.com/xDrivenDevelopment/1c-syntax)
* в `linux` недоступен `SourceTree` - поэтому придется использовать консольное приложение `git`
* при установке `GIT для Windows` важно установить флаг `Добавлять unix утилиты в %PATH%` - это избавит вас от проблем и "артефактов"

для удобства инсталятор сгруппирован в командный файл [расположенный на github](https://github.com/silverbulleters/vanessa-bootstrap/blob/master/tools/windows/env-install.cmd)
