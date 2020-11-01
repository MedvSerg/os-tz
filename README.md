# os-tz
TZ for Ocean Studio

1) Change a list of sites in file inventory.cfg
   (Example - 192.192.192.192)

2) Change vars in file main.yml

  ( Example:

    user_name: "joe"
    db_name:   "joe"
    user_pass: "qq1"

  )

3) Run command:

  ansible-playbook -i inventory.cfg main.yml

