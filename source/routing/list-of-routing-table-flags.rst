.. include:: /substitutions.rsti

List of Routing Table Flags
===========================

From the man page:

+----------+------------------+----------------------------------------------------+
| Letter   | Flag             | Meaning                                            |
+==========+==================+====================================================+
| 1        | RTF_PROTO1       | Protocol specific routing flag #1                  |
+----------+------------------+----------------------------------------------------+
| 2        | RTF_PROTO2       | Protocol specific routing flag #2                  |
+----------+------------------+----------------------------------------------------+
| 3        | RTF_PROTO3       | Protocol specific routing flag #3                  |
+----------+------------------+----------------------------------------------------+
| B        | RTF_BLACKHOLE    | Just discard pkts (during updates)                 |
+----------+------------------+----------------------------------------------------+
| b        | RTF_BROADCAST    | The route represents a broadcast address           |
+----------+------------------+----------------------------------------------------+
| C        | RTF_CLONING      | Generate new routes on use                         |
+----------+------------------+----------------------------------------------------+
| c        | RTF_PRCLONING    | Protocol-specified generate new routes on use      |
+----------+------------------+----------------------------------------------------+
| D        | RTF_DYNAMIC      | Created dynamically (by redirect)                  |
+----------+------------------+----------------------------------------------------+
| G        | RTF_GATEWAY      | Destination requires forwarding by intermediary    |
+----------+------------------+----------------------------------------------------+
| H        | RTF_HOST         | Host entry (net otherwise)                         |
+----------+------------------+----------------------------------------------------+
| L        | RTF_LLINFO       | Valid protocol to link address translation         |
+----------+------------------+----------------------------------------------------+
| M        | RTF_MODIFIED     | Modified dynamically (by redirect)                 |
+----------+------------------+----------------------------------------------------+
| R        | RTF_REJECT       | Host or net unreachable                            |
+----------+------------------+----------------------------------------------------+
| S        | RTF_STATIC       | Manually added                                     |
+----------+------------------+----------------------------------------------------+
| U        | RTF_UP           | Route usable                                       |
+----------+------------------+----------------------------------------------------+
| W        | RTF_WASCLONED    | Route was generated as a result of cloning         |
+----------+------------------+----------------------------------------------------+
| X        | RTF_XRESOLVE     | External daemon translates proto to link address   |
+----------+------------------+----------------------------------------------------+

