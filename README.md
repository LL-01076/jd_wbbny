<b>京东热爱狂欢趴 一键完成任务脚本来袭</b>

活动地址：

https://wbbny.m.jd.com/babelDiy/Zeus/2s7hhSTbhMgxpGoa9JDnbDzJTaBB/index.html#/home


脚本使用方法：


1、python脚本，依赖requests库，需要自己抓取cookie，保存在ck.txt文件中

2、参数设置

    task_times     #循环任务次数，可以多跑几次没事
    sleep_times  #间隔时间，默认在任务所需的基础上加，一般设置2s左右就成，看自己

3、脚本可以完成签到，逛店，加购等任务

4、将py文件件跟ck.txt放一起运行，没ck.txt的自己创建个，多账号的话换行放cookie即可

截图：

试了几个号暂时看着没啥问题，运行截图
<img src='https://image.planet.youku.com/img/100/28/62238/i_1490875862238_0ed9b71bf959f06a1e81684cb5b89291_b_w308h705_face_w308h705_x0y0w0h0c0.jpg'>

Cookie抓取：



不会抓cookie的看这里

1.推荐使用chrome浏览器，打开浏览器，按F12选择手机模式

<img src='https://image.planet.youku.com/img/100/28/62238/i_1490875862238_165fa22eca1c6c8c43f9b38b8b50a1f0_b_w855h277_face_w855h277_x0y0w0h0c0.png'>

2.浏览器的 User-Agent 必须包含 jdapp，设置含有jdapp的user-agent，设置完成【save后记得选择刚保存的user-agent】

exp:

jdapp;iPhone; CPU iPhone OS 5_0 like Mac OS X) AppleWebKit/534.46 (KHTML, like Gecko) Version/5.1 Mobile/9A334 Safari/7534.48.3
<img src='https://image.planet.youku.com/img/100/28/62238/i_1490875862238_5d8af6a784d21741be12bb7efb78a4f4_b_w1006h479_face_w1006h479_x0y0w0h0c0.png'>

3.访问 https://wbbny.m.jd.com/babelDiy/Zeus/2s7hhSTbhMgxpGoa9JDnbDzJTaBB/index.html#/home，登录京东账号【save后记得选择刚保存的user-agent】

4.登录后，点击network，然后活动中的任务列表，在network中找到那个请求的接口，把Headers 中的Cookie复制出来，直接document出来的貌似失败
<img src='https://image.planet.youku.com/img/100/28/62238/i_1490875862238_05ef0bdf914bc70a89cdde3876324780_b_w1188h1057_face_w1188h1057_x0y0w0h0c0.png'>

