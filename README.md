# About

This website its Online Ticket shop (e-Ticket) an online portal that purchases and sells tickets to concerts and events worldwid
![Dashboard _ Admin - Starloards](https://user-images.githubusercontent.com/50520333/197030581-88aeaea2-8760-48f1-970f-e8e10e48b873.png)
![Home - Starloards](https://user-images.githubusercontent.com/50520333/197031041-8c3aa1a6-64d2-4a5c-9dfe-65a4da7b9a84.png)


# Installation
```
git clone
cd Starlab-Intership-Team-4
cp .env.example .env
composer update
npm install
php artisan migrate --seed
```
### Start Project
``` 
php artisan serve
```
And
``` 
npm run dev
```

### Configurate
- Server Configurate `.env`
- Project other Configurate `config/`

### Technology we use:
- TALL Stack
- TailwinCSS
- AlpineJS (3)
- Laravel (9)
- Livewire

### Some Package
- Laravel Jetstream
- Laravel Socialite
- Laravel Cashier (Stripe)
- Laravel Debugger
- Role and Permission (spatie)
- Medialibrary (spatie)
- WireUI


# Feature
- Live Chat for Costumer
- SEO Meta Tags
- Vizitors
- Feedback
- Auditing
- Blog
- Backup System
- Monitorate System 
- e-Mail Support (Notification)
- Admin Table
    - Multi Delelte
    - Sortable
    - Fast Paginate
    - Serchable


#### User
- Online/Offline
- Verify/UnVerify
- Ban/UnBan with Reason
- Role Asighn
- User Login Action track

#### Event
- Multi Category
- Multi Tags
- Like, Share,whishlist,Report(polymorphism)
- Comment & Reply (polymorphism)
- Google Map
- Newsletter
- Rich Filter
- Ticket Payment

#### Organisation
- Multi Category
- Multi Tags
- Subscription with Notification
- Report (polymorphism)
- Review with Star Rating (Polymorphism)
- Google Map
- Album/Gallery

# Costum Command

This command make Livewire CRUD (for Modeles) on Admin Panel

```
php artisan make:crud MODEL_NAME
``` 
