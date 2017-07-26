## Automatic Python PyObject ref-count management in C++ using a smart ptr  
Originally published: 2011-12-16 23:28:07  
Last updated: 2011-12-19 15:24:03  
Author: samh   
  
Managing ref-counting is a complex and error prone business. If you choose C++ to extend or embed Python, you can simply use a modification on `std::auto_ptr`. Instead of calling delete on the managed pointer, it will decref it.