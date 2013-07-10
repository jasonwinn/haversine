haversine
=========

Small Java class for calculating the distance between two points using the Haversine function.

```java
public static double distance(double startLat, double startLong,
                              double endLat, double endLong)
```

### How to use
Call in a static context:

```java
Haversine.distance(47.6788206, -122.3271205,
                   47.6788206, -122.5271205)

// -> 14.973190481586224 [km]
```                    
