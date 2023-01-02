.. image:: https://img.shields.io/pypi/v/pmxbot.webhooks.svg
   :target: https://pypi.org/project/pmxbot.webhooks

.. image:: https://img.shields.io/pypi/pyversions/pmxbot.webhooks.svg

.. image:: https://github.com/jaraco/pmxbot.webhooks/workflows/tests/badge.svg
   :target: https://github.com/jaraco/pmxbot.webhooks/actions?query=workflow%3A%22tests%22
   :alt: tests

.. image:: https://img.shields.io/badge/code%20style-black-000000.svg
   :target: https://github.com/psf/black
   :alt: Code style: Black

.. .. image:: https://readthedocs.org/projects/skeleton/badge/?version=latest
..    :target: https://skeleton.readthedocs.io/en/latest/?badge=latest

.. image:: https://img.shields.io/badge/skeleton-2023-informational
   :target: https://blog.jaraco.com/skeleton

Webhooks for `pmxbot <https://pypi.org/project/pmxbot>`_. Read the source
for details.

Bookmarklet
===========

This lib provides a bookmarklet
for readily sending messages to the pmxbot HTTP interface. To install it,
just open /bookmarklet in the API service. It will present a link.
Option-click the link and add it to your bookmarks. Give it a name like
"Send to pmxbot".

To use the bookmarklet, browse to any web page, then select the bookmarklet.
You will be prompted with a dialog with a channel and message. Specify the
channel and optionally edit the message. Then hit Enter or click Submit and
that message will be broadcast on the channel indicated.
