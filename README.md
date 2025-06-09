# Ansible Real-World-Concepts

This repository is a real-time implementation of Ansible automation workflows. It reflects the kind of work I perform in my current role as a DevOps Engineer—covering core and advanced concepts such as **variables, loops, conditionals, roles, templates, error handling, and more**.

> 🚀 This project simulates how Ansible is used in actual DevOps environments to automate server provisioning, application setup, and cloud configuration management using a modular and production-like approach.

---

## 🎯 Project Objectives

- Demonstrate real-time usage of Ansible in infrastructure automation
- Show best practices with modular roles, secure vault integration, and reusable playbooks
- Help DevOps Engineers, learners, and professionals apply concepts in real-world projects

---

## 📚 Real-Time Ansible Concepts Covered

| Concept              | Description                                                                 |
|----------------------|-----------------------------------------------------------------------------|
| `vars`               | Group vars, host vars, defaults, and variable precedence                    |
| `loops`              | Iterating over lists, maps, files, and dynamic content                      |
| `conditionals`       | When conditions and register results to control task execution              |
| `handlers`           | Task triggers for service reloads and restarts                              |
| `tags`               | Run selected tasks using tags for faster deployments                        |
| `templates`          | Jinja2-based configuration file generation                                  |
| `vault`              | Securely storing sensitive information like passwords and keys              |
| `roles`              | Structuring reusable code using Ansible roles                               |
| `dynamic inventory`  | Using AWS EC2 dynamic inventory plugin                                       |
| `error handling`     | Using `ignore_errors`, `block/rescue`, and `failed_when`                    |
| `crontab`            | Scheduling jobs via Ansible                                                 |
| `ad-hoc commands`    | Running one-off tasks on multiple machines                                  |
| `project configuration` | Setting up entire services or apps via structured playbooks             |
| `ansible installation`| Setting up Ansible and verifying connectivity                              |

---

## 🗂️ Repository Structure

```

Ansible-Practice/
├── group\_vars/
├── host\_vars/
├── roles/
│   ├── common/
│   ├── webserver/
│   └── database/
├── playbooks/
│   ├── site.yml
│   └── db.yml
├── inventory/
│   ├── hosts.ini
│   └── aws\_ec2.yaml
├── vault/
│   └── secrets.yml
├── templates/
│   └── nginx.conf.j2
├── crontab/
│   └── system-jobs.yml
└── README.md

````

---

## 🛠️ Sample Use Cases Covered

- Deploying a multi-tier application using modular roles
- Installing and configuring Nginx, MySQL using templates and handlers
- Securing credentials using Ansible Vault
- Managing users, packages, and scheduled tasks (cron jobs)
- Automating EC2 server management using dynamic inventory

---

## 💡 How to Use This Repository

1. Clone this repo
2. Install Ansible (if not already)
3. Configure your inventory and vault
4. Run a playbook:

```bash
ansible-playbook -i inventory/hosts.ini playbooks/site.yml --ask-vault-pass
````

---

## ✅ Prerequisites

* Ansible 2.9+
* Python & Boto (for AWS inventory)
* AWS credentials (for dynamic inventory testing)
* Encrypted vault password (to run sensitive configurations)

---

## 📬 Connect with Me

Feel free to reach out or follow my DevOps content:

* [LinkedIn Profile](https://www.linkedin.com/in/bharath-kumar-reddy2103/)
* [GitHub Profile](https://github.com/BharathKumarReddy2103)
