# homebrew-r-blas
R Homebrew Formula that lets you select which BLAS library is used (Reference/Apple Accelerate/OpenBLAS)
Based on the homebrew-core r.rb:  
https://github.com/Homebrew/homebrew-core/blob/HEAD/Formula/r.rb  
This formula supports options regarding BLAS library.  
If you use no flags, then you get the R reference BLAS.    
But, you can also do:  
--with-accelerate  
This will use Apple's Accelerate BLAS.  
--with-openblas  
This will use OpenBLAS, see http://openblas.net    
If you also use:   
--with-lapack   
then any LAPACK library included in your BLAS library will also be used——this may be a bad idea?  
For more information check:   
https://cran.r-project.org/doc/manuals/r-patched/R-admin.html#Linear-algebra
