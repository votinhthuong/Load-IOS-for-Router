**Load IOS for Router**
  __________
||          ||                                          __________________
||          ||                                        ||                  ||    
||  Router  ||      ------------------------------>   ||   TFTP Server    ||  
||          ||               192.168.1.0/24           ||                  ||  
||__________||                                        ||__________________||


**Copy IOS từ Flash ra TFTP Server

*Router# copy flash: tftp:

**Copy IOS từ TFTP server vào Flash

*Router# copy tftp : flash:

**Copy IOS từ TFTP server vào Flash khi router mất IOS**
