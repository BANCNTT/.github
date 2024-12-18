# <p align="center">:tada::tada::tada: ✨ Bus Station Management ✨ :tada::tada::tada:</p>

## :newspaper: Table of Things

### Applications, Services, Databases and Storages
|    Server     | Port  | Repos/Database/Storage | Purpose                             | Opened? | Ran? | IP opened           | Notes |
|:-------------:|-------|------------------------|-------------------------------------|:-------:|:----:|---------------------|-------|
| 192.168.77.31 | 14333 | SQL Server             | Database                            |    x    |  x   | 192.168.7.210:14333 |       |
|               | 82    | bsm-file-storage       | Files Scan                          |    x    |  x   | 192.168.7.210:82    |       |
|               | 89    | bsm-file-service       | API file                            |    x    |  x   | 192.168.7.210:89    |       |
| 192.168.77.33 | 3005  | bsm-app                | Soft                                |    x    |  x   | 192.168.7.210:3005  |       |
|               | 3007  | bsm-app-administrator  | Soft Administrator                  |    x    |  x   | 192.168.7.210:3007  |       |
|               | 3010  | bsm-app-car-qrcode     | Soft Seeing car which is processing |    x    |  x   | 192.168.7.210:3010  |       |
|               | 3009  | bsm-app-kiosk          | Soft Searching in Kiosk Pos         |    x    |  x   | 192.168.7.210:3009  |       |
|               |       | bsm-app-statistic      | Soft Statistic                      |         |      |                     |       |
|               | 3006  | bsm-file-management    | Soft File Management                |    x    |  x   | 192.168.7.210:3006  |       |
| 192.168.77.35 | 80    | bsm-core               | API core                            |    x    |  x   | 192.168.7.210:80    |       |
|               | 84    | bsm-core-administrator | API core administrator              |    x    |  x   | 192.168.7.210:84    |       |
|               | 83    | bsm-core-statistic     | API core statistic                  |    x    |  x   | 192.168.7.210:83    |       |
|               | 81    | bsm-user-service       | API user                            |    x    |  x   | 192.168.7.210:81    |       |

### Fan Out
|    Server     | Port  | Repos                  | Purpose                             | Current?             | Opened? | Ran? | IP opened          | Notes |
|:-------------:|-------|------------------------|-------------------------------------|----------------------|:-------:|:----:|--------------------|-------|
| 192.168.77.35 | 5000  | bsm-alpr-3             | ALPR                                |                      |    x    |  x   | 192.168.7.210:5000 |       |
|               | 88    | bsm-ticket             | API ticket                          |                      |    x    |  x   | 192.168.7.210:88   |       |
| *All clients* | 3456  | bsm-print-client       | Print receipt PDF (SumatraPDF)      |                      |    x    |  x   | localhost:3456     |       |
| *All clients* | 4567  | bsm-control-qrcode     | Controll QR Code machines           |                      |    x    |  x   | localhost:4567     |       |

### DevOps
| Repos                  | Description      | Tasks            |
|------------------------|------------------|------------------|
| bsm-monitoring         |                  |                  |

### Tools
| Repos                  | Description      | Tasks            |
|------------------------|------------------|------------------|
| bsm-receipt-manual     |                  |                  |

## :bookmark_tabs: References Softs

## :bookmark_tabs: References Technical Stack

## :memo: Notes
