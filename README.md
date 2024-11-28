java c
ELEE   8240 
Fall   2024 
Laboratory 9: External Libraries 
(Due   11/4/2024)
In this   lab we will compile a   library   and   use 3   functions   to   process   a   png   image   to   detect   the   edges.
1.          Create a vi that opens a   png   image   file   using   the   read   png   vi.   The   extract   the   byte   data   using   the   uncluster   by   name tool.   Find a   png   image   (online, on your   phone, etc.) that   you   can   use   to   test your code.
a.          For fun, figure out   how to   display   the   color   image   using   the   picture   vi   or   the   Intensity   Graph.
2.          In Visual Studio, create   a   c++   dll. To   create the   project   you   can   choose   the   console,   windows, and   library   options.   Place the code   in the attached   .cpp and   .h   files   into   the   correct   files   in the   project and compile   the   project.
3.          If your   png file   is an 8-bit   RGB   file   there   should   be   3   bytes   per   pixel.   (Some   png   files   have   an additional   byte for transparency.   Make sure to choose   a代 写ELEE 8240 Fall 2024 Laboratory 9: External LibrariesC/C++
代做程序编程语言   file   with   3   bytes   per   pixel.)   The   Function   in the   dll,   png_to_array() will   sum the colors for   each   pixel   and   put   the   data   into   a   two-dimensional array, creating a grayscale version of   the   image.   Display   the   grayscale   version   of the   vi   using the   Intensity Graph.   Manipulate your   image so that   it appears   upright.
4.          Use the Sobelx() and Sobely()   functions   in   the   dll   to   create   the   x   and   y   gradients.
5.         The edges of an   image g can   be   detected   by   creating   the   image   |▽g|.   Create this   image   and display   it   in a separate   Intensity   Graph.
a.          If you   have   previous c++ experience   and/or   are   feeling   cocky, you   can   try   adding   your own   image   processing function to the   dll.   For example a   Laplacian filter   replaces every pixel with the weighted sum of   adjacent   pixels,  A   smoothing   filter might use  
6.          Upload the vi and   dll   (just   the   .dll)   file   to   ELC.







         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
