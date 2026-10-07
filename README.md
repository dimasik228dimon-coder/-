# Расписание — сборка APK

1. Зайдите на github.com, создайте аккаунт (бесплатно) и новый репозиторий (New repository).
2. Нажмите "uploading an existing file" и перетащите ВСЕ файлы и папки из этого архива
   (www, .github, package.json, capacitor.config.json). Папка .github обязательна.
   Если проводник скрывает папку .github, включите показ скрытых файлов.
3. Нажмите Commit changes.
4. Откройте вкладку Actions -> Build APK. Сборка идёт 5-8 минут.
   Если не стартовала сама: Run workflow.
5. Откройте завершённую сборку, внизу в Artifacts скачайте raspisanie-apk (zip),
   внутри будет app-debug.apk.
6. Скопируйте APK на телефон, откройте его и разрешите установку из этого источника.
