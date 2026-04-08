Описание проекта обновляется 


### 5. Файл `README.md` для репозитория

```markdown
# Urho3D-SwimCorridor

Сцены и регламенты для соревнований по робототехнике в Urho3D.

## Структура

- `Scenes/` — XML сцены Urho3D
- `Materials/` — материалы (жёлтый, зелёный, красный)
- `Rules/` — регламент соревнований

## Использование

1. Скопируйте `Scenes/*.xml` в `Urho3D/build/bin/Data/Scenes/`
2. Скопируйте `Materials/*.xml` в `Urho3D/build/bin/Data/Materials/`
3. Запустите в Urho3D:
```bash
./Urho3DPlayer Data/Scenes/GeneratedCorridorWithLines3.xml
