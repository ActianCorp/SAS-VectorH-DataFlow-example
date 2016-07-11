# SAS-VectorH-and-DataFlow-Example

Raw data can be found at http://www.ucd.ie/issda/data/commissionforenergyregulationcer/ .
Data has been loaded as bz2 files to Actian's vmcluster at hdfs://usau-vm-demo-lead.datarush.local:8020/data/energy/zipped .
VectorH tables can be found in the demo database on usau-vm-demo-worker1.datarush.local .
The DataFlow workflow loads different tables than are used in the SAS demo so as not to modify those tables.
The DataFlow workflow and SAS code are attached to this git repository.

