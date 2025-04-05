---
layout: page
title: ""
permalink: /adolts_reading/
lang: ua
show_header: false
---

![Alt text](/assets/images/funnel4/funnel4_banner.png){: .img}

### Бонус за скептицизм

Убедись на себе, что Дизайн Человека работает.

Получи полный разбор своей карты + 30% скидка на разбор карты ребёнка.

### Зачем это мне?
Дизайн Человека способен дать наиболее полный и исчерпывающий ответ на вопрос "Кто Я?".
В нём есть слова, которые ты всегда знал(а) о себе, но (возможно) никогда не произносил(а) вслух.
Если хочешь разобраться в себе и укрепить внутренние опоры, то тебе точно сюда.

### Вот что люди говорят

{% include reviews_adolts.html %}

### Как устроены консультации

- длительность: 2 часа
- стоимость: 150 евро 
- в Берлине или онлайн
- Язык: Украинский Русский Английский

### Записаться
Кнопка ниже направит тебя прямиком на форму заявки

<div class="button-container">
    <a href="#" class="button" id="track-click">Оставить заявку</a>
</div>

<script>
  // Function to get the subscriber_id from the URL
  function getSubscriberId() {
    const params = new URLSearchParams(window.location.search);
    return params.get("subscriber_id");
  }

  document.getElementById('track-click').addEventListener('click', function(event) {
    event.preventDefault();

    const subscriberId = getSubscriberId();
    const baseUrl = "https://nikpolonsky.github.io/";
    const anchor = "#consultation-form";

    let nextPage = baseUrl;

    if (subscriberId) {
      nextPage += `?subscriber_id=${subscriberId}${anchor}`;
    } else {
      nextPage += anchor;
    }

    window.location.href = nextPage;
  });
</script>

