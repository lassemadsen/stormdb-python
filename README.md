stormdb-python
==============

* Python classes for interacting with the STORM database at CFIN.
* A command-line utility (`submit_to_cluster`) for submitting commands for processing on the Hyades-cluster.

__NB! Help with documentation and examples needed!__

Submodule: access
-----------------

Home of the `Query`-object, used to send queries to the database (_e.g._, for the purpose of getting a list of included subjects).

```
from stormdb.access import Query
q = Query('MINDLAB20XX_MEG-YourProject')
subjects = q.get_subjects()
for sub in subjects:
  # do some work
```


Submodule: process
-----------------

NEEDS UPDATING, see also `doc`-folder

Install
-----------------
```
pip install git+https://github.com/lassemadsen/stormdb-python#egg=stormdb-python
```
