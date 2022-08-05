==========
Quickstart
==========

.. code-block:: bash

    ussocdata [foo,bar] [-del] [-foo:foo,bar] [-bar:foo,bar]

** Warning dont do this other thing **

default options are:

.. code-block:: bash

    -foo:foo
    -bar:

Examples:

.. code-block:: bash

    # Do this
    ussocdata foo -del -foo:bar -bar:foo
    # Do that
    ussocdata bar -foo:foo

More examples in :doc:`use_cases`