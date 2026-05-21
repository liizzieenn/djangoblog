# Django Blog — Demo პროექტი

## გაშვება
```bash
python manage.py runserver
```
გახსენი: http://127.0.0.1:8000

## ადმინ პანელი
URL: http://127.0.0.1:8000/admin
მომხმარებელი: admin
პაროლი: admin123

## სტრუქტურა
- `blog/models.py` → Post და Comment მოდელები
- `blog/views.py` → post_list და post_detail view-ები
- `blog/urls.py` → URL routing
- `blog/templates/` → HTML შაბლონები
- `blog/admin.py` → ადმინ პანელის კონფიგურაცია
