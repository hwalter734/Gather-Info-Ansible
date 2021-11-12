# Gather-Apps-Ansible
A repository responsible for retrieving installed applications on the given hosts.

# Repository structure

## .SQL Script Files
* create_table_apps.sql: Creates the serversinfo table, which holds all the information of the applications info on every server.
* create_table_facts.sql: Creates the serversdata table, which holds all the information of server facts alongside personalized facts.
* insert_data_facts.sql: Inserts facts data into the serversdata table.
* insert_data_apps.sql: Inserts apps data into the serversinfo table.

