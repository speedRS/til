# Enable DB2 Trace

1. Enable/disable trace:

       db2trc on -f trace.dmp
       db2start
       db2trc off

2. Extract relevant trace details to individual files:

       db2trc flw trace.dmp trace.flw
       db2trc fmt trace.dmp trace.fmt
