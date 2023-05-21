# ToolDelta-Docker
>>>ToolDelta运行PhoenixBuilder所需要的Docker

运行环境:
apt-get -yq update \

apt-get install ca-certificates -y \

apt-get install libreadline8 -y \

apt-get install -y tzdata \

apt-get install gcc -y \

apt-get install wget -y \

ln -snf /usr/share/zoneinfo/$TIME_ZONE /etc/localtime   echo $TIME_ZONE > /etc/timezone \

dpkg-reconfigure -f noninteractive tzdata \


      
    新建文件夹: 
    mkdir -p /root/.config   mkdir -p /root/.config/fastbuilder \
     
    设定语言:
    echo -n 'zh_CN' > /root/.config/fastbuilder/language
    
>>>END 
