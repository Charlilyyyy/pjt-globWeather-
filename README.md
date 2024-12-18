# Larave Vue Weather App

### Pre requisite

1. composer 
2. node
3. npm

### Stack

- Laravel 11
- Vue 3
- Typescript
- Tailwind

### Steps

#### Below are the steps to run the backend app

###### Go to backend directory
```bash
cd backend
```

###### Install php laravel dependencies
```bash
composer install
```

###### create env
```bash
cp .env.example .env
```

###### setup app key
```bash
php artisan key:generate
```

###### run migration
```bash
php artisan migrate
```

###### serve app
```bash
php artisan serve
```

#### Below are the steps to run the frontend app

###### Go to frontend directory
```bash
cd frontend
```

###### Install node modules
```bash
npm install && npm run dev
```

- Open http://localhost:8000/api or your predefined route for testing the api
- Open http://localhost:5173 or your predefined localhost route for viewing the website
