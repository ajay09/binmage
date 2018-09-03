# binmage
The above python code helps you convert a binary file to a coloured representation. Each byte is read and converted to pixel using a colour map.
Colour representaitons of files can be helpful in analyzing the binary file.

![alt text](https://github.com/chaser3/binmage/blob/master/example/05042268ee4fa6959f49e1d99d30fd71.png)

# Dependencies
pip install pillow

pip install numpy

# Using
call the function -: fileToImage(path to file).  
It will return a PIL Image object which can be saved using the following command in your code.  
returned_object.save('output_file_name.png')
