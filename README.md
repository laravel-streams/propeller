<p align="center"><img src="/art/logo.svg" alt="Logo Propeller"></p>

<p align="center">
    <a href="https://packagist.org/packages/streams/propeller">
        <img src="https://img.shields.io/packagist/dt/streams/propeller" alt="Total Downloads">
    </a>
    <a href="https://packagist.org/packages/streams/propeller">
        <img src="https://img.shields.io/packagist/v/streams/propeller" alt="Latest Stable Version">
    </a>
    <a href="https://packagist.org/packages/streams/propeller">
        <img src="https://img.shields.io/packagist/l/streams/propeller" alt="License">
    </a>
</p>

## Introduction

Propeller is an application starter kit based on [Laravel Breeze](https://github.com/laravel/breeze) and pre-configured with [Laravel Streams](https://github.com/laravel-streams/streams).

Propeller provides a minimal and simple starting point for building a Laravel application with authentication. Styled with Tailwind, Propeller publishes authentication controllers and views to your application that can be easily customized based on your own application's needs.

Propeller is powered by Blade, Tailwind, and Streams. <!-- If you're looking for a more robust Laravel starter kit that includes two factor authentication, Livewire / Inertia support, and more, check out [Laravel Jetstream](https://jetstream.laravel.com). -->

Getting started couldn't be easier:

```bash
laravel new my-app

cd my-app

composer require streams/core streams/api streams/ui

composer require streams/propeller --dev

php artisan breeze:install
```

## Contributing

Thank you for considering contributing to Propeller! You can read the contribution guide [here](.github/CONTRIBUTING.md).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

Please review [our security policy](https://github.com/laravel/propeller/security/policy) on how to report security vulnerabilities.

## License

Propeller is open-sourced software licensed under the [MIT license](LICENSE.md).
