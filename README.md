# Awesome Flask [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/awesomelistsio/awesome)

[![DOI](https://zenodo.org/badge/1115455162.svg)](https://doi.org/10.5281/zenodo.19673347)  
[![GitHub Sponsor](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/brandonhimpfen) &nbsp; 
[![Buy Me a Coffee](https://srv-cdn.himpfen.io/badges/buymeacoffee/buymeacoffee-flat.svg)](https://buymeacoffee.com/brandonhimpfen) &nbsp; 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/brandonhimpfen) &nbsp; 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://paypal.me/brandonhimpfen)

📌 This repository is archived with Zenodo and can be cited using the DOI above.

> A curated list of extensions, tools, frameworks, boilerplates, and learning resources for building web applications and APIs with **Flask**, the lightweight Python web framework.

_Support ongoing maintenance and curation via [GitHub Sponsors](https://github.com/sponsors/brandonhimpfen)._

## Contents

- [Official Resources](#official-resources)
- [Starter Kits & Boilerplates](#starter-kits--boilerplates)
- [Authentication & Authorization](#authentication--authorization)
- [APIs & Serialization](#apis--serialization)
- [Database, ORM & Migrations](#database-orm--migrations)
- [Background Jobs & Task Queues](#background-jobs--task-queues)
- [Forms, Validation & Templates](#forms-validation--templates)
- [Security](#security)
- [Testing & Quality Assurance](#testing--quality-assurance)
- [Deployment & DevOps](#deployment--devops)
- [Monitoring & Error Tracking](#monitoring--error-tracking)
- [Learning Resources](#learning-resources)
- [Related Awesome Lists](#related-awesome-lists)

## Official Resources

- [Flask Documentation](https://flask.palletsprojects.com/) – Official documentation covering Flask concepts, APIs, and extensions.
- [Flask GitHub Repository](https://github.com/pallets/flask) – Source code and issue tracker for Flask.
- [Pallets Projects](https://palletsprojects.com/) – Organization behind Flask, Werkzeug, Jinja, and Click.
- [Flask API Reference](https://flask.palletsprojects.com/en/latest/api/) – Detailed reference for Flask classes and functions.

## Starter Kits & Boilerplates

- [Cookiecutter Flask](https://github.com/cookiecutter-flask/cookiecutter-flask) – Production-ready Flask project template with best practices.
- [Flasky](https://github.com/miguelgrinberg/flasky) – Example application from *Flask Web Development* book.
- [Flask-Boilerplate](https://github.com/hack4impact/flask-base) – Modular Flask boilerplate with authentication and APIs.
- [Flask-AppBuilder](https://github.com/dpgaspar/Flask-AppBuilder) – Application framework built on Flask for rapid CRUD apps.
- [Flask-SaaS Boilerplate](https://github.com) – Starter template for building subscription-based Flask applications.

## Authentication & Authorization

- [Flask-Login](https://github.com/maxcountryman/flask-login) – User session management for Flask applications.
- [Flask-Security-Too](https://github.com/Flask-Middleware/flask-security) – Authentication, authorization, and role management extension.
- [Flask-JWT-Extended](https://github.com/vimalloc/flask-jwt-extended) – JWT authentication for APIs built with Flask.
- [Authlib](https://github.com/lepture/authlib) – OAuth and OpenID Connect client and server implementation.
- [Flask-Principal](https://github.com/mattupstate/flask-principal) – Role-based access control for Flask apps.

## APIs & Serialization

- [Flask-RESTful](https://github.com/flask-restful/flask-restful) – Extension for building REST APIs quickly.
- [Flask-RESTX](https://github.com/python-restx/flask-restx) – REST API framework with Swagger/OpenAPI support.
- [Marshmallow](https://github.com/marshmallow-code/marshmallow) – Object serialization and validation library.
- [Flask-Smorest](https://github.com/marshmallow-code/flask-smorest) – API framework integrating Marshmallow and OpenAPI.
- [Connexion](https://github.com/spec-first/connexion) – OpenAPI-first framework built on top of Flask.

## Database, ORM & Migrations

- [Flask-SQLAlchemy](https://github.com/pallets-eco/flask-sqlalchemy) – SQLAlchemy integration for Flask applications.
- [SQLAlchemy](https://www.sqlalchemy.org/) – Powerful Python ORM and database toolkit.
- [Flask-Migrate](https://github.com/miguelgrinberg/flask-migrate) – Database migration support using Alembic.
- [Alembic](https://alembic.sqlalchemy.org/) – Lightweight database migration tool for SQLAlchemy.
- [Flask-MongoEngine](https://github.com/MongoEngine/flask-mongoengine) – MongoDB integration for Flask apps.

## Background Jobs & Task Queues

- [Celery](https://docs.celeryq.dev/) – Distributed task queue commonly used with Flask.
- [Flask-Celery-Ext](https://github.com/robertwayne/flask-celery-ext) – Simplified Celery integration for Flask.
- [RQ](https://github.com/rq/rq) – Simple Redis-backed job queue for Python.
- [APScheduler](https://github.com/agronholm/apscheduler) – Task scheduling library for Python applications.
- [Huey](https://github.com/coleifer/huey) – Lightweight task queue for small Flask projects.

## Forms, Validation & Templates

- [WTForms](https://wtforms.readthedocs.io/) – Flexible forms and validation library for Python.
- [Flask-WTF](https://github.com/wtforms/flask-wtf) – WTForms integration with CSRF protection for Flask.
- [Jinja2](https://palletsprojects.com/p/jinja/) – Powerful templating engine used by Flask.
- [Flask-Bootstrap](https://github.com/mbr/flask-bootstrap) – Bootstrap integration for Flask templates.
- [Flask-Admin](https://github.com/flask-admin/flask-admin) – Admin interface generator for Flask apps.

## Security

- [Flask-Talisman](https://github.com/GoogleCloudPlatform/flask-talisman) – HTTP security headers for Flask applications.
- [ItsDangerous](https://github.com/pallets/itsdangerous) – Cryptographically signed data for Flask apps.
- [Flask-Limiter](https://github.com/alisaifee/flask-limiter) – Rate limiting for Flask routes.
- [Bandit](https://github.com/PyCQA/bandit) – Security linter for Python codebases.
- [OWASP Flask Security](https://owasp.org/) – Best practices for securing Flask applications.

## Testing & Quality Assurance

- [Pytest](https://docs.pytest.org/) – Popular Python testing framework used with Flask apps.
- [Flask-Testing](https://github.com/jarus/flask-testing) – Unit testing utilities for Flask applications.
- [Factory Boy](https://github.com/FactoryBoy/factory_boy) – Test fixtures replacement for ORM-based apps.
- [Coverage.py](https://coverage.readthedocs.io/) – Code coverage measurement for Python projects.
- [Tox](https://tox.wiki/) – Test automation across Python environments.

## Deployment & DevOps

- [Gunicorn](https://gunicorn.org/) – WSGI HTTP server commonly used for deploying Flask apps.
- [uWSGI](https://uwsgi-docs.readthedocs.io/) – Application server for Python web apps.
- [Docker](https://www.docker.com/) – Containerization platform for packaging Flask applications.
- [Fly.io](https://fly.io/) – Global deployment platform for Flask containers.
- [Render](https://render.com/) – Managed hosting for Flask apps and APIs.
- [DigitalOcean App Platform](https://www.digitalocean.com/products/app-platform/) – PaaS hosting for Python web apps.

## Monitoring & Error Tracking

- [Sentry](https://sentry.io/) – Error tracking and performance monitoring for Flask applications.
- [Prometheus](https://prometheus.io/) – Metrics collection system for application monitoring.
- [Grafana](https://grafana.com/) – Visualization dashboards for metrics and logs.
- [Elastic APM](https://www.elastic.co/apm/) – Application performance monitoring for Python services.
- [New Relic](https://newrelic.com/) – Observability platform for Flask and backend services.

## Learning Resources

### Tutorials
- [Flask Mega-Tutorial](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world) – Comprehensive tutorial series by Miguel Grinberg.
- [Flask Web Development Book](https://www.oreilly.com/library/view/flask-web-development/9781491991725/) – Definitive guide to building Flask apps.
- [Real Python Flask Tutorials](https://realpython.com/tutorials/flask/) – Practical Flask tutorials and examples.

### Guides
- [Flask Application Patterns](https://flask.palletsprojects.com/en/latest/patterns/) – Recommended architectural patterns for Flask apps.
- [Designing Flask APIs](https://flask.palletsprojects.com/) – Best practices for building maintainable APIs.
- [Python Web Security Guide](https://realpython.com/python-web-security/) – Security guidance relevant to Flask applications.

### Courses
- *Build REST APIs with Flask* – API-focused Flask development course.
- *Flask for SaaS Applications* – Course covering authentication, billing, and scaling Flask apps.
- *Full-Stack Python with Flask* – End-to-end Flask web development training.

## Related Awesome Lists

- [Awesome Python](https://github.com/awesomelistsio/awesome-python)
- [Awesome Django](https://github.com/awesomelistsio/awesome-django)
- [Awesome APIs](https://github.com/awesomelistsio/awesome-apis)
- [Awesome Web Development](https://github.com/awesomelistsio/awesome-web-development)

## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
