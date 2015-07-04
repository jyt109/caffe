##Installation Instructions

```
LDFLAGS="`pkg-config --libs protobuf` `pkg-config --libs opencv`" make all
LDFLAGS="`pkg-config --libs protobuf` `pkg-config --libs opencv`" make test
LDFLAGS="`pkg-config --libs protobuf` `pkg-config --libs opencv`" make runtest
make pycaffe
make distribute
```
