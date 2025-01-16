# learn-ansible

For Inventory:

[APP]
10.0.0.5
10.0.0.6

[DB]
10.0.0.9 URL = "https://google.com"
10.0.010


# Command : ansible -i inventory APP --list-hosts
# Displays only APP servers
# Ansible best practices

Dynamic Inventory
