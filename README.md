Ansible Role for CacheFiles
===========================

[![Build Status](https://travis-ci.org/pantarei/ansible-role-cachefilesd.svg?branch=master)](https://travis-ci.org/pantarei/ansible-role-cachefilesd)
[![GitHub tag](https://img.shields.io/github/tag/pantarei/ansible-role-cachefilesd.svg)](https://github.com/pantarei/ansible-role-cachefilesd)
[![GitHub license](https://img.shields.io/github/license/pantarei/ansible-role-cachefilesd.svg)](https://github.com/pantarei/ansible-role-cachefilesd/blob/master/LICENSE)

Ansible Role for CacheFiles Installation.

Requirements
------------

This role require Ansible 2.0 or higher.

This role was designed for Ubuntu Server 14.04 LTS and Ubuntu Server 16.04 LTS.

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
<td>cachefilesd_daemon_opts</td>
<td>yes</td>
<td></td>
<td></td>
<td>Additional options that are passed to the Daemon.</td>
</tr>
<tr class="even">
<td>cachefilesd_die_time</td>
<td>yes</td>
<td>10</td>
<td></td>
<td>Time to wait for the server to die, in seconds.</td>
</tr>
<tr class="odd">
<td>cachefilesd_start_time</td>
<td>yes</td>
<td>2</td>
<td></td>
<td>Time to wait for the server to start, in seconds.</td>
</tr>
</tbody>
</table>

Dependencies
------------

No additional role dependencies.

Example Playbook
----------------

    - hosts: all
      roles:
        - role: hswong3i.cachefilesd

License
-------

-   Code released under [MIT](https://github.com/pantarei/ansible-role-cachefilesd/blob/master/LICENSE)
-   Docs released under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)

Author Information
------------------

-   Wong Hoi Sing Edison
    -   <a href="https://twitter.com/hswong3i" class="uri" class="uri">https://twitter.com/hswong3i</a>
    -   <a href="https://github.com/hswong3i" class="uri" class="uri">https://github.com/hswong3i</a>

