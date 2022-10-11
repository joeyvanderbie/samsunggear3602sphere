# fusion2sphere for Samsung Gear360
@author Joey van der Bie
@date 2022-10-11
@twitter @joeyvanderbie

# gear360 specifics 
Install fusion2sphere as you would normally do. (See installation section)
To use the Gear360 settings and convert the fisheye photos,
use the following command:

```shell
$ ./fusion2sphere -b 5 -f inputImage.jpg inputImage.jpg -o outputImage.jpg gear360/gear360_photo.txt 
```

Note that your input image is the same image for the Front and the Back, the gear360_photo.txt settings will handle the part of the Front camera and the part of the back camera.