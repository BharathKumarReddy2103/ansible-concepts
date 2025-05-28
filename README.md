# Ansible Practice Repository

Welcome to the **Ansible Practice Repository** 🛠️  

This repository is maintained by Bharath Kumar Reddy (https://www.linkedin.com/in/bharath-kumar-reddy2103) — a Senior DevOps & DataOps Engineer — to explore, practice, and demonstrate real-world use cases of **Ansible** for DevOps automation and configuration management.

---

## 📌 Repository Purpose

This repository serves as a hands-on learning space for:
- Practicing Ansible playbooks, roles, and modules
- Automating infrastructure provisioning and configuration
- Managing servers in a repeatable, idempotent way
- Preparing for DevOps interviews and certifications
- Sharing reusable Ansible scripts for the DevOps community

---

## 📂 Folder Structure

```bash
Ansible-Practice/
├── 01-playbook.yaml             # Basic Ansible playbook structure
├── 02-hello-world.yaml          # Hello World example
├── 03-nginx.yaml                # Start and manage nginx service
├── 04-multi-play.yaml           # Multi-playbook example
├── 05-play-vars.yaml            # Define variables at play level
├── 06-tasks-vars.yaml           # Define variables at task level
├── 07-vars-file.yaml            # Load variables from an external file
├── 08-vars-prompt.yaml          # Use prompt to get variables at runtime
├── 09-vars-inventory.yaml       # Variables defined in inventory
├── 10-vars-inventory.yaml       # Another example of inventory variables
├── 11-vars-args.yaml            # Pass variables using --extra-vars
├── 12-vars-preference.yaml      # Precedence of variables
├── 13-data-types.yaml           # YAML data types in Ansible
├── 14-conditions.yaml           # Conditional task execution
├── course.yaml                  # Variable file used by playbooks
└── inventory.ini                # Static inventory file
````

> 🔄 New examples and modules will be added regularly.

---

## ✅ Prerequisites

To run the playbooks in this repository, make sure you have:

* Ansible installed (`ansible --version`)
* Access to one or more Linux target machines (or localhost)
* SSH connectivity to target nodes
* Proper inventory setup (`inventory.ini` or dynamic inventory)

---

## 🚀 How to Run a Playbook

```bash
# Navigate to the repo directory
cd Ansible-Practice/

# Run a specific playbook
ansible-playbook -i inventory.ini 03-nginx.yaml
```

To pass extra variables:

```bash
ansible-playbook 11-vars-args.yaml -e "COURSE=DevOps DURATION=100"
```

---

## 📘 Topics Covered

* Ansible Playbook Fundamentals
* Variable Scopes and Precedence
* External Variable Files and Prompts
* Conditional Execution
* Data Types in YAML
* Inventory-based Variables
* Task vs Play-Level Variables
* Real-world Use Cases for Automation

---

## 🌐 Author

**Bharath Kumar Reddy**
Senior DevOps & DataOps Engineer

* 💼 [LinkedIn](https://www.linkedin.com/in/bharath-kumar-reddy2103)
* 🐙 [GitHub](https://github.com/BharathKumarReddy2103)

---

## 🤝 Contributions

This is a personal practice repository, but feel free to fork, star ⭐, or raise issues if you find bugs or want to collaborate.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

> 🚧 *This repository is under active development — more advanced examples and role-based projects will be added soon.*
