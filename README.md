# Публикация сайта через GitHub Pages

В этой папке уже лежит готовый сайт: `index.html` и картинка `og.png`.

## Как выложить сайт

1. Откройте свой созданный репозиторий на GitHub.
2. Нажмите **Add file → Upload files**.
3. Перетащите в окно два файла из этой папки: `index.html` и `og.png`.
4. Внизу нажмите **Commit changes**.
5. Откройте **Settings → Pages** в меню репозитория.
6. В блоке **Build and deployment** выберите:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/(root)**
7. Нажмите **Save** и подождите 1–3 минуты.

GitHub покажет адрес сайта в этом же разделе. Обычно он выглядит так:
`https://ВАШ-ЛОГИН.github.io/НАЗВАНИЕ-РЕПОЗИТОРИЯ/`

Если репозиторий приватный, для бесплатного публичного GitHub Pages лучше сделать его **Public**: Settings → General → Danger Zone → Change repository visibility.
