Deprecated Features
===================

This document lists all deprecated features in Twig 1.x. They are kept for
backward compatibility but they will be removed in Twig 2.0.

Token Parsers
-------------

* The token parser broker sub-system is deprecated; the following class and
  interface will be removed in 2.0:

  * ``Twig_TokenParserBrokerInterface``
  * ``Twig_TokenParserBroker``

Extensions
----------

* The ability to remove an extension is deprecated and the
  ``Twig_Environment::removeExtension()`` method will be removed in 2.0.

Filters
-------

* When adding a filter, use the ``Twig_SimpleFilter`` class; the following
  classes and interfaces will be removed in 2.0:

  * ``Twig_FilterInterface``
  * ``Twig_FilterCallableInterface``
  * ``Twig_Filter``
  * ``Twig_Filter_Function``
  * ``Twig_Filter_Method``
  * ``Twig_Filter_Node``

* When adding a function, use the ``Twig_SimpleFunction`` class; the following
  classes and interfaces will be removed in 2.0:

  * ``Twig_FunctionInterface``
  * ``Twig_FunctionCallableInterface``
  * ``Twig_Function``
  * ``Twig_Function_Function``
  * ``Twig_Function_Method``
  * ``Twig_Function_Node``

* When adding a test, use the ``Twig_SimpleTest`` class; the following classes
  and interfaces will be removed in 2.0:

  * ``Twig_TestInterface``
  * ``Twig_TestCallableInterface``
  * ``Twig_Test``
  * ``Twig_Test_Function``
  * ``Twig_Test_Method``
  * ``Twig_Test_Node``
