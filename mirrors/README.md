mirrors
=========

Configure system software mirrors that very useful in China.

Requirements
------------

None.

Role Variables
--------------

```yaml
# Choose one from sjtug, tuna or ustc.
mirror_site: tuna
```

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      become: true
      gather_facts: true 

      roles:
         - { role: mirrors }

License
-------

MIT/BSD

Author Information
------------------

剑十三

