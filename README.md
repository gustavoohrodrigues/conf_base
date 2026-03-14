# Ansible Role: Base Configuration

This role performs baseline configuration for Linux servers before application deployment.

---

## 📌 Overview

The **conf_base** role prepares servers with common configuration used in infrastructure environments.

It is typically the **first role executed in automation pipelines**.

---

## 🚀 Features

* System preparation
* Base configuration
* Infrastructure standardization

---

## 🧰 Requirements

* Ansible >= 2.9
* Linux system

---

## ⚙️ Role Variables

Example variables:

```yaml
base_update_packages: true
base_timezone: UTC
```

---

## ▶️ Example Playbook

```yaml
- hosts: all
  become: true
  roles:
    - gustavoohrodrigues.conf_base
```

---

## 📦 Installation

```bash
ansible-galaxy install gustavoohrodrigues.conf_base
```

---

## Author

**Gustavo Henrique Rodrigues**
SysAdmin

LinkedIn
https://www.linkedin.com/in/gustavo-henrique-rodrigues-3070a5260

---

## 📜 License

MIT
