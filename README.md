# PRE.AX Марафон

Описание проекта

## Инструкция по участию:

1. Клонировать проект
```git
git clone https://github.com/jorjodell/pre.ax-test.git
```

2. Создать из ветки `main` свою ветку `developer/FL-01`, где FL — ваши инициалы, 01 — ваш ID.
```git
git checkout -b developer/FL-01
```
3. Установить зависимости и запустить проект
```
npm install
npm start
```
4. После завершения задачи коммитить названием и номером задачи, например `1. Create ui layout`;
```git
git commit -m "1. Create ui layout"
```

5. Пушить в такую же удаленную ветку
```git
git push origin developer/FL-01
```

## Инструкция по продолжению работы в другой ветке:
1. Стянуть все удаленные ветки
```git
git fetch origin
```
2. Переключиться на нужную ветку, например `developer/DR-02`.
```git
git checkout developer/DR-02
```
3. Закоммитить согласно верхним правилам.
4. Проверить не было ли изменений в удаленной ветке.
```git
git pull
```
5. Запушить в эту же удаленную ветку
```git
git push
```
