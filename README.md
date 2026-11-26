AIdownloader — черновые юридические страницы

Файлы:
- requisites.html
- offer.html
- refund.html
- privacy.html

Установка:
1. Скопируйте все четыре HTML-файла в корень репозитория GitHub рядом с index.html.
2. В index.html замените текущий блок footer на:

<footer>
  <div>⚡ AIdownloader · Работает на Replicate</div>
  <div style="margin-top:8px;display:flex;gap:14px;justify-content:center;flex-wrap:wrap">
    <a href="/requisites.html">Реквизиты</a>
    <a href="/offer.html">Публичная оферта</a>
    <a href="/refund.html">Возврат</a>
    <a href="/privacy.html">Политика конфиденциальности</a>
    <a href="mailto:support@aidownloader.app">Контакты</a>
  </div>
</footer>

3. Замените все поля в квадратных скобках на проверенные данные. Не публикуйте страницы с незаполненными полями.
4. Проверьте тексты с юристом и убедитесь, что они соответствуют фактической работе сервиса и требованиям платёжного оператора.

Важно:
- Это шаблоны, а не юридическая консультация и не готовые документы для приёма платежей.
- Не публикуйте вымышленные реквизиты, адреса, статусы продавца или неподтверждённые условия возврата.
- Не добавляйте секреты API, Firebase ID-токены, ключи ЮKassa или Replicate в эти страницы и HTML.
