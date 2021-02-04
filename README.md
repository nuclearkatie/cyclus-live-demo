# Cyclus live demo

This repository contains the same files that will be replicated or used in the live demo. 

The requirements to run the Cyclus input files (.xml files) include 
- [Cyclus](https://github.com/cyclus/cyclus)
- [Cycamore](https://github.com/cyclus/cycamore)
- all their dependencies

It is recommended to install Cyclus from source, rather than through Conda.

Running a Cyclus input file

`cyclus path/to/input/file.xml`

Requirements to view output (.sqlite files)
- A SQLite browser/viewer application, such as [DB Browser for SQLite](https://sqlitebrowser.org/) (Windows, Mac, Linux) or an online viewer like [SQLite Viewer](https://inloop.github.io/sqlite-viewer/)

For additional analysis and manipulation,
- [Cymetric](https://github.com/cyclus/cymetric)
- [Python](https://www.python.org/)
- [Jupyter Notebook](https://jupyter.org/install). You can try Jupyter from your browser on [mybinder.org](https://jupyter.org/try)
- [PyNE](http://pyne.io/index.html)


Helpful links from the Cyclus homepage, fuelcycle.org
- [Understanding the Database](http://fuelcycle.org/user/dbdoc.html#explicit-inv-compact-table)