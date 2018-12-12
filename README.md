# docker-security-checker

The SensioLabs Security Checker is a command line tool that checks if your application uses dependencies with known security vulnerabilities. It uses the [Security Check Web service](https://security.symfony.com/) and the [Security Advisories Database](https://github.com/FriendsOfPHP/security-advisories).

## Run

### Default Run

```bash
docker run -v /path/to/code/:/opt/mount/ guardrails/security-checker:latest
```

### JSON Output

```bash
docker run -v /path/to/code/:/opt/mount/ guardrails/security-checker:latest --format=json
```

## Contributing

Have some improvements? Send a pull request! Thank you!

## Support

This repository is supported by [GuardRails.io](https://www.guardrails.io).