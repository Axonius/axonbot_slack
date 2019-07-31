.. include:: .special.rst

|MIT license|
|made-with-python|
|code-black|

Axonius Bot for Slack
##################################################################

This is a `Slack bot <https://api.slack.com/bot-users>`_ for `Axonius <https://axonius.com>`_.

It enables users in Slack to interact with an Axonius instance in a number of ways:

* Get a report of objects in JSON format sent to you in a new thread.
* You can search for user objects by username, email (using regex or not).
* You can search for device objects by hostname, IP address, or MAC address (using regex or not).
* You can search for user or device objects by a query built in the Query Wizard of the Axonius GUI.
* You can add or remove labels in the thread that is started up for returned objects.

To ask questions, request features, or report a bug:

* File an issue on the `Issue Tracker <https://github.com/Axonius/axonbot_slack/issues>`_
* Email apiclient@axonius.com

This is publicly available in a few places:

* `GitHub <https://github.com/Axonius/axonbot_slack>`_
* `Docker <https://hub.docker.com/r/axonius/axonbot_slack>`_
* `PyPi <https://pypi.org/project/axonbot-slack/>`_

Table of Contents
###############################################

.. toctree::
   :maxdepth: 3
   :numbered:

   prereq.rst
   install.rst
   variables_required.rst
   variables_optional.rst
   generate_slack_token.rst
   get_axonius_tokens.rst
   configure.rst
   changelog.rst
   todo.rst

Indices and tables
###############################################

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`


.. |MIT license| image:: https://img.shields.io/badge/License-MIT-blue.svg
   :target: https://lbesson.mit-license.org/

.. |made-with-python| image:: https://img.shields.io/badge/Made%20with-Python-1f425f.svg
   :target: https://www.python.org/

.. |code-black| image:: https://img.shields.io/badge/code%20style-black-000000.svg
   :target: https://github.com/python/black