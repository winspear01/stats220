<h1> Image I used </h1>

# ![image](https://user-images.githubusercontent.com/62272092/159117041-31115742-3d32-4a3e-8a12-e61e05d86915.png)

<h2> My Code </h2>

```
{

library(magick)

picture <- image_read('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRvaIMGsc4DJzuA6iBSkEuOM8R2q9qGPOeTt0HPID3EuUqajN2ZlsaZIu6ITBgW7pIhxLk&usqp=CAU')%>%
image_annotate("When the teacher catches you eating in class", color = 'black', size = 15, gravity = 'south')%>%

  
print(picture)

image_write(picture, "my_meme.png")

}
```


I made this meme because its a character from a show I am currently watching and I always ate in class in highschool


*This website helped to make this look decent* https://www.markdownguide.org/extended-syntax/
