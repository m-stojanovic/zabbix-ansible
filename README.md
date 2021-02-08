<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [Contact](#contact)



<!-- ABOUT THE PROJECT -->
## About The Project

Zabbix ansible role that both zabbix-server and zabbix-agent configuration on Debian systems with mysql and nginx setup.
Some custom vars are needed to be defined within project.

### Built With

* [Ansible](https://ansible.com)
* [Yaml](https://yaml.com)
* [Zabbix](https://zabbix.com)


## Getting Started

ansible-playbook -i {{ your_inventory_file }} zabbix_server|agent.yml


### Prerequisites

Ansible version 2.9.0 +

<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/m-stojanovic/zabbix-ansible/issues) for a list of proposed features (and known issues).

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


<!-- CONTACT -->
## Contact

Milos Stojanovic - [@linkedin](https://www.linkedin.com/in/infomilosstojanovic/)

Project Link: [https://github.com/m-stojanovic/zabbix-ansible](https://github.com/m-stojanovic/zabbix-ansible)
