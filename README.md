## Kaggle explorations



example tensorboard graph server:
```
tensorboard --logdir=foo:C:\Users\codywin\mdev\kaggle-stuff\log
```

#switch between environments
activate tensorflow
activate tensorflow-gpu



## YOL

# Download protobuff release and put bin/protoc on path
https://github.com/google/protobuf/releases

```
git clone https://github.com/tensorflow/models

cd research

#compile the protos
protoc object_detection/protos/*.proto --python_out=.




```