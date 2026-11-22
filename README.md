# 🎵 YandexMusicIsland

Compact floating **Dynamic Island** for Yandex Music on Windows (WPF + Windows SMTC) — a single portable `.exe` with no installer or extra files.

Компактный плавающий **Dynamic Island** для Яндекс Музыки на Windows (WPF + Windows SMTC) — один `.exe`-файл без установки и лишних файлов.

---

## 🇬🇧 English

### ✨ Features
- **Compact & Expanded Views:** Mini pill with album art, track title, and live equalizer expands on hover and collapses smoothly when the cursor leaves.
- **Playback Controls:** Play/pause, next/previous track, and smooth interactive timeline seeking without stuttering.
- **Per-App Volume Control:** Volume slider and mute button control only the Yandex Music audio session (via `ISimpleAudioVolume`) without changing system volume.
- **Synced Lyrics:** Automatic lyrics lookup via `lrclib.net` with smooth auto-scroll and click-to-seek on any line.
- **Themes, Colors & Custom Background:**
  - 4 built-in themes: **Yandex**, **Neon**, **Light**, **Ocean**.
  - Color & preset editor: customize accent, background, and border colors in `#RRGGBB` / `R, G, B` or via a popup **HSV color wheel**, rename presets, or add your own.
  - **Custom Background (PNG / Animated GIF):** Set any PNG or animated GIF as the island background (saved in `%LocalAppData%\YandexMusicIsland`).
- **Free Screen Placement:** Drag the island anywhere on screen or pick an exact spot from Settings (position is saved between launches).
- **Custom `.exe` Support:** Select any Yandex Music `.exe` path manually in Settings (works with official, custom, or modified builds).
- **Lightweight:** Render loop pauses automatically when music is paused or hidden; album art and GIF frames are downscaled in memory.

### 🚀 Usage
1. Download `YandexMusicIsland.exe` from **Releases**.
2. Run it — the island appears on screen and adds a tray icon.
3. All settings, presets, and window coordinates are stored in `HKCU\Software\YandexMusicIsland`.

### ⚙️ Requirements
- Windows 10 / Windows 11
- .NET Framework 4.x (built into Windows)

---

## 🇷🇺 Русский

### ✨ Возможности
- **Компактный и развёрнутый вид:** мини-остров с обложкой, названием трека и живым эквалайзером раскрывается при наведении курсора и плавно сворачивается обратно.
- **Управление воспроизведением:** переключение треков, пауза/воспроизведение, интерактивная перемотка по полосе прогресса без задержек и лагов тайминга.
- **Отдельная громкость плеера:** ползунок громкости и кнопка Mute управляют только аудиосессией Яндекс Музыки (через `ISimpleAudioVolume`), не затрагивая общую громкость Windows.
- **Синхронизированный текст песни:** автоматический поиск текста через `lrclib.net`, плавная автопрокрутка и переход к строке по клику.
- **Темы, цвета и свой фон:**
  - 4 встроенные темы: **Яндекс**, **Неон**, **Светлый**, **Океан**.
  - Редактор цветов и пресетов: настройка акцента, фона и рамки в формате `#RRGGBB` / `R, G, B` или через выпадающий **цветовой круг**, переименование и создание своих пресетов.
  - **Свой фон (PNG / анимированный GIF):** установка любого изображения или GIF-анимации в качестве фона острова (сохраняется в `%LocalAppData%\YandexMusicIsland`).
- **Свободное расположение на экране:** перетаскивание острова мышкой в любое место или выбор точки на экране через настройки (координаты сохраняются между запусками).
- **Поддержка любых сборок Яндекс Музыки:** в настройках можно вручную указать путь к любому `.exe`-файлу плеера (официальной или модифицированной версии) для запуска и привязки громкости.
- **Низкое потребление ресурсов:** рендер-цикл отключается на паузе и при скрытии, обложки и GIF-кадры оптимизированы по памяти.

### 🚀 Запуск
1. Скачайте `YandexMusicIsland.exe` из раздела **Releases**.
2. Запустите файл — остров появится на экране и добавит иконку в системный трей.
3. Все настройки, пресеты и позиция окна сохраняются в реестре (`HKCU\Software\YandexMusicIsland`).

### ⚙️ Требования
- Windows 10 / Windows 11
- .NET Framework 4.x (встроен в Windows)
