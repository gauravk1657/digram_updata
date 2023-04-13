# digram_updata
diagram  fetch data



   +--------------+    +--------------+     +--------------+
   |              |    |              |     |              |
   |  Loading...  |----|   Loaded!    |---->|  Error!      |
   |              |    |              |     |              |
   +--------------+    +--------------+     +--------------+
        |                     |                     |
   +----|---------------------|---------------------|----+
   |    v                     v                     v    |
   | +--------------+  +--------------+  +--------------+ |
   | |              |  |              |  |              | |
   | |   Fetching   |  |   Success!   |  |   Failure!   | |
   | |    Action    |  |    Action    |  |    Action    | |
   | |              |  |              |  |              | |
   | +--------------+  +--------------+  +--------------+ |
   |        |                     |                     | 
   +--------|---------------------|---------------------+
            v                     v
       +--------------+    +--------------+
       |              |    |              |
       |   JSON Data  |    |   Error Msg  |
       |              |    |              |
       +--------------+    +--------------+

