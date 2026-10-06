# DnDT - Dungeons and Dragons Tracker

A simple tracking tool to help track various things across campaigns.

## Features

- **Inventory Tracking** - Track inventories with a historical log of items coming in and out
- **Shared Contacts** - Track shared contacts across campaigns
- **Locations** - Track locations
- **Documents/Notes** - Store and share notes

## Tech Stack

### Backend

- [Laravel v8.x](https://laravel.com/)
- [Sanctum](https://laravel.com/docs/8.x/sanctum) - Session based authentication
- [Socialite](https://laravel.com/docs/8.x/socialite) - Third party SSO

### Frontend

- [VueJS v2.x](https://vuejs.org/)
- [Vuetify](https://vuetifyjs.com/en/) - UI library
- [Axios](https://github.com/axios/axios) - HTTP requests

## Setup

### Prerequisites

- PHP 8.0+
- Composer
- Node.js 16+
- MySQL
- Nginx

### Installation

1. Clone the repository:

```bash
git clone https://github.com/itsdarklikehell/dndt.git
cd dndt
```

2. Install dependencies:

```bash
composer install
npm install
```

3. Configure environment:

```bash
cp .env.example .env
php artisan key:generate
```

4. Run migrations:

```bash
php artisan migrate
```

5. Build frontend:

```bash
npm run dev
```

6. Start the server:

```bash
php artisan serve
```

## Docker

```bash
docker-compose up -d
```

## Testing

```bash
php artisan test
```

## License

MIT
