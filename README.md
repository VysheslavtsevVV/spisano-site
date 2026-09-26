# Сайт Spisano (GitHub Pages)

Главная, политика конфиденциальности и условия использования. Этот каталог копируется
в отдельный **публичный** репозиторий `spisano-site` (GitHub Pages бесплатно — только для публичных).

## Загрузка

1. github.com → New repository → имя `spisano-site`, Public → Create.
2. «uploading an existing file» → перетащи всё содержимое этой папки (вместе с `fonts/` и `.nojekyll`) → Commit changes.
3. Settings → Pages → Source: Deploy from a branch → Branch `main`, папка `/ (root)` → Save.
4. Через 1–2 минуты сайт откроется по адресу `https://ЛОГИН.github.io/spisano-site/`.
   Политика — `.../privacy.html`, условия — `.../terms.html`.
5. Ссылку на политику — в Play Console («Контент приложения» → «Политика конфиденциальности»)
   и позже в App Store Connect.

## Обновление

Правь файлы здесь (`site/` в проекте приложения), потом загрузи изменённые в репозиторий `spisano-site`.
Текст политики держи в согласии с экраном «Конфиденциальность и условия» в приложении
(`lib/features/more/info_screens.dart`) и меняй дату редакции в обоих местах.

Шрифты: Unbounded, Golos Text — SIL Open Font License (`fonts/OFL-*.txt`).
