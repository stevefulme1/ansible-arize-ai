> **EXPERIMENTAL** - This collection is a proof of concept and is not production ready.
> Modules may use placeholder API endpoints and have not been validated against real infrastructure.
> Do not use in production environments.

# Arize AI Ansible Collection

Ansible Collection for Arize AI model observability platform. Provides modules for managing models, monitors, dashboards, embeddings, custom metrics, and alert rules via the Arize REST API.

## Requirements

- Ansible >= 2.16
- Python >= 3.9
- `requests` Python library

## Installation

```bash
ansible-galaxy collection install stevefulme1.arize_ai
```

## Modules

- `stevefulme1.arize_ai.model` - Manage models in Arize AI
- `stevefulme1.arize_ai.model_info` - Retrieve model information from Arize AI
- `stevefulme1.arize_ai.monitor` - Manage monitors in Arize AI
- `stevefulme1.arize_ai.monitor_info` - Retrieve monitor information from Arize AI
- `stevefulme1.arize_ai.dashboard` - Manage dashboards in Arize AI
- `stevefulme1.arize_ai.dashboard_info` - Retrieve dashboard information from Arize AI
- `stevefulme1.arize_ai.embedding` - Manage embedding configurations in Arize AI
- `stevefulme1.arize_ai.embedding_info` - Retrieve embedding information from Arize AI
- `stevefulme1.arize_ai.custom_metric` - Manage custom metrics in Arize AI
- `stevefulme1.arize_ai.custom_metric_info` - Retrieve custom metric information from Arize AI
- `stevefulme1.arize_ai.alert_rule` - Manage alert rules in Arize AI
- `stevefulme1.arize_ai.alert_rule_info` - Retrieve alert rule information from Arize AI

## Roles

- `arize_setup` - Install and configure Arize AI integration
- `arize_monitor_deploy` - Deploy monitoring configuration for Arize AI models

## Event-Driven Ansible

- `arize_alerts` - Arize AI Alerts event source plugin

## License

GPL-3.0-or-later

## Author

Steve Fulmer ([@stevefulme1](https://github.com/stevefulme1))
