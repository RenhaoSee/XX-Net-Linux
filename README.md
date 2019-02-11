#### XX-Net-Linux 3.13.1
Mini version of [XX-Net](https://github.com/XX-net/XX-Net) for Linux user.

Usage: 

    git clone https://github.com/miketwes/XX-Net-Linux.git

    sudo /etc/init.d/miredo start
    cd XX-Net-Linux/local && python2 proxy.py
    
    # Chromium
    chromium --proxy-server="http://127.0.0.1:8087"
    
    # Firefox 
    about:config
    network.proxy.type 1     
    network.proxy.http 127.0.0.1
    network.proxy.http_port 8087      


Note: all XX-Net 3.13.1 related Python 2.7.15+ libs are latest version and installed by pip2.

    pip2 install setuptools
    pip2 install hyper ipaddress  pyOpenSSL hyperframe pyasn1 PySocks -U

    asn1crypto   0.24.0 
    cffi         1.11.5 
    cryptography 2.5    
    enum34       1.1.6  
    h2           2.6.2  
    hpack        3.0.0  
    hyper        0.7.0  
    hyperframe   5.2.0  
    ipaddress    1.0.22 
    pip          19.0.1 
    pyasn1       0.4.5  
    pycparser    2.19   
    pyOpenSSL    19.0.0 
    PySocks      1.6.8  
    setuptools   40.8.0 
    six          1.12.0
