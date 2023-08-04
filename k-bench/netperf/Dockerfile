FROM gcr.io/google-containers/nginx

run wget https://github.com/HewlettPackard/netperf/archive/netperf-2.7.0.tar.gz && \
 tar xf netperf-2.7.0.tar.gz && \
 cd netperf-netperf-2.7.0 && \
 ./configure && \
 make && \
 make install && \
 make clean && \
 cd .. && \
 rm -rf netperf-2.7.0.tar.gz && \
 rm -rf netperf-netperf-2.7.0 
CMD sleep infinity
