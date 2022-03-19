# stats220

# Assignment 1, Part A 

Hi welcome to my stats 220 assignment 1 website page! 

## About me 

* Im in my 3rd year in **University of Auckland** and I study Biological Science 🌱  and Statistics 📊 together! 

* In my spare I love to watch *ghibli* and listen to music all the time! 💖 

## ✨ Memes ✨

 
* Below is a gif from my favourite ghibli movie, *Kiki's Delivery Service* of a character named: Kiki 💜

* I created this gif by using a R package: [{magick}] ("https://c.tenor.com/xu7knlWzzDAAAAAd/kikis-delivery-service-ghibli.gif). 

![](https://c.tenor.com/xu7knlWzzDAAAAAd/kikis-delivery-service-ghibli.gif) 

I have created the gif by putting in the following code into R: 

```r 
## download {magick} package 
install.packages("magick")
library("magick")
## copy url address from internet by using image_read function
meme <- image_read("https://c.tenor.com/xu7knlWzzDAAAAAd/kikis-delivery-service-ghibli.gif" &>&
                     image_write(meme, "my_meme.png")
print(meme)
```
