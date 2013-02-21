# Django Vkontakte Places

[![Build Status](https://travis-ci.org/ramusus/django-vkontakte-places.png?branch=master)](https://travis-ci.org/ramusus/django-vkontakte-places)

Приложение позволяет взаимодействовать с географическими объектами Вконтакте, такими как страны и города через Вконтакте API используя стандартные модели Django

## Установка

    pip install django-vkontakte-places

В `settings.py` необходимо добавить:

    INSTALLED_APPS = (
        ...
        'vkontakte_api',
        'vkontakte_places',
    )