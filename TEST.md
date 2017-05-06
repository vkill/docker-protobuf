### Test

```
$ docker run -it --rm --name protobuf vkill/protobuf bash

docker$ wget -P /tmp https://raw.githubusercontent.com/google/protobuf/master/examples/addressbook.proto
docker$ protoc -I=/tmp --cpp_out=/tmp /tmp/addressbook.proto
```
