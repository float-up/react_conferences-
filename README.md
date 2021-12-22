
## JUG.RU Conferences contest

### Установка

Для установки выполнить клонирование репозитория, перейти в папку и установить зависимости: `npm i` и запустить: `npm start`

### Описание

Приложение реализовано с использованием __TypeScript__, в качестве библиотеки для state-management используется __MobX__. 

Корневым компонентом служит `src/components/App.tsx`. В качестве mock данных используется json файл  расположенный в `public/data.json`

К приложению написаны юнит и интеграционные тесты компонентов с использованием Jest и Enzyme (расположены в папке `src/components/__tests__`), а также тесты mobx store (`store/__tests__`) 


![Снимок экрана 2021-12-22 в 20 20 18](https://user-images.githubusercontent.com/10547797/147132181-97c98fc3-b237-41cb-b7cf-2829e4cca6f9.png)
