Ansible Role for Usermin
========================

[![Build Status](https://travis-ci.org/pantarei/ansible-role-usermin.svg?branch=master)](https://travis-ci.org/pantarei/ansible-role-usermin)
 [![GitHub tag](https://img.shields.io/github/tag/pantarei/ansible-role-usermin.svg)](https://github.com/pantarei/ansible-role-usermin)
 [![GitHub license](https://img.shields.io/github/license/pantarei/ansible-role-usermin.svg)](https://github.com/pantarei/ansible-role-usermin/blob/master/LICENSE)
 [![Ansible Role](https://img.shields.io/ansible/role/6235.svg)](https://galaxy.ansible.com/detail#/role/6235)

Ansible Role for Usermin Installation.

Requirements
------------

This role require Ansible 1.9 or higher.

This role was designed for Ubuntu Server 14.04 LTS.

Role Variables
--------------

<table>
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">parameter</th>
<th align="left">required</th>
<th align="left">default</th>
<th align="left">choices</th>
<th align="left">comments</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">usermin_listen</td>
<td align="left">yes</td>
<td align="left">20000</td>
<td align="left"></td>
<td align="left">Pass value as <code>listen</code> to <code>/etc/usermin/miniserv.conf</code>.</td>
</tr>
<tr class="even">
<td align="left">usermin_port</td>
<td align="left">yes</td>
<td align="left">20000</td>
<td align="left"></td>
<td align="left">Pass value as <code>port</code> to <code>/etc/usermin/miniserv.conf</code>.</td>
</tr>
<tr class="odd">
<td align="left">usermin_ssl</td>
<td align="left">yes</td>
<td align="left">1</td>
<td align="left"></td>
<td align="left">Pass value as <code>ssl</code> to <code>/etc/usermin/miniserv.conf</code>.</td>
</tr>
</tbody>
</table>

Dependencies
------------

No additional role dependencies.

Example Playbook
----------------

    - hosts: servers
      roles:
        - { role: hswong3i.usermin }

License
-------

-   Code released under [MIT](https://github.com/pantarei/ansible-role-usermin/blob/master/LICENSE)
-   Docs released under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)

Author Information
------------------

-   Wong Hoi Sing Edison
    -   <https://twitter.com/hswong3i>
    -   <https://github.com/hswong3i>

