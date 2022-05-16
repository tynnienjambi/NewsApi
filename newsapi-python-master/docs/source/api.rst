.. _api:

API Reference
=============

.. module:: NewsApi

This page is a technical reference to the public classes, exceptions, and data
defined in newsapi-python.

While newsapi-python makes every effort to keep up with the API,
please consider the official News API `docs <https://NewsApi.org/docs>`_
as the canonical News API reference.

Classes
-------

.. autoclass:: NewsApi.NewsApiClient
   :members:

Exceptions
----------

.. autoexception:: NewsApi.NewsApi_exception.NewsAPIException

Constants
---------

The :mod:`NewsApi.const` module holds constants and allowed parameter values specified in the official News API documentation.

.. autodata:: NewsApi.const.languages

.. autodata:: NewsApi.const.countries

.. autodata:: NewsApi.const.categories

.. autodata:: NewsApi.const.sort_method
