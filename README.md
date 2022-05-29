# Django Disable CSRF
django middleware to disable CSRF validation

## Set up

**settings.py**

```python

MIDDLEWARE = [
  ...
  # 'django.middleware.csrf.CsrfViewMiddleware',
  'apps.<your_app>.middleware.DisableCSRF',
  ...
]

```
