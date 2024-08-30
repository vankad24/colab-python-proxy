# Google Colab Proxy

Colab тетрадка для запуска своего личного прокси на машине Google😎

![](https://media1.tenor.com/m/7SI7s743NmoAAAAC/evil-evil-laugh.gif)

---

## Инструкция

- Скачать файл [сolab_proxy.ipynb](сolab_proxy.ipynb)
- Зайти на [Google Colab](https://research.google.com/colaboratory)
- Нажать `Файл > Загрузить блокнот`
- Запустить все ячейки
- Скопировать ссылку и вставить в настройки интернета
- Наслаждаться халявой!

---

## Комментарии

- Реализация proxy была подсмотрена у [Deviper-Labs](https://github.com/Deviper-Labs/Web-Proxy-PHP-Colab/)
- Для создания tcp тоннеля можно использовать и Ngrok, но нужен подтверждённый аккаунт.
- Данный proxy проработает не более 1 часа (для бесплатных аккаунтов pinggy), затем ссылка меняется. Также через несколько часов сеанс в Colab будет остановлен из-за ограничений.
- Если proxy не работает, можно попробовать сменить машину, на которой он запускается. Для этого нажмите `Среда выполнения > Отключиться от среды выполнения и удалить её`, затем снова выполните все ячейки.

---

## Гениально, не правда ли?

![](https://media1.tenor.com/m/6wWAAAupK7EAAAAd/thanks-awesome.gif)