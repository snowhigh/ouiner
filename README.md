# ouiner
ouiner is a project to create a JSON database derived from IEEE's OUI                   
(Organizationally Unique Identifier)/MA-L (MAC Address Block Large) [registry](http://standards.ieee.org/develop/regauth/oui/oui.txt).                           
                                                                                  
It also merges popular device data currently gathered by Etienne Perot's             
[macchiato](https://github.com/EtiennePerot/macchiato) project.

The ouiner database is used to feed the popular MAC address spoofing mode in
Subgraph's macouflage application.

# Usage
```
$ wget -o data/oui.txt http://standards.ieee.org/develop/regauth/oui/oui.txt
$ python ouiner.py > ouis.json
```

