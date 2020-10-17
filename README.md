# Rocket Todo SX пример от lib

Чтобы запустить проект неоходимо установить `diesel` и `sqlite3`.

Далее примеры для установки  `sqlite3`

 
  * **Windows:** // !сначала скачайте `sqlite3` из <a href="https://www.sqlite.org/2020/sqlite-dll-win64-x64-3330000.zip">оф сайта</a>. Потом распакуйте в любой директории.Далее Пуск -> Developer Command Prompt for VS 2019 (тут должно быть установлено vs) `lib /folderSqlite3/def:sqlite3.def /machine:X64 /folderSqlite3/out:sqlite3.lib ` .
  Далее вставьте готовы файлы в этих директориях: `C:\Users\%username%\.rustup\toolchains\nightly-x86_64-pc-windows-msvc\lib\rustlib\x86_64-pc-windows-msvc\lib` и `C:\Users\%username%\.rustup\toolchains\stable-x86_64-pc-windows-msvc\lib\rustlib\x86_64-pc-windows-msvc\lib`.
  Далее уже можно запустить `cargo run`.

  * **OS X:** `brew install sqlite`
  * **Debian/Ubuntu:** `apt-get install libsqlite3-dev`
  * **Arch:** `pacman -S sqlite`
