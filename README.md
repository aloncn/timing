# timing  
[![GoDoc](https://godoc.org/github.com/aloncn/timing?status.svg)](https://godoc.org/github.com/aloncn/timing)
[![Build Status](https://travis-ci.org/thinkgos/timing.svg?branch=master)](https://travis-ci.org/thinkgos/timing)
[![codecov](https://codecov.io/gh/thinkgos/timing/branch/master/graph/badge.svg)](https://codecov.io/gh/thinkgos/timing)
![Action Status](https://github.com/aloncn/timing/workflows/Go/badge.svg)
[![Go Report Card](https://goreportcard.com/badge/github.com/aloncn/timing)](https://goreportcard.com/report/github.com/aloncn/timing)
[![Licence](https://img.shields.io/github/license/thinkgos/timing)](https://raw.githubusercontent.com/thinkgos/timing/master/LICENSE)  
 - 实现时间定时器,采用优先级队列实现
 - 实现简单时间调度,任务处理
 - 任务默认在协程池中处理,任务频繁却又不耗时. 可以配置使用goroutine处理
 - 扫描超时条目时间复杂度o(1).
 - 不限最大时间
