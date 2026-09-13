---
title: "Homepage"
---

Homepage: [https://gethomepage.dev](https://gethomepage.dev)

Homepage is a highly customizable dashboard for your home server.

## Usage

Set `homepage_enabled: true` in your `inventories/<your_inventory>/group_vars/nas.yml` file.

The Homepage web interface can be found at [http://ansible_nas_host_or_ip:3000](http://ansible_nas_host_or_ip:3000).

Homepage stores its configuration in the role's `homepage_data_directory`. The Docker socket is mounted read-only to enable Docker integrations.
