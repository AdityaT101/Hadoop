Hadoop Mapreduce -  Design patterns 

Music Industry has reached a new high in Business and it has gone beyond the usual stereotypes of CD and DVD’s. It has become much more freely available on the internet, thanks to ever enhancing connectivity and newer technologies. 
As every day passes, new recommendation engines have emerged in the market and they use BigData heavily in their processing. My motive behind Analyzing this Million Songs Dataset is to simulate a recommendation engine using Design Patterns used in Hadoop Mapreduce.


Here, the original Dataset available in h5 format is processed using Hdf5 _getters.py, convert.sh and parallel-convert.py scripts to convert it into txt format(CSV). Once, we have the data in Txt format, this data is further processed using Extractor script to come up with Design Patterns such as TopK design Pattern. Then Dist_Grep Design pattern, Partitioning Design Pattern and Latitude_Longitude Design pattern. So, here the extractor script basically gives us only the desired fields and this makes the processing and filtering the data easy. 
This is the basic idea to perform a very reliable and easy filtering on the data. Personally, I feel that this greatly reduces efforts and is quite efficient in terms of performance.

