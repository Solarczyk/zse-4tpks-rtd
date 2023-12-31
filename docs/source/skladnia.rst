
Składnia RsT
============

Nagłówek tekstowy poziomu I
---------------------------

.. code-block::

   Nagłówek
   ========


Nagłówek tekstowy poziomu II
----------------------------

.. code-block::

   Nagłówek
   --------

   
Nagłówek tekstowy poziomu III
-----------------------------

.. code-block::

   Nagłówek
   ~~~~~~~~


Nagłówek tekstowy poziomu IV
----------------------------
.. code-block::

   Nagłówek
   ^^^^^^^^

Akapit tekstowy
---------------

.. code-block::

       Akapit tekstowy

Akapit tekstowy

Akapit informacyjny - Note
--------------------------

.. code-block::

       .. note::

          Akapit informacyjny

.. note::

   Akapit informacyjny

Akapit informacyjny - Tip
-------------------------

.. code-block::

       .. tip::

          Akapit informacyjny

.. tip::

   Akapit informacyjny

Fragment kodu - liniowy
-----------------------

.. code-block::

       .. code-block::
          ``Fragment kodu``

``Fragment kodu``

Fragment kodu - blokowy
-----------------------

.. code-block::

       .. code-block::

          Fragment kodu

.. _etykieta:

Odnośnik wewnętrzny (w obrębie dokumentacji)
--------------------------------------------

.. code-block::

       .. _etykieta:

            Sekcja do odniesienia
            ---------------------
            
      Odnośnik do sekcji :ref:`tekst odnośnika<etykieta>'.

Odnośnik wewnętrzny: :ref:`odnośnik<etykieta>`.

Odnośnik zewnętrzny (do innego serwisu)
---------------------------------------

.. code-block::

   `Tekst odnośnika <link>`_

`Tekst odnośnika <https://github.com/Solarczyk/zse-docs-gh/wiki/Spis-tre%C5%9Bci>`_

Lista numerowana
----------------

.. code-block::

   #. Element 1
   #. Element 2
   itd...

#. Element 1
#. Element 2

Lista wypunktowana
------------------

.. code-block::

   * Element 1
   * Element 2
   itd...

* Element 1
* Element 2

Lista definicji
---------------

.. code-block::

       Określenie (max w jednej linii)
          Definicja

Określenie
   Definicja
         
Obraz
-----

.. code-block::

   .. figure:: ścieżka do zdjęcia
      :width: x%
      :align: center
      :alt: tekst alternatywny

      Podpis pod obrazkiem

.. figure:: examp.png
   :width: 80%
   :align: center
   :alt: tekst alternatywny

   Podpis pod obrazkiem

Tabela z danymi
---------------

.. code-block::

       ======== ========
       Kolumna1 Kolumna2
       ======== ========
       Element1 Element1
       Element2 Element2
       Element3 Element3
       ======== ========

======== ========
Kolumna1 Kolumna2
======== ========
Element1 Element1
Element2 Element2
Element3 Element3
======== ========
