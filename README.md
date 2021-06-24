# WhaleRdmaChannel
Whale RDMA Channel:A Channel-Oriented RDMA Java Communication Framework. More high-level abstract Channel API on top of RDMA verbs.

1. rdmaWriteInQueue operation
2. rdmaSendInQueue operation
3. rdmaSendWithImm operation
4. rdmaReadInQueue operation
5. rdmaChannel stop operation

## How to use?

If you want to compile the project, you should ensure that you have installed mvn v3.5.4 and jdk v1.8.0 on your machine. Then you compile the project as follows.

1\. Clone the project from github.

```shell
$ git clone <repo_url>
```

2\. Go into RdmaChannel directory and compile it.

```shell
$ cd RDMAChannel
$ mvn clean install -Dmaven.test.skip=true -Dcheckstyle.skip=true
```

Then you get `disni-1.6.jar` at `disni/target/`, `rdmachannel-core-1.0-SNAPSHOT.jar` at `rdmachannel-core/target/`. You can use them in your own project.

## License

RdmaChannel is released under the [Apache 2 license](http://www.apache.org/licenses/LICENSE-2.0.html).

