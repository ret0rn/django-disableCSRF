# Django Disable CSRF
django middleware to disable CSRF validation

##Set up

```python

MIDDLEWARE = [
  ...
  # 'django.middleware.csrf.CsrfViewMiddleware',
  'apps.<your_app>.middleware.DisableCSRF',
  ...
```
