# racing-time-series
Sample time-series application using car telemetry as the use case without Open TSDB

The data should be stored in MapR Json DB by storing batches of data points in each record. The data should be transmitted via MapR Streams, but eventually stored in MapR Json DB.

Tasks:

1. Need CV github id's
1. Need streams sand box or AWS instance
2. Need slide show on time series


The goal is to have real-time data acquisition flow through multiple clusters that are intermittently connected.

Telemetry info
http://www.f1fanatic.co.uk/2014/08/07/ferraris-telemetry-lap-hungaroring/ferrari-telemetry-hungaroring-1/
http://www.mclaren.com/appliedtechnologies/products/item/atlas/
https://www.metasphere.co.uk/telemetry-data-journey-f1/

Car simulators
http://wiki.vdrift.net/index.php?title=About_the_project
http://vamos.sourceforge.net/
http://164.100.133.129:81/eCONTENT/Uploads/VDHS-0%20Vehicle%20Dynamics.pdf

High level control
https://f1metrics.wordpress.com/2014/10/03/building-a-race-simulator/
http://www.nt.ntnu.no/users/skoge/prost/proceedings/ifac11-proceedings/data/html/papers/2954.pdf
https://www.math.uni-magdeburg.de/institute/imo/ag_sager/PUBLICATIONS/Kehrle2010.pdf
