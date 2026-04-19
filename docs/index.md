# Rubix NumPower</h1>

Inspired by NumPy, the NumPower extension was created by Henrique Borba to provide the foundation for efficient scientific computing in PHP, as well as leverage the machine learning tools and libraries that already exist and can benefit from it.

This C extension developed for PHP can be used to considerably speed up mathematical operations on large datasets and facilitate the manipulation, creation and operation of N-dimensional tensors.

NumPower was designed from the ground up to utilize AVX2 and the GPU to further improve performance. With the use of contiguous single precision arrays, slices, buffer sharing and a specific GC engine, 

NumPower aims to manage memory more efficiently than a matrix in PHP arrays