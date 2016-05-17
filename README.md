Ansible Role for Usermin
========================

[![Build Status](https://travis-ci.org/pantarei/ansible-role-usermin.svg?branch=master)](https://travis-ci.org/pantarei/ansible-role-usermin)
[![GitHub tag](https://img.shields.io/github/tag/pantarei/ansible-role-usermin.svg)](https://github.com/pantarei/ansible-role-usermin)
[![GitHub license](https://img.shields.io/github/license/pantarei/ansible-role-usermin.svg)](https://github.com/pantarei/ansible-role-usermin/blob/master/LICENSE)

Ansible Role for Usermin Installation.

Requirements
------------

This role require Ansible 2.0 or higher.

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
<th>parameter</th>
<th>required</th>
<th>default</th>
<th>choices</th>
<th>comments</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>usermin_listen</td>
<td>yes</td>
<td>20000</td>
<td></td>
<td>Pass value as <code>listen</code> to <code>/etc/usermin/miniserv.conf</code>.</td>
</tr>
<tr class="even">
<td>usermin_port</td>
<td>yes</td>
<td>20000</td>
<td></td>
<td>Pass value as <code>port</code> to <code>/etc/usermin/miniserv.conf</code>.</td>
</tr>
<tr class="odd">
<td>usermin_ssl</td>
<td>yes</td>
<td>1</td>
<td></td>
<td>Pass value as <code>ssl</code> to <code>/etc/usermin/miniserv.conf</code>.</td>
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
    -   <a href="https://twitter.com/hswong3i" class="uri" class="uri">https://twitter.com/hswong3i</a>
    -   <a href="https://github.com/hswong3i" class="uri" class="uri">https://github.com/hswong3i</a>

