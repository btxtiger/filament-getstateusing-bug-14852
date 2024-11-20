# Filament getStateUsing() bug

Example code to reproduce the bug.

## Installation
```sh
composer install && npm install && npm run build
```

## Steps to reproduce
Start the app using
```sh
composer run dev
```
Open 
```sh
http://127.0.0.1:8000/admin/users
```
Login with credentials
```sh
admin@admin.com
admin
```

On the Users page, open the Laravel DebugBar > Queries and see 3 identical queries
