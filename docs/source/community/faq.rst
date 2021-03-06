Frequently Asked Questions
==========================

Why Python 3 only?
------------------

1. Python 3 has faster ``int`` <-> ``bytes`` conversion.
2. The official (really this time) EOL for Python 2 is the year 2020.
3. Polyglot is messy.

How so fast?
------------

Bit uses `pyca/cryptography <https://github.com/pyca/cryptography>`_ for most
cryptographic operations, which itself is a wrapper around
`OpenSSL <https://github.com/openssl/openssl>`_.

Why GitHub Pages instead of ReadtheDocs?
----------------------------------------

GitHub Pages has better page load times and is a bit more reliable. Also,
not only does `GitHub itself`_ use it, but other large projects like `React`_,
`Bootstrap`_, etc. do too.

I consider GitHub more future-proof.

.. _GitHub itself: https://github.com/blog/1939-how-github-uses-github-to-document-github
.. _React: https://github.com/facebook/react
.. _Bootstrap: https://github.com/twbs/bootstrap
