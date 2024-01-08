Draft
Dockerを触ってみた
Yayで docker をインストールして、systemctl enable docker
ここまではうまくいったけど、そこからがエラーで進まない。debugしてみるとmodule が見つからないとか。
uname -r
してみると、Arch Linux 9になってる。確か昨日10になったのに。。と思って、再起動してないことを思い出しました。
rebootで、もう一度uname -rで Arch Linux 10になってました。これでパスが通って無事見つけられたようで、何なくdockerが動いてくれました。