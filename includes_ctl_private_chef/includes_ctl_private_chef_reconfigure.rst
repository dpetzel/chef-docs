.. The contents of this file are included in multiple topics.
.. This file describes a command or a sub-command for Knife.
.. This file should not be changed in a way that hinders its ability to appear in multiple documentation sets.


The ``reconfigure`` subcommand is used when changes are made to the |enterprise rb| file to reconfigure the server. When changes are made to the |enterprise rb| file, they will not be applied to the |chef server oec| configuration until after this command is run. This subcommand will also restart any services for which the ``service_name['enabled']`` setting is set to ``true``.

This subcommand has the following syntax:

.. code-block:: bash

   $ private-chef-ctl reconfigure



