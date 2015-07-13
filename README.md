##Installation Instructions

```
Install these dependencies: http://caffe.berkeleyvision.org/install_osx.html
LDFLAGS="`pkg-config --libs protobuf` `pkg-config --libs opencv`" make all
LDFLAGS="`pkg-config --libs protobuf` `pkg-config --libs opencv`" make test
LDFLAGS="`pkg-config --libs protobuf` `pkg-config --libs opencv`" make runtest
make pycaffe
make distribute
#export PYTHONPATH
```
