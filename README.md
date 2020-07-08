# video_ia895
Assets for final project (video) for IA895 class at Unicamp


Face Drawings - https://www.cartoonify.de/
Animation Process - SynfigStudios
Story Board - ?


# Setup
```shell script
# Install SynfigStudio

```


```shell script
# Install magick
sudo apt-get install autoconf automake autotools-dev libtool pkg-config
sudo apt-get install build-essential libjpeg-dev libjpeg-tools libpng-dev libpng-tools
wget https://www.imagemagick.org/download/ImageMagick.tar.gz
tar xvzf ImageMagick.tar.gz
cd ImageMagick-7.0.10-23/
./configure 
make -j 8
sudo make install
sudo ldconfig /usr/local/lib
magick -version
```


# Compression
```shell script
convert original.png -resize 200x200 resize.png
for Q in 50 20 10 5 2 1
do
  convert resize.png -quality $Q resize_quality_$Q.jpeg
done 
```







