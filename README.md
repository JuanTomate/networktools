# networktools 3 
Is a one simple lib for extract informations of networkt interface

# Example 1 

>>> import networktools
>>> me = networktools.network_tools("wlan0")
>>> me.interface()
["wlan0"," 192.168.0.23",24]
>>> 

# Example 2 

>>> import networktools
>>> me = networktools.ping("192.168.32.2")
>>> me.ping()
False
>>> 


