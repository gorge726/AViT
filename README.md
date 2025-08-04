# AViT
🎧 AViT-інструмент для генерації музичних відео з кільцевим спектрумом (Web + Telegram + FFmpeg + WASM/WebGL)

Це портативне технічне рішення, що поєднує в собі веб-інтерфейс, Telegram-бот, FFmpeg-процесинг, візуалізацію аудіо, WASM/WebGL, структуру збірки, а також готовність до розширення функціоналу.

AViT/
├── assets/
│   ├── styles.css
│   ├── script.js
│   └── AVTTool.wasm
├── data/
│   └── log.txt
├── temp/
│   └── (тимчасові файли створюються під час роботи)
├── AVTTool.py
├── AVTTool.cpp
├── AVTTool.cs
├── AVTTool.wat
├── AVTTool.wasm
├── index.html
├── requirements.txt
├── tests/
│   └── test_AVTTool.py
├── AVTTool_backup.tar.gz
└── README.md

Деталі основних файлів:
* assets/ – статичні ресурси (CSS, JS, wasm).
* data/ – лог-файли.
* temp/ – тимчасові файли створюються під час роботи.
* AVTTool.py / .cpp / .cs – основні скрипти для різних середовищ.
* index.html – інтерфейс WebUI.
* AVTTool.wat / .wasm – WebAssembly модулі.
* requirements.txt – залежності для Python-версії.
* tests/ – юніт-тести.
* AVTTool_backup.tar.gz – резервна копія проєкту.
* README.md – опис проєкту.

Така структура забезпечує легкість у розгортанні та підтримці проєкту. Ви можете запускати будь-який із доступних режимів, дотримуючись відповідних команд збірки та запуску.


На жаль, я не можу зараз виконати компіляцію або тестування коду безпосередньо. Ви можете скористатися наведеними командами для збірки проєкту AViT локально на вашій машині.

Команди для збірки:
python -m py_compile AVTTool.py
g++ -std=c++17 -o AVTTool AVTTool.cpp
csc /target:winexe /out:AVTTool.exe AVTTool.cs
wat2wasm AVTTool.wat -o AVTTool.wasm

Команди для запуску тестів:
python -m unittest discover -s tests
./AVTTool
start AVTTool.exe
start index.html

Якщо виникнуть помилки під час збірки або запуску, будь ласка, надішліть логи для подальшої допомоги.

Siri, did it!
               ╱|、
              (˚ˎ 。7  
               |、˜〵          
               じしˍ,)ノ
              little bastard!
