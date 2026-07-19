# switchVLESS - Vless Proxy-Client for Nintendo Switch

<a name="english"></a>
## 🇬🇧 English

**switchVLESS** is a homebrew application for the Nintendo Switch that serves as a frontend for VLESS proxy/VPN protocols. It provides an intuitive console-based interface to manage your VLESS subscription links, update server lists, and configure DNS routing directly from your console.

### ✨ Features

- **Native On-Screen Keyboard Integration:** Easily input or paste your VLESS subscription URLs using the Switch's native OS keyboard (`swkbd`).
- **Persistent Storage:** Your subscription link is automatically saved to the SD card (`sdmc:/switch/MyVLESS/sub.txt`) so you don't have to enter it again after rebooting.
- **Server Selection:** Fetch and parse available servers from your subscription URL and navigate through them using the D-Pad.
- **DNS Toggle:** Quickly switch between Local DNS and Server (VPN) DNS modes.
- **Lightweight & Fast:** Written in standard C++ using `libnx` console UI for instant compilation and zero overhead.

### 🎮 Controls

* **[ A ]** - Open the native keyboard to enter/change the subscription link.
* **[ X ]** - Update the server list from the provided link.
* **[ Y ]** - Toggle between Local DNS and VPN DNS modes.
* **[ + ]** - Connect / Disconnect the proxy.
* **[ D-Pad Up/Down ]** - Navigate through the parsed server list.
* **[ - ]** - Exit the application.

### ⚠️ Disclaimer

This is a frontend proxy client template. For full proxy routing, it is meant to interface with a background sysmodule or a local core proxy (like Xray-core / sing-box compiled for AArch64) running on `127.0.0.1:1080`.

---

<a name="русский"></a>
## 🇷🇺 Русский

**switchVLESS** — это homebrew приложение для Nintendo Switch, которое служит клиентом (интерфейсом) для VLESS прокси/VPN протоколов. Оно предоставляет интуитивно понятный консольный интерфейс для управления ссылками на подписки VLESS, обновления списков серверов и настройки маршрутизации DNS прямо с вашей консоли.

### ✨ Возможности

- **Нативная экранная клавиатура:** Удобный ввод или вставка ссылок на подписки VLESS с помощью встроенной клавиатуры Switch (`swkbd`).
- **Сохранение данных:** Ваша ссылка на подписку автоматически сохраняется на SD-карту (`sdmc:/switch/MyVLESS/sub.txt`), поэтому её не нужно вводить заново после перезагрузки.
- **Выбор сервера:** Загрузка и парсинг доступных серверов из вашей ссылки на подписку с удобной навигацией с помощью крестовины (D-Pad).
- **Переключение DNS:** Быстрое переключение между режимами локального DNS и серверного DNS (VPN).
- **Легкость и скорость:** Написано на стандартном C++ с использованием консольного UI `libnx` для мгновенной компиляции и отсутствия задержек.

### 🎮 Управление

* **[ A ]** - Открыть системную клавиатуру для ввода/изменения ссылки на подписку.
* **[ X ]** - Обновить список серверов по указанной ссылке.
* **[ Y ]** - Переключить режим DNS (Локальный / VPN).
* **[ + ]** - Подключить / Отключить прокси.
* **[ Крестовина Вверх/Вниз ]** - Навигация по загруженному списку серверов.
* **[ - ]** - Выйти из программы.


### ⚠️ Примечание

Это шаблон клиентского интерфейса прокси. Для полноценной маршрутизации трафика предполагается его работа в связке с фоновым системным модулем (sysmodule) или локальным ядром (например, Xray-core / sing-box, скомпилированным под архитектуру AArch64), работающим на `127.0.0.1:1080`.
