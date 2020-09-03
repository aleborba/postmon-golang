你好！
很冒昧用这样的方式来和你沟通，如有打扰请忽略我的提交哈。我是光年实验室（gnlab.com）的HR，在招Golang开发工程师，我们是一个技术型团队，技术氛围非常好。全职和兼职都可以，不过最好是全职，工作地点杭州。
我们公司是做流量增长的，Golang负责开发SAAS平台的应用，我们做的很多应用是全新的，工作非常有挑战也很有意思，是国内很多大厂的顾问。
如果有兴趣的话加我微信：13515810775  ，也可以访问 https://gnlab.com/，联系客服转发给HR。
[![Build Status](https://travis-ci.org/PostmonAPI/postmongo.svg?branch=master)](https://travis-ci.org/PostmonAPI/postmongo) [![GoDoc](https://godoc.org/github.com/PostmonAPI/postmongo?status.png)](https://godoc.org/github.com/PostmonAPI/postmongo)

PostmonGo
===============

Go Wrapper for Postmon API

Uso
----
    
    package main
    
    import (
        "fmt"
        "github.com/PostmonAPI/postmongo"
    )

    func main() {
        res, err := postmongo.BuscarCep("01419101")
        fmt.Println(res)
        fmt.Println(err)
    }


ToDo
------

    * Adicionar suporte ao método de rastreio do Postmon
    * Melhorar os testes unitários


Licença
--------

    Copyright 2014 The Postmon API Team

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
