# Role Name
![](https://i.imgur.com/waxVImv.png)
### [View all Roadmaps](https://github.com/nholuongut/all-roadmaps) &nbsp;&middot;&nbsp; [Best Practices](https://github.com/nholuongut/all-roadmaps/blob/main/public/best-practices/) &nbsp;&middot;&nbsp; [Questions](https://www.linkedin.com/in/nholuong/)
<br/>

Installation of bits from Docker, Inc. useful in running a Docker host.

Requirements
------------

TODO

Role Variables
--------------

* docker_engine_install: true
* docker_engine_install_via_script: true
* docker_engine_install_version: 1.12.5
* docker_engine_graph: /var/lib/docker
* docker_engine_storage_driver: overlay2
* docker_engine_log_size: 1g
* docker_compose_install: true
* docker_compose_version: 1.9.0
* docker_machine_install: true
* docker_machine_version: 0.8.2

Dependencies
------------

* kurron.base

Example Playbook
----------------

```
- hosts: servers
  roles:
      - { role: kurron.docker-host, docker_engine_storage_driver: overlay2 }
```

To not use Docker installation script so a specific version can be installed:

```
- hosts: servers
  roles:
      - { role: kurron.docker-host, docker_engine_install_via_script: false, docker_engine_install_version: 1.11.0 }
```

# 🚀 I'm are always open to your feedback.  Please contact as bellow information:
### [Contact ]
* [Name: nho Luong]
* [Skype](luongutnho_skype)
* [Github](https://github.com/nholuongut/)
* [Linkedin](https://www.linkedin.com/in/nholuong/)
* [Email Address](luongutnho@hotmail.com)

![](https://i.imgur.com/waxVImv.png)
![](Donate.png)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nholuong)

# License
* Nho Luong (c). All Rights Reserved.🌟
