GTA San Andreas + CoopAndreas для игры по локальной сети

Содержимое:
- SAMP\ — готовая папка игры с установленным CoopAndreas;
- CoopAndreasServer\ — локальный сервер на UDP-порту 6768;
- GTA San Andreas User Files\coopandreas.ini — пример конфигурации клиента.

Установка на другом ПК:
1. Распакуйте папку SAMP в удобное место, например E:\SAMP.
2. Скопируйте файл coopandreas.ini в "Документы\GTA San Andreas User Files".
3. В coopandreas.ini задайте уникальный nickname. IP должен быть адресом ПК-хоста,
   например 192.168.1.104, а порт — 6768.
4. На ПК-хосте запустите CoopAndreasServer\Start-CoopAndreas-Server.cmd.
   Один раз от имени администратора выполните Configure-LAN-Firewall.ps1,
   чтобы разрешить UDP 6768 в частной сети.
5. На каждом ПК откройте SAMP\LaunchCoopAndreas.exe, получите свой beta-ключ
   в Discord по команде из окна лаунчера и нажмите Launch CoopAndreas.

Для обычного SA-MP: удалите SAMP\eax.dll и переименуйте eax_orig.dll обратно в eax.dll.
