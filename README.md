# usbLogin
mac通过usb连接手机

手机上的22端口映射mac上的1234端口
`python tcprelay.py -t 22:1234`

mac上登录
`ssh root@127.0.0.1 -p 1234`
