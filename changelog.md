## История изменений

**2.2.4**
- Добавлена совместимость с Django 1.5.

**2.2.3**
- Вывод прав пользователя в `GetRolePermissionAction` - убраны
  ненайденные.

**2.2.2**
- Обновление app_meta.register_urlpatterns для совместимости с Django 1.10.
- Исправлен вывод прав пользователя в `GetRolePermissionAction` - убраны
  неактуальные.

**2.2.1**
- Исправлены ошибки при запросах к таблице пользователей. Теперь вместо
  импорта модели пользователей используется получение модели пользователей из
  функции get_user_model.

**2.2.0**
- Добавлены миграции django 1.8
- Функция ``patterns`` из ``django.conf.urls.defaults`` заменена на
  одноименную из ``django.conf.urls``.
- Декоратор ``django.transaction.commit_on_success`` заменен на
  ``m3_django_compat.atomic``.
- Добавил поддержку кастомных моделей пользователя.

**2.1.1**
- Изменил MANIFEST.in. Добавлен m3-builder, .gitignore, REQUIREMENTS, changelog
