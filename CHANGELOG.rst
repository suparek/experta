CHANGELOG
---------

1.9.4
~~~~~

* Resolved #10. Corner case in DepthStrategy in which the first
  activation of the agenda didn't get removed.


1.9.3
~~~~~

* Resolved #11 that was introduced with #7, that caused the same
  behavior under different conditions.


1.9.2
~~~~~

* Resolved #7. In some situations last activation was removed right
  after entering the agenda.


1.9.1
~~~~~

* Resolved #3. Rules should not be called with already retracted facts.


1.9.0
~~~~~

* Drop Python 3.4 support.
* Use setup.cfg to save all package metadata.


1.8.0-1.8.2
~~~~~~~~~~~

* Rebranded to Experta.


1.7.0
~~~~~

* Implemented the template system.
* Replaced warnings by watchers messages.
* Fixed freeze() with frozen objects.
* Fixed unfreeze() with unfrozen objects.
* Parametrized DefFacts via reset() kwargs.


1.6.0
~~~~~

* Improved overall performance.


1.5.0
~~~~~

* Added Python version 3.7 to tox.ini.
* Monkey and bananas example.
* Fixed bug, numeric index args gets repeated in a weird way introduced in `1.4.0`.
* Pass only the defined args in absence of kwargs.


1.4.0
~~~~~

* Order integer facts keys after making a copy.
* as_dict method for Fact.
* freeze and unfreeze method documentation.
* unfreeze method in pyknow.utils.
* Zebra example from Clips.


1.3.0
~~~~~

* `pyknow.operator` module.
* Nested matching.
* Added Talk 'Sistemas Expertos en Python con PyKnow - PyConES 2017' to docs
  folder.


1.2.0
~~~~~

* Freeze fact values as the default behavior to address Issue #9.
* Added `pyknow.utils.anyof` to mitigate Issue #7.
* Raise RuntimeError if a fact value is modified after declare().
* Added MATCH and AS objects.


1.1.1
~~~~~

* Removing the borg optimization for P field constraints.
* Use the hash of the check in the sorting of the nodes to always
  generate the same alpha part of the network.


1.1.0
~~~~~

* Allow any kind of callable in Predicate Field Constraints (P()).


1.0.1
~~~~~

* DNF of OR clause inside AND or Rule was implemented wrong.


1.0.0
~~~~~

* RETE matching algorithm.
* Better Rule decorator system.
* Facts are dictionaries.
* Documentation.


<1.0.0
~~~~~~

* Unestable API.
* Wrong matching algorithm.
* Bad performance
* PLEASE DON'T USE THIS.
