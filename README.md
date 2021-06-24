[![](https://img.shields.io/badge/released-2021.6.24-green.svg?longCache=True)](https://pypi.org/project/django-objects-count/)
[![](https://img.shields.io/badge/license-Unlicense-blue.svg?longCache=True)](https://unlicense.org/)

### Installation
```bash
$ pip install django-objects-count
```

### How it works
+   admin interface
+   middleware (optional, admin urls only) - dynamic models `verbose_name_plural` with objects count

#### `settings.py`
```python
INSTALLED_APPS+=['django_objects_count']

MIDDLEWARE+=['django_objects_count.middleware.ObjectsCountMiddleware'] # optional
```
#### `migrate`
```bash
$ python manage.py migrate
```

