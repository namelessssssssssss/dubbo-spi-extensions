# dubbo-spi-extensions
[![Build Status](https://travis-ci.org/apache/dubbo-spi-extensions.svg?branch=master)](https://travis-ci.org/apache/dubbo-spi-extensions)
[![codecov](https://codecov.io/gh/apache/dubbo-spi-extensions/branch/master/graph/badge.svg)](https://codecov.io/gh/apache/dubbo-spi-extensions)
[![Maven Central](https://img.shields.io/maven-central/v/org.apache.dubbo/dubbo-spi-extensions.svg)](https://search.maven.org/search?q=g:org.apache.dubbo%20AND%20a:dubbo-spi-extensions)
[![GitHub release](https://img.shields.io/github/release/apache/dubbo-spi-extensions.svg)]

The purpose of dubbo-spi-extensions is to provide open, community-driven, reusable components to build microservice programs with different needs. These components extend the core of the Apache Dubbo project, but they are separated and decoupled.

Developers can flexibly choose the required extension dependencies to develop microservice programs based on their needs. The available extensions are as follows:Developers can flexibly choose the required extension dependencies to develop microservice programs based on their needs. 

The available extensions are as follows:

- [dubbo-api-docs](dubbo-api-docs)
  - [dubbo-api-docs-annotations](dubbo-api-docs/dubbo-api-docs-annotations)
  - [dubbo-api-docs-core](dubbo-api-docs/dubbo-api-docs-core)
  - [dubbo-api-docs-examples](dubbo-api-docs/dubbo-api-docs-examples)
- [dubbo-cluster-extensions](dubbo-cluster-extensions)
  - [dubbo-cluster-broadcast-1](dubbo-cluster-extensions/dubbo-cluster-broadcast-1)
  - [dubbo-cluster-loadbalance-peakewma](dubbo-cluster-extensions/dubbo-cluster-loadbalance-peakewma)
  - [dubbo-cluster-polaris-dubbo2](dubbo-cluster-extensions/dubbo-cluster-polaris-dubbo2)
  - [dubbo-cluster-specify-address-common](dubbo-cluster-extensions/dubbo-cluster-specify-address-common)
  - [dubbo-cluster-specify-address-dubbo2](dubbo-cluster-extensions/dubbo-cluster-specify-address-dubbo2)
  - [dubbo-cluster-specify-address-dubbo3](dubbo-cluster-extensions/dubbo-cluster-specify-address-dubbo3)
- [dubbo-common-extensions](dubbo-common-extensions)
- [dubbo-configcenter-extensions](dubbo-configcenter-extensions)
  - [dubbo-configcenter-consul](dubbo-configcenter-extensions/dubbo-configcenter-consul)
  - [dubbo-configcenter-etcd](dubbo-configcenter-extensions/dubbo-configcenter-etcd)
- [dubbo-cross-thread-extensions](dubbo-cross-thread-extensions)
- [dubbo-extensions-dependencies-bom](dubbo-extensions-dependencies-bom)
- [dubbo-extensions-distribution](dubbo-extensions-distribution)
  - [dubbo-apache-release](dubbo-extensions-distribution/dubbo-apache-release)
  - [dubbo-bom](dubbo-extensions-distribution/dubbo-bom)
- [dubbo-filter-extensions](dubbo-filter-extensions)
  - [dubbo-filter-polaris-dubbo2](dubbo-filter-extensions/dubbo-filter-polaris-dubbo2)
    - [dubbo-filter-polaris-circuitbreaker-dubbo2](dubbo-filter-extensions/dubbo-filter-polaris-dubbo2/dubbo-filter-polaris-circuitbreaker-dubbo2)
    - [dubbo-filter-polaris-ratelimit-dubbo2](dubbo-filter-extensions/dubbo-filter-polaris-dubbo2/dubbo-filter-polaris-ratelimit-dubbo2)
  - [dubbo-filter-seata](dubbo-filter-extensions/dubbo-filter-seata)
- [dubbo-gateway-extensions](dubbo-gateway-extensions)
  - [dubbo-gateway-common](dubbo-gateway-extensions/dubbo-gateway-common)
  - [dubbo-gateway-consumer](dubbo-gateway-extensions/dubbo-gateway-consumer)
  - [dubbo-gateway-provider](dubbo-gateway-extensions/dubbo-gateway-provider)
- [dubbo-metadata-report-extensions](dubbo-metadata-report-extensions)
  - [dubbo-metadata-report-consul](dubbo-metadata-report-extensions/dubbo-metadata-report-consul)
  - [dubbo-metadata-report-etcd](dubbo-metadata-report-extensions/dubbo-metadata-report-etcd)
- [dubbo-mock-extensions](dubbo-mock-extensions)
  - [dubbo-mock-admin](dubbo-mock-extensions/dubbo-mock-admin)
  - [dubbo-mock-api](dubbo-mock-extensions/dubbo-mock-api)
- [dubbo-registry-extensions](dubbo-registry-extensions)
  - [dubbo-registry-consul](dubbo-registry-extensions/dubbo-registry-consul)
  - [dubbo-registry-dns](dubbo-registry-extensions/dubbo-registry-dns)
  - [dubbo-registry-etcd3](dubbo-registry-extensions/dubbo-registry-etcd3)
  - [dubbo-registry-nameservice](dubbo-registry-extensions/dubbo-registry-nameservice)
  - [dubbo-registry-polaris](dubbo-registry-extensions/dubbo-registry-polaris)
  - [dubbo-registry-redis](dubbo-registry-extensions/dubbo-registry-redis)
  - [dubbo-registry-sofa](dubbo-registry-extensions/dubbo-registry-sofa)
- [dubbo-remoting-extensions](dubbo-remoting-extensions)
  - [dubbo-remoting-etcd3](dubbo-remoting-extensions/dubbo-remoting-etcd3)
  - [dubbo-remoting-grizzly](dubbo-remoting-extensions/dubbo-remoting-grizzly)
  - [dubbo-remoting-mina](dubbo-remoting-extensions/dubbo-remoting-mina)
  - [dubbo-remoting-p2p](dubbo-remoting-extensions/dubbo-remoting-p2p)
  - [dubbo-remoting-quic](dubbo-remoting-extensions/dubbo-remoting-quic)
  - [dubbo-remoting-redis](dubbo-remoting-extensions/dubbo-remoting-redis)
- [dubbo-rpc-extensions](dubbo-rpc-extensions)
  - [dubbo-rpc-hessian](dubbo-rpc-extensions/dubbo-rpc-hessian)
  - [dubbo-rpc-http](dubbo-rpc-extensions/dubbo-rpc-http)
  - [dubbo-rpc-memcached](dubbo-rpc-extensions/dubbo-rpc-memcached)
  - [dubbo-rpc-native-thrift](dubbo-rpc-extensions/dubbo-rpc-native-thrift)
  - [dubbo-rpc-redis](dubbo-rpc-extensions/dubbo-rpc-redis)
  - [dubbo-rpc-rmi](dubbo-rpc-extensions/dubbo-rpc-rmi)
  - [dubbo-rpc-rocketmq](dubbo-rpc-extensions/dubbo-rpc-rocketmq)
  - [dubbo-rpc-webservice](dubbo-rpc-extensions/dubbo-rpc-webservice)
- [dubbo-serialization-extensions](dubbo-serialization-extensions)
  - [dubbo-serialization-avro](dubbo-serialization-extensions/dubbo-serialization-avro)
  - [dubbo-serialization-fastjson](dubbo-serialization-extensions/dubbo-serialization-fastjson)
  - [dubbo-serialization-fst](dubbo-serialization-extensions/dubbo-serialization-fst)
  - [dubbo-serialization-fury](dubbo-serialization-extensions/dubbo-serialization-fury)
  - [dubbo-serialization-gson](dubbo-serialization-extensions/dubbo-serialization-gson)
  - [dubbo-serialization-jackson](dubbo-serialization-extensions/dubbo-serialization-jackson)
  - [dubbo-serialization-kryo](dubbo-serialization-extensions/dubbo-serialization-kryo)
  - [dubbo-serialization-msgpack](dubbo-serialization-extensions/dubbo-serialization-msgpack)
  - [dubbo-serialization-native-hession](dubbo-serialization-extensions/dubbo-serialization-native-hession)
  - [dubbo-serialization-protobuf](dubbo-serialization-extensions/dubbo-serialization-protobuf)
  - [dubbo-serialization-protostuff](dubbo-serialization-extensions/dubbo-serialization-protostuff)
  - [dubbo-serialization-test](dubbo-serialization-extensions/dubbo-serialization-test)
- [dubbo-tag-extensions](dubbo-tag-extensions)
  - [dubbo-tag-subnets](dubbo-tag-extensions/dubbo-tag-subnets)

## Contribution


Thanks to everyone who has contributed!


<a href="https://github.com/apache/dubbo-spi-extensions/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=apache/dubbo-spi-extensions" />
</a>


