# PasswordBreaker

## Описание

`PasswordBreaker` — это VBA-скрипт для Microsoft Excel, который позволяет снять защиту с листа, удалить пароль и отобразить текущий пароль, установленный на листе. Этот инструмент предназначен для использования в ситуациях, когда вы забыли пароль для защиты листа Excel и нужно восстановить доступ к данным.

## Содержание

- [Предупреждение](#предупреждение)
- [Как использовать](#как-использовать)
  - [Шаг 1: Подготовка](#шаг-1-подготовка)
  - [Шаг 2: Запуск скрипта](#шаг-2-запуск-скрипта)
- [Что делает скрипт](#что-делает-скрипт)
- [Примечания](#примечания)
- [Лицензия](#лицензия)

## Предупреждение

Использование данного скрипта для снятия защиты с листов Excel, к которым вы не имеете законного доступа, может нарушать политику конфиденциальности и авторские права. Убедитесь, что у вас есть разрешение на использование данного инструмента для снятия защиты.

## Как использовать

### Шаг 1: Подготовка

1. **Откройте Microsoft Excel**.
2. **Откройте файл, который вы хотите разблокировать**.
3. **Откройте редактор VBA**:
   - Нажмите `ALT` + `F11`, чтобы открыть редактор VBA.

4. **Создайте новый модуль**:
   - В редакторе VBA выберите `Вставка` -> `Модуль`, чтобы создать новый модуль.

5. **Скопируйте код** из файла `PasswordBreaker` и вставьте его в окно модуля.

### Шаг 2: Запуск скрипта

1. **Вернитесь в Excel**:
   - Нажмите `ALT` + `F8`, чтобы открыть окно "Макросы".

2. **Выберите `PasswordBreaker`** из списка доступных макросов и нажмите `Выполнить`.

3. **Следуйте инструкциям**:
   - Скрипт выполнит процесс снятия защиты с листа, удалит пароль и отобразит текущий пароль.

## Что делает скрипт

- **Снимает защиту с указанного листа**: Если лист защищен паролем, скрипт попытается снять защиту.
- **Удаляет пароль**: После снятия защиты пароль удаляется.
- **Отображает пароль**: Скрипт покажет текущий пароль, если это возможно.

## Примечания

- Скрипт может не работать с листами, защищенными современными алгоритмами шифрования.
- Убедитесь, что ваш Excel настроен на выполнение макросов. Для этого вам может понадобиться изменить настройки безопасности макросов в Excel.

## Лицензия

Этот проект распространяется под лицензией [MIT License](LICENSE). См. файл LICENSE для подробностей.
