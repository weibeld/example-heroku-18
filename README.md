# Example Heroku-18 app

Example Heroku app using the [Heroku-18](https://devcenter.heroku.com/articles/heroku-18-stack) stack.

## App

```bash
$ heroku info
=== ancient-eyrie-54549
Auto Cert Mgmt: false
Dynos:
Git URL:        https://git.heroku.com/ancient-eyrie-54549.git
Owner:          danielmweibel@gmail.com
Region:         us
Repo Size:      5 KB
Slug Size:      6 MB
Stack:          heroku-18
Web URL:        https://ancient-eyrie-54549.herokuapp.com/
```

## Restore

Clone the repository:

```bash
git clone https://github.com/weibeld/example-heroku-18
cd example-heroku-18
```

Add `heroku` remote:

```bash
git remote add heroku https://git.heroku.com/ancient-eyrie-54549.git
```

Heroku app is now restored:

```bash
heroku info
```

## See also

[Example Heroku-16 app](https://github.com/weibeld/example-heroku-16)
