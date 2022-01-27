|Latest Version| |Supported Python versions| |Wheel format| |License|
|Development Status| |Downloads monthly| |Build Status|

cudf\_talib
=============

A faster talib (A Python Pandas implementation of technical indicators) interpretation built for speed with cudf instead of pandas.

Original version from:

-  `Bruno Franca <https://github.com/brunogfranca>`__

-  `panpanpandas <https://github.com/panpanpandas>`__

-  `Peter
   Bakker <https://www.quantopian.com/users/51d125a71144e60865000044>`__

Contributors

-  `Yao Hong Kok <https://github.com/yaohongkok>`__
- `Leonardo Lazzaro <https://github.com/llazzaro>`__
- `and all... <https://github.com/femtotrader/pandas_talib/graphs/contributors>`__

See also:

-  `panpanpandas/ultrafinance <https://github.com/panpanpandas/ultrafinance>`__

-  `llazzaro/analyzer <https://github.com/llazzaro/analyzer>`__

-  https://www.quantopian.com/posts/technical-analysis-indicators-without-talib-code

If you are looking for a more complete set of technical indicators you
might have a look at this TA-Lib Python wrapper:
https://github.com/mrjbq7/ta-lib

Development
-----------

You can help to develop this library.

Issues
~~~~~~

You can submit issues using
https://github.com/femtotrader/pandas_talib/issues

Clone
~~~~~

You can clone repository to try to fix issues yourself using:

::

    $ git clone https://github.com/femtotrader/pandas_talib.git

Run unit tests
~~~~~~~~~~~~~~

Follow instructions from TA-Lib and install it:

https://github.com/mrjbq7/ta-lib

Run all unit tests

::

    $ nosetests -s -v

Run a given test

::

    $ nosetests tests.test_pandas_talib:test_indicator_MA -s -v

Run samples
~~~~~~~~~~~

Run ``samples/main.py`` (from project root directory)

::

    $ python samples/main.py

Install development version
~~~~~~~~~~~~~~~~~~~~~~~~~~~

::

    $ python setup.py install

or

::

    $ sudo pip install git+https://github.com/femtotrader/pandas_talib.git

Known Issues
~~~~~~~~~~~~~

- The method ROC is currently not accurate yet.
