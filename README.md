# qdbm-ruby-patch
QDBM 1.8.78 ruby Library patches for ruby 2.x
  
## Usage  
  
tar zxf qdbm-1.8.78.tar.gz  
cd qdbm-1.8.78  
.  
.  
(qdbm compile & install)  
.  
.  
git clone https://github.com/animarl/qdbm-ruby-patch.git  
patch -p1 < qdbm-ruby-patch/curia.patch  
patch -p1 < qdbm-ruby-patch/depot.patch  
patch -p1 < qdbm-ruby-patch/villa.patch  
cd ruby  
./configure  
make  
make install  
