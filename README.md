# Network-Performance-Test
https://kb.smartrg.com/DM_KnowledgeBase/Content/User_Manual/UM_NPT_Preparation.htm

https://www.bufferbloat.net/projects/codel/wiki/RRUL_test_suite/

TEST REQUIREMENTS

•	MUST test ipv6 and ipv4 simultaneously if available
•	MUST test for classification preservation and optimization
•	MUST run long enough to defeat bursty bandwidth optimizations such as PowerBoost and discard data from that interval.
•	MUST measure unloaded network performance of web pages, CIR and VOIP-like streams
•	MUST measure network performance under a saturating background load, of web pages, CIR and VOIP-like streams
•	MUST test UDP and TCP.
•	MUST track and sum bi-directional throughput, using estimates for ACK sizes of ipv4, ipv6, and encapsulated ipv6 packets, udp and tcp_rr packets, etc.
•	MUST have the test server(s) within 80ms of the testing client
•	MUST track CPU loading as a factor in being able to drive the test at full speed or not. Insufficient CPU available should invalidate the tests.
•	MUST run in userspace on the client(s)
•	COULD require special kernel assistance (such as web100) on the servers
•	SHOULD test for ECT(0) and ECT(1) ECN markings
•	SHOULD test for classification preservation/alteration

TEST VERSIONING

As typical workloads change over time, there will be periodic revisions to the behavior of the backend tools and emulations. 
This first iteration shall be called RRUL2013.


Package draw2d is a pure [go](http://golang.org) 2D vector graphics library with support for multiple output devices such as [images](http://golang.org/pkg/image) 
(draw2d), pdf documents (draw2dpdf) and opengl (draw2dgl), which can also be used on the google app engine. It can be used as a pure go [Cairo](http://www.cairographics.org/) alternative. 
draw2d is released under the BSD license. See the [documentation](http://godoc.org/github.com/llgcode/draw2d) for more details.

## Inspired by JPerf & nuttcp with features like, Complexity of parameters and configurations 

Installation
------------

Install [golang](http://golang.org/doc/install). To install or update the package draw2d on your system, run:

Stable release
```
go get -u gopkg.in/llgcode/draw2d.v1
```

or Current release
```
go get -u github.com/llgcode/draw2d
```
