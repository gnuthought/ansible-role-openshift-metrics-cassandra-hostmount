Role Name
=========

An Ansible role for configuring hostmount for cassadra database.

Requirements
------------

OCP 3.3 or 3.4

Role Variables
--------------

* `openshift_metrics_cassandra_hostmount_path` - Host path for cassandra

* `openshift_metrics_cassandra_nodeselector` - Node selector for cassandra placement

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - role: openshift-metrics-cassandra-hostmount

License
-------

BSD

Author Information
------------------

Johnathan Kupferer (jkupfere@redhat.com)
