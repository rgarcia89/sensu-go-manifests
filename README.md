# sensu-go-manifests
Everything you need to setup a sensu-go backend cluster that uses an external etcd. \
The backend manifest expects you to secure etcd client and sensu backen API communication via TLS. \
\
Information about how to create the related certificates can be found here: \
https://docs.sensu.io/sensu-go/latest/guides/securing-sensu/

Deploy in the following order etcd -> backend -> agent
