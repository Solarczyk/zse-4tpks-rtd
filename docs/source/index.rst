Dokumentacja Read The Docs
==========================

**RtD** (/lu'make/) jest darmowym programem do generowania dokumentacji. 
Program pozwala nam na łatwe sporządzenie dokumentacji, a także 
pozwala nam na łatwe utworzenie strony z dokumentacją. Dzięki
Read The Docs tworzenie dokumentacji jest jak tworzenie dokumentacji, ale
na platformie Read The Docs. 

Odwiedź stronę :doc:`Składnia RtD` by poznać składnię programu Read the docs


.. toctree::
   :maxdepth: 1

   Składnia RsT
   O Autorze


Składnia RsT
------------


Nagłówek tekstowy poziomu I
~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. code-block::

   Nagłówek
   ========


Nagłówek tekstowy poziomu II
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. code-block::

   Nagłówek
   --------

   
Nagłówek tekstowy poziomu III
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. code-block::

   Nagłówek
   ~~~~~~~~


Nagłówek tekstowy poziomu IV
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. code-block::

   Nagłówek
   ^^^^^^^^


Akapit tekstowy
~~~~~~~~~~~~~~~

.. code-block::

       Akapit tekstowy

Akapit tekstowy

Akapit informacyjny - Note
~~~~~~~~~~~~~~~~~~~~~~~~~~

.. code-block::

       .. note::

          Akapit informacyjny

.. note::

   Akapit informacyjny

Akapit informacyjny - Tip
~~~~~~~~~~~~~~~~~~~~~~~~~

.. code-block::

       .. tip::

          Akapit informacyjny

.. tip::

   Akapit informacyjny

Fragment kodu - liniowy
~~~~~~~~~~~~~~~~~~~~~~~

.. code-block::

       .. code-block::
          ``Fragment kodu``

``Fragment kodu``

Fragment kodu - blokowy
~~~~~~~~~~~~~~~~~~~~~~~

.. code-block::

       .. code-block::

          Fragment kodu

Odnośnik wewnętrzny (w obrębie dokumentacji)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. code-block::

       The output of this line has no spaces at the beginning.

Odnośnik zewnętrzny (do innego serwisu)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. code-block::

       The output of this line has no spaces at the beginning.

Lista numerowana
~~~~~~~~~~~~~~~~

.. code-block::

   #. Element 1
   #. Element 2
   itd...

#. Element 1
#. Element 2

Lista wypunktowana
~~~~~~~~~~~~~~~~~~

.. code-block::

   * Element 1
   * Element 2
   itd...

* Element 1
* Element 2

Lista definicji
~~~~~~~~~~~~~~~

.. code-block::

       Określenie (max w jednej linii)
          Definicja

Określenie
   Definicja
         
Obraz
~~~~~

.. code-block::

       The output of this line has no spaces at the beginning.

Tabela z danymi
~~~~~~~~~~~~~~~

.. code-block::

       The output of this line has no spaces at the beginning.

Lista Zadań wykonanych i niewykonanych
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. code-block::

       The output of this line has no spaces at the beginning.
