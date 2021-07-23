# Registration Roles

[![MIT license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/the-turk/flarum-regrole/blob/master/LICENSE) [![Latest Stable Version](https://img.shields.io/packagist/v/the-turk/flarum-regrole.svg)](https://packagist.org/packages/the-turk/flarum-regrole) [![Total Downloads](https://img.shields.io/packagist/dt/the-turk/flarum-regrole.svg)](https://packagist.org/packages/the-turk/flarum-regrole)

Allow users to assign roles to themselves during registration. You can also force existing users.

![Registration Roles](https://i.ibb.co/KhFp3hQ/reg-Role-Sign-Up-Modal.png)

[Settings Screenshot](https://i.imgur.com/U4URUoG.png)

## Installation

```bash
composer require the-turk/flarum-regrole:"*"
```

## Updating

```bash
composer update the-turk/flarum-regrole
php flarum cache:clear
```

## Usage

Enable the extension and set allowed roles from the extension's settings. Also enable the "Force users to assign at least one role to themselves" option to force guests as well as existing users (users with "Edit user groups" permission will be excluded) to have at least one of those allowed roles.

**! Attention:** I've tested this extension as much as I can. However, any malfunction of this extension may cause fatal errors during registration and your users might be unable to use your forum. So please test it yourself (register to your forum and login as existing user if you're forcing them to choose a role) after installation to see if everything is working fine for everyone.

## Links

- [Flarum Discuss post](https://discuss.flarum.org/d/24500-registration-roles)
- [Source code on GitHub](https://github.com/the-turk/flarum-regrole)
- [Changelog](https://github.com/the-turk/flarum-regrole/blob/master/CHANGELOG.md)
- [Report an issue](https://github.com/the-turk/flarum-regrole/issues)
- [Download via Packagist](https://packagist.org/packages/the-turk/flarum-regrole)
