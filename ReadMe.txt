11.05.2022

In accordance to hometask of Contrast Security:

Created 2 REST API applucations as a Maven projects.
Their API are self documented by a command:

http://localhost:8080/swagger-ui.html

1.Producer: 
1.1 Sents a file of 100 samples to a bucket.
1.2 Reads this file from a bucket and send all its rows into
Kinesis stream.

2.Planet:
2.1 Calculates average value and count of samples between
two timestamps:
http://{hostname}/api/events/{eventType}/average?from={timestamp}&to={timestamp}
2.2 Deletes resources used AWS resources.

