# usergrant

Temporarily grant ACLs and environment to a secondary user for the duration of a command

## What

Normally, systemd grants udev access to certain devices via a `uaccess` tag, but this tag
is only available to users on a physical seat.

If you run "secondary" or "delegated" users, you cannot use this.

Yes you can setup udev rules, but sometimes you just want a quick one-off
Plus, writing a script is fun.

## Issues

Check the issues page on GitHub for any notes about outstanding or existing
issues. If you encounter a problem with `usergrant` of which no such
issue already exists please feel free to help the developer by creating an
issue ticket.

## License

GPLv2

```
  The GPLv2 License

    Copyright (C) 2025 pyamsoft

    This program is free software; you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation; either version 2 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License along
    with this program; if not, write to the Free Software Foundation, Inc.,
    51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA.
```
