========
fail2ban
========

These states install an configure fail2ban.

init
----

Installs the `fail2ban` package and manages the service with the same name.

The local configuration :file:`/etc/fail2ban/jail.local` is created:

.. literalinclude:: jail.local
   :language: ini
   :linenos:
