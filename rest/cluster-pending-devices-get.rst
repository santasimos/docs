GET /rest/cluster/pending/devices
=================================

.. versionadded:: 1.13.0

Lists remote devices which have tried to connect, but are not yet
configured in our instance.

.. code-block:: json

    {
      "P56IOI7-MZJNU2Y-IQGDREY-DM2MGTI-MGL3BXN-PQ6W5BM-TBBZ4TJ-XZWICQ2": {
        "time": "2020-03-18T11:43:07Z",
        "name": "Friend Joe",
        "address": "192.168.1.2:22000"
      }
    }
