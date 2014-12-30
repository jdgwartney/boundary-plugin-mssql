Boundary Microsoft SQL Server Plugin
------------------------------------
Collects metrics from Microsoft SQL Server instance. Multiple instances of SQL Server running on the same machine are supported: each instance will show up as a separate source on your Boundary dashboard.

### Platforms
- Windows

### Prerequisites
- SQL Server 2008, 2012 or 2014.

### Plugin Setup

None

### Plugin Configuration Fields

The plugin will collect data from the default SQL Server Instance installed on the machine, and requires
no configuration.

### Metrics Collected

The metrics collected are a subset of the SQL Server counters available using Windows Performance Counters.


|Metric Name                             |Description|
|:---------------------------------------|:----------|
|MSSQL - Active Temp Tables              |           |
|MSSQL - User Connections                |           |
|MSSQL - Logical Connections             |           |
|MSSQL - Transactions                    |           |
|MSSQL - Processes Blocked               |           |
|MSSQL - Lock Timeouts                   |           |
|MSSQL - Lock Waits                      |           |
|MSSQL - Lock Wait Time (ms)             |           |
|MSSQL - Lock Average Wait Time (ms)     |           |
|MSSQL - Lock Timeouts (>0)              |           |
|MSSQL - % Log Used                      |           |
|MSSQL - Replication Pending Transactions|           |
|MSSQL - Compilations                    |           |
|MSSQL - IO Latch Waits                  |           |
