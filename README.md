## Опис

### mhddos_bash - скрипт на bash, що керує [mhddos_proxy](https://github.com/porthole-ascend-cinnamon/mhddos_proxy)

* Запускається однією командою в Linux і WSL2 (Windows Subsystem for Linux). Подальше втручання від користувача не обов'язкове. 
 
```
curl -s https://raw.githubusercontent.com/KarboDuck/mhddos_bash/master/runner.sh | bash
```
* Автоматично встановлює git, python3, pip, mhddos_proxy, MHDDoS, розширений список proxy і всі залежності.

* Праюцює із базою сайтів [Українського женця](https://github.com/Aruiem234/auto_mhddos/blob/main/runner_targets).

* База цілей оновлюється кожні 20 хвилин.

* Під час запуску завжди перевіряє і завантажує оновлення mhddos_proxy і MHDDoS.

Рекомендовано використовувати на Ubuntu 20.04. На інших системах не перевірялось. Можливо буде працювати на всіх Ubuntu починаючи з 18.04, усіх похідних Ubuntu, Debian, та WSL2.

Для зупинки скрипта кілька разів натисніть CTRL+C, або закрийте вікно з терміналом.
