# php-memcached for windows
 * php-memcached dependency libmemcached

        copy libmemcached.dll to c:\Windows 
        
  
        
 * install php-memcached
 
    copy php-memcached.dll to you php extension directory
    
    **notice:Note the version of PHP and thread safety whether or not**
    
 * memcached_support:
        
    **3.1.4**
    
    |name|is_support|
    ----|----------
    |SASL support|no|
    |Session support|yes|
    |igbinary support|no|
    |json support|yes|
    |msgpack support|no|
    
     **3.1.5**
     
    |name|is_support|
    ----|----------
    |SASL support|no|
    |Session support|yes|
    |igbinary support|yes|
    |json support|yes|
    |msgpack support|yes|
	
     **pre3.2.0**
     
    |name|is_support|
    ----|----------
    |SASL support|no|
    |Session support|yes|
    |igbinary support|yes|
    |json support|yes|
    |msgpack support|yes|	


version>=3.15 
* basic

    support session and json
* [igbinary](https://pecl.php.net/package/igbinary)

    support session and json and igbinary
    
    must download igbinary.dll and configure it to php.ini
* [msgpack](https://pecl.php.net/package/msgpack)
    
    support session and json and msgpack
    
    must download msgpack.dll and configure it to php.ini
    
    	
Tips:
ucrtbased.dll missing copy ucrtbased to system32 or SysWOW64
recommend use x64.x86 may be could not worked correctly.
    
### Visitors

![](http://profile-counter.glitch.me/lifenglsf/count.svg)
### 🧧 赞助

    
     
