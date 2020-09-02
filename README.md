你好！
很冒昧用这样的方式来和你沟通，如有打扰请忽略我的提交哈。我是光年实验室（gnlab.com）的HR，在招Golang开发工程师，我们是一个技术型团队，技术氛围非常好。全职和兼职都可以，不过最好是全职，工作地点杭州。
我们公司是做流量增长的，Golang负责开发SAAS平台的应用，我们做的很多应用是全新的，工作非常有挑战也很有意思，是国内很多大厂的顾问。
如果有兴趣的话加我微信：13515810775  ，也可以访问 https://gnlab.com/，联系客服转发给HR。
# javascript-js2png

Hide JavaScript code into PNG image. For more details and a step-by-step
description of the code follow this [post][1].

## Prerequisite

* Go 1.3+ `sudo apt-get install golang-go`
* Make (optional)
* `git clone https://github.com/expobrain/javascript-js2png.git`

## Usage

To compile the JS-to-PNG encoder run:

    make js2png

To convert any payload into an image:

    bin/js2png <js_file> <png_file>

## Example

To run the embedded web server:

    make js2png
    make serve

To test the payload run the embedded web server and open the browser on
`http://localhost:8080`.

**Note**: remember that for security reasons the browser will not execute any
JavaScript code if the HTML file is loaded with the `file://` protocol.

[1]: https://www.expobrain.net/2014/09/26/hide-javascript-code-into-images/
