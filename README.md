# react-wp-template
Шаблон для создания react-приложений на стеке (react + ts + webpack + firebase + eslint + stylelint + prettier)

## Команды
- Запуск проекта в режиме разработки: ```npm run start```
- Сборка проекта на продакшн: ```npm run build```
- Проверить js код: ```npm run eslint```
- Пофиксить проблемы js кода: ```npm run eslint:fix```
- Проверить синтаксис проекта: ```npm run prettier```
- Пофиксить проблемы синтаксиса проекта: ```npm run prettier:fix```
- Проверить css код: ```npm run stylelint```
- Пофиксить проблемы css кода: ```npm run stylelint:fix```

## CI/CD (конфиг для gitlab'а)
Базовая конфигурация для сборки проекта при MR и слиянии в master
готова и описана в .gitlab-ci.yml. Расширяйте его так, как вам надо. 
