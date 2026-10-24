# STRATUM

In-game mod loader for **CarX Drift Racing Online 2 / Windows x64**.
Loader **0.9.0** · Native ABI **1** · **.strmod v2** · SDK **0.9.1**.

## Install / Установка

1. Close the game. / Закройте игру.
2. Copy **winhttp.dll** next to the game's EXE. Replace the previous STRATUM DLL when updating. / Скопируйте **winhttp.dll** рядом с EXE игры; при обновлении замените прежнюю DLL STRATUM.
3. Start the game through Steam. Press **Insert** to open or close the menu. / Запустите игру через Steam. **Insert** открывает и закрывает меню.

Default UI scale: **125%**. The menu starts closed. / Начальный масштаб: **125%**. При запуске меню скрыто.

## Mods / Моды

Import a package through **«Установить мод» (Install mod)** or place it in **STRATUM/Mods**. Close the game before replacing a loaded package.

Импортируйте пакет через **«Установить мод»** либо поместите его в **STRATUM/Mods**. Перед заменой загруженного пакета закройте игру.

Created automatically on first launch / Создаются автоматически при первом запуске:

```text
STRATUM/Mods       mods / моды
STRATUM/Configs    settings / настройки
STRATUM/Logs       logs / журналы
```

Supports native C++ and C# Native AOT packages. Existing managed/BepInEx DLLs need source adaptation and rebuilding. Players do not need the SDK or a separate .NET/BepInEx installation.

Поддерживаются нативные C++ и C# Native AOT пакеты. Старые управляемые/BepInEx DLL требуют адаптации исходников и пересборки. Игроку не нужны SDK и отдельная установка .NET/BepInEx.

Developer guides are in the archive's **SDK/docs** folder, in English and Russian. / Гайды для разработчиков находятся в папке **SDK/docs** архива на английском и русском.
