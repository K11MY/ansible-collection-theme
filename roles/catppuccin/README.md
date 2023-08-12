Papirus Icons
=========

This role will download and install Catppuccin themes

Role Variables
--------------

| Name           | Default Value | Type  | Options  | Description                       |
| -------------- | ------------- | ----- | -------- |-----------------------------------|
| `user_home` | test | string | | user home profile to save icons |
| `color_variant` | frappe | string | `mocha` `frappe` `macchiato` `latte` `all` | colour variant |
| `accent` | rosewater | string | `rosewater` `flamingo` `pink` `mauve` `red` `maroon` `peach` `yellow` `green` `teal` `sky` `sapphire` `blue` `lavender` `all` | theme colour variant |
| `tweaks` | rimeless | string | `black` `rimless` `normal` `float` | specify version of tweaks |
| `user_home` | {{ user_home }}/cat_theme | string | | directory path to create cat_theme |

Dependencies
------------

Example Playbook
----------------

```yaml
- name: Install papirus icons
  hosts: localhost
  vars:
    user_home: marryjane
  roles:
    - catppuccin
```

License
-------

TBC

Author Information
------------------

K11MY
