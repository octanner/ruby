# Code Quality

#### Code Smells

> [Reek](https://github.com/troessner/reek) checks our code for [smells](https://martinfowler.com/bliki/CodeSmell.html)

We want to avoid known anti-patterns when writing our code.

#### Security

> [Bundler-Audit](https://github.com/rubysec/bundler-audit) (Gems) and [Brakeman](https://github.com/presidentbeef/brakeman) (Rails) check for security vulnerabilities

We want our applications to be secure.  We use `bundle-audit check -u` to ensure no gems in our `Gemfile` have known [CVE](https://cve.mitre.org/) vulnerabilities reported.

We use `brakeman` to ensure our Rails applications don't have known security issues.

#### Performance

> [Bullet](https://github.com/flyerhzm/bullet) checks for slow N+1 queries in ActiveRecord

We value fast code.  We use `bullet` to catch common N+1 queries in our ActiveRecord code.
