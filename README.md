# ansible.yml
ansible code
  - hosts: apache
    tasks:
      - name: run echo command
        command: /bin/echo hello world
