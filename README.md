# deployments
Various premade deployments to develop or run Horde environments

## basic-setup

* The Horde Base app with mariadb database connection and SQL Auth, an initial user injected.
* Use this to test drive your custom app.
* Database schema autoinstalls

## groupware-webmail

Horde with webmail, calendar, tasks, notes, etc.
* Apps come with some generic config
* Database schema autoinstalls
* Webmail will connect to a Dovecot and a Postfix container

## helm charts collection

Installation

```console
helm repo add maintaina https://curx.github.io/maintaina-deployments/
helm search repo maintaina
```

