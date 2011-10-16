Munin Theme Oxy
===============

This project is a [Munin](http://munin-monitoring.org/) theme customised by [Oxyva Webdesign
Purmerend](http://oxyva.nl). The Munin website describes Munin as follows:

    Munin is a networked resource monitoring tool that can help analyze
    resource trends and "what just happened to kill our performance?"
    problems. It is designed to be very plug and play. A default installation
    provides a lot of graphs with almost no work.

The Munin Theme Oxy offers a cleaner way of displaying the navigation bar, and
also offers iPad compatibility. It is also possible to add this theme to the
home screen on your iPad. In this case the theme offers a Munin shortcut icon.


Licence
=======

This program is free software: you can redistribute it and/or modify it under
the terms of the GNU General Public License as published by the Free Software
Foundation, either version 3 of the License, or (at your option) any later
version.

This program is distributed in the hope that it will be useful, but WITHOUT
ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS
FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with
this program. If not, see <http://www.gnu.org/licenses/>.


Installation
============

In Ubuntu Server, by default the Munin template is located in
/etc/munin/templates First backup your original theme by copying it to a temp
folder:

    mv /etc/munin/templates /etc/munin/templates-backup
    
Now copy the Munin Oxy Theme into the template folder:

    cp -r munin-theme-oxy/src /etc/munin/templates
    
You theme is now installed.