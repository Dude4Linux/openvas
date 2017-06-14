OpenVAS - Descriptive Title
=======================================

`OpenVAS`_ is an advanced open source vulnerability scanner and manager licensed under the GPL.

Description or Purpose
----------------------
.. Briefly describe what the appliance does 

OpenVAS is a framework of several services and tools offering a comprehensive and powerful vulnerability scanning and vulnerability management solution. The framework is part of Greenbone Networks' commercial vulnerability management solution from which developments are contributed to the Open Source community since 2009.

This appliance includes all the standard features in `TurnKey Core`_,
and on top of that:

Additional Features
-------------------
.. Add or remove additional features from the list below

- SSL support out of the box.
- Postfix MTA (bound to localhost) to allow sending of email (e.g.,
  password recovery).
- Webmin modules for configuring Apache2, PHP and Postfix.

Credentials *(passwords set at first boot)*
-------------------------------------------

-  Webmin, SSH, ShellInABox: username **root**

.. Edit above to remove references to MySQL, phpMyAdmin, etc if not used in your appliance.  Add a line for additional application credentials, if any, set at first boot.

.. _OpenVAS: http://www.openvas.org
.. _TurnKey Core: http://www.turnkeylinux.org/core
