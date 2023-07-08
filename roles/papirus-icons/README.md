Papirus Icons
=========

This role will download and install papirus icons

Role Variables
--------------

| Name           | Default Value | Type  | Options  | Description                       |
| -------------- | ------------- | ----- | -------- |-----------------------------------|
| `icon_folder` | [`ePapirus`, `ePapirus-Dark`, `Papirus`, `Papirus-Dark`, `Papirus-Light`] | list | | list of current Papirus icons|
| `user_home` | test | string | | user home profile to save icons |

Dependencies
------------

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
- name: Install papirus icons
  hosts: localhost
  vars:
    user_home: marryjane
  roles:
    - papirus-icons
```

License
-------

TBC

Author Information
------------------

K11MY