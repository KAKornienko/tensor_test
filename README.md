Тестовые сценарии в соответствии с требованиями к выполнению тестового задания

Для запуска проекта: 
1. Склонируйте репозиторий к себе
2. Разверните и запустите виртуального окружение
3. Установите зависимости
4. Запустите тесты командой pytest в корневой папке проекта

Дополнительные замечения к тестовой работе:
1. При выполнении первоого сценария столкнулся с крайне неприятным банером от яндекса предлагающим установить свои расширения в момент когда выводятся результаты поиска. Смог обойти с помощью browser.implicitly_wait(1).
2. При выполнении второго сценария столкнулся с тем что кнопка меню больше не находится на прежнем месте, теперь меню появляется при клике на поле поиска. Поэтому тесты адаптированы под новый дизайн сайта
3. Из-за особенностей загрузки картинок ссылка не успевает измениться до проверки, из-за этого был использован time.sleep()