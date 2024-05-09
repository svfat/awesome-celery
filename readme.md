# Awesome Celery [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> The Awesome Celery list is a curated collection of open source resources, tools, and libraries for the Python Celery task queue. The list includes libraries and tools to make working with Celery easier, as well as interesting projects and examples. Whether you&#39;re new to Celery or an experienced developer, the list has something for everyone.


## Contents

- [General](#general)
- [Administration and Monitoring](#administration-and-monitoring)
- [Analogues](#analogues)
- [Task flow and organization](#task-flow-and-organization)
- [Implementation in different languages](#implementation-in-different-languages)

## General

General Celery related items.

- [Celery documentation](https://docs.celeryq.dev/en/stable/) - Documentation on Celery Framework.
- [Celery GitHub](https://github.com/celery/celery) - Celery source code.
- [Celery Pytest Plugin](https://pytest-celery.readthedocs.io) - Official pytest plugin for Celery.
- [celery-tasks-checklist](https://github.com/vintasoftware/celery-tasks-checklist) - Useful checklist for building great Celery tasks.

## Administration and Monitoring

- [Celery Insights](https://github.com/danyi1212/celery-insights) - Realtime monitoring tool for Celery clusters with a modern web UI.
- [Flower](https://github.com/mher/flower) - Web-based tool for managing and administering Celery clusters.
- [Leek](https://github.com/kodless/leek) - Monitoring tool that can monitor multiple brokers with a single container, unlike other tools.
- [django-celery-beat](https://github.com/celery/django-celery-beat) - Running periodic tasks from Django Admin.
- [celery-progress](https://github.com/czue/celery-progress) - Download progress bar for Django/Celery.
- [django-celery-results](https://github.com/celery/django-celery-results) - Storing task results using the Django ORM.
- [django-health-check](https://github.com/revsys/django-health-check) - Health check plugin for Django. Celery health checks are bundled.
- [clearly](https://github.com/rsalmei/clearly) - Console worker monitoring/inspecting/debugging.
- [celery-exporter](https://github.com/danihodovic/celery-exporter) - A Prometheus exporter for Celery.
- [celery-mixin](https://github.com/danihodovic/celery-exporter/tree/master/celery-mixin) - Monitoring mixin for Celery. A set of Grafana dashboards and Prometheus rules for Celery.

## Analogues

- [RQ](https://github.com/rq/rq) - Simple, lightweight, Python library for creating background jobs, and processing them.
- [WakaQ](https://github.com/wakatime/wakaq) - Minimalistic alternative to Celery.
- [aiotasks](https://github.com/cr0hn/aiotasks) - Celery-like task queue but for asyncronous functions.
- [TaskTiger](https://github.com/closeio/tasktiger) - Task management using Redis.

## Task flow and organization
- [Selinon](https://github.com/selinon/selinon) - Advanced flow control with dynamic task scheduling and declarative YAML configs.
- [celery-director](https://github.com/ovh/celery-director) - YAML workflows for Celery tasks and WebUI to run them.
- [celery-once](https://github.com/cameronmaske/celery-once) - Prevent multiple execution of celery tasks.
- [Jobtastic](https://github.com/PolicyStat/jobtastic) - Implement progress, status, caching, error handling with simple wrappers.
- [RedBeat](https://github.com/sibson/redbeat) - Celery Beat Scheduler that stores the scheduled tasks and runtime metadata in Redis.

## Implementation in different languages
- [Rusty Celery](https://github.com/rusty-celery/rusty-celery) - Rust implementation.
- [gocelery](https://github.com/gocelery/gocelery) - Go Client/Server for Celery Distributed Task Queue.
- [celery.node](https://github.com/actumn/celery.node) - Celery client/worker implementation in Node.js.

Contributions are always welcome! Read the [contribution guidelines](contributing.md) first.
