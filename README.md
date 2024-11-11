# Testing-API-Yandex.Counter-
Разработчики сделали новую функциональность в API Яндекс.Прилавка. Новую версию API передали тебе на тестирование. 
Предусловия
Тестовый стенд: https://{id}.serverhub.praktikum-services.ru/
Документация API: https://{id}.serverhub.praktikum-services.ru/docs/
Изучи новую функциональность. 
Работа с наборами: возможность добавлять продукты в набор — ручка POST /api/v1/kits/{id}/products.
Работа с курьерами: возможность проверить, есть ли доставка курьерской службой «Привезём быстро» и сколько она стоит. Ручка POST /fast-delivery/v3.1.1/calculate-delivery.xml. 
Работа с корзиной:
возможность получить список продуктов, которые добавили в корзину. Ручка GET /api/v1/orders/id;
возможность добавлять продукты в корзину. Ручка PUT /api/v1/orders/:id;
возможность удалять корзину. Ручка DELETE/api/v1/orders/:id.
Постановка задачи
Проанализируй требования к новой функциональности бэкенда Яндекс.Прилавка. Изучи документацию к API в Apidoc. Требования к бэкенду находятся здесь.
https://code.s3.yandex.net/qa/files/backend_requirements.pdf
Спроектируй тесты в виде чек-листа, чтобы покрыть функциональность, которую тебе передали на тестирование: она описана выше. Авторизацию проверять не нужно.
Чек-лист помести в гугл-таблицу. Создай копию шаблона и открой доступ на комментирование по ссылке.
![chrome_AyXjv1fD2q](https://github.com/user-attachments/assets/af98f81e-cea8-43c1-a106-714e1bbc746d)
![chrome_BUa29yCLqT](https://github.com/user-attachments/assets/b17718b5-28e7-4931-b1a5-bbc84bf11604)
![chrome_A97UuuB9Ax](https://github.com/user-attachments/assets/374a06a6-de47-4380-99ea-08a3641a55ce)
![chrome_wgkVyi9aeu](https://github.com/user-attachments/assets/c5cb4047-4137-4357-9913-696ee3f5feb8)
![chrome_uHLZsMxiaU](https://github.com/user-attachments/assets/b360b5b6-2034-4fdf-91e5-e5f03e2bdb6d)
![chrome_nYVGbON3tO](https://github.com/user-attachments/assets/4cb0351b-0d1c-4509-84fe-e63a2545f394)
![chrome_GqdVOEPFqt](https://github.com/user-attachments/assets/780d30a9-3dc3-497f-926c-ee5149fe3901)
![chrome_O67430l7lG](https://github.com/user-attachments/assets/aeeefbc7-7979-4422-a676-7d9f9c412185)
https://docs.google.com/spreadsheets/d/1ZK5DdFUKul76ObfIT9YVVFMNNxWeFKfcxts3L1WVFKA/edit?usp=sharing
Протестируй API через Postman и заведи баг-репорты в YouTrack, если это понадобится.
https://gamanstela.youtrack.cloud/issues?q=tag:%20%7BSprint4Practice%7D
