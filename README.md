# braind_task2

Задание 2 - Исправить ошибки  
В архиве находятся исходники вёрстки с системой их сборки, в которых содержатся ошибки.  
Вам необходимо р азобраться с проблемами и заставить к нопку «Добавить в корзину» работать. Пример работы кнопки представлен на скриншоте:  

Исправленные исходники загрузите в репозиторий github и собранные исходники (содержимое папки build после сборки) для демонстрации на github pages  

__________________________________________________

Процесс выполнения:  
Node.js был уменьшен до версии 11.10.1, gulp версии 3.9.1;  
Удален task - concatLegacyScripts - в json;  
В main.js - переменные $btns - изменены на let btns;  
dataType изменен с "html" на "json" (11 строка);  
Немного изменены строки 12-22;  
Добавлены стили в main.scss для .cart-icon, .cart-icon__counter;  
