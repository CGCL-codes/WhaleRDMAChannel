# WhaleRDMAChannel
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

### Publications
If you want to know more detailed information, please refer to this paper:

Jie Tan, Hanhua Chen, Yonghui Wang, Hai Jin, "Whale: Efficient One-to-Many Data Partitioning in RDMA-assisted Distributed Stream Processing Systems," Proceedings of International Conference for High Performance Computing, Networking, Storage and Analysis (SC 2021), St. Louis. MO, USA, Nov. 14-19, 2021. 
([bibtex](https://github.com/CGCL-codes/WhaleRDMAChannel/blob/master/Whale.bib))

### Authors and Copyright
WhaleRDMAChannel is developed in National Engineering Research Center for Big Data Technology and System, Cluster and Grid Computing Lab, Services Computing Technology and System Lab, School of Computer Science and Technology, Huazhong University of Science and Technology, Wuhan, China by Jie Tan (tjmaster@hust.edu.cn), Hanhua Chen (chen@hust.edu.cn), Yonghui Wang (yhw@hust.edu.cn), Hai Jin (hjin@hust.edu.cn).

Copyright (C) 2021, [STCS & CGCL](grid.hust.edu.cn) and [Huazhong University of Science and Technology](www.hust.edu.cn).
