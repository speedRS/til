# Enable DB2 Trace

1.  Enable/disable trace:

       ``` shell
       db2trc on -f trace.dmp
       db2start
       db2trc off
       ```

2.  Extract relevant trace details to individual files:

       ``` shell
       db2trc flw trace.dmp trace.flw
       db2trc fmt trace.dmp trace.fmt
       ```
