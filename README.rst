Openupgrade buildout
====================

This repository contains a buildout. Prepare it by running::

    python bootstrap.py

and then run it with::

    bin/buildout -c dev.cfg  (for development environment)

    bin/buildout -c prod.cfg  (for production environment)

After that, you can run the actual migration::

    ./migrate.sh your_database_name
