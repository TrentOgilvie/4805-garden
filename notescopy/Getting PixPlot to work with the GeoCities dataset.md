[[index]]

After trying (and failing) to retrace my steps and gather a new dataset of GeoCities screenshots, I returned to my saved collection of images and tried to input it to PixPlot. 
 
 With 250 images from the Enchanted Forest neighbourhood, I compressed the folder and uploaded it to the google collab notebook. 
 
 My first attempt, I was confronted with a similar error message to what I had received in class. I went back and realized I had left in one bit of extra code that I hadn't previously left in:
```
 !source activate pixplot_test; pixplot --images "/content/downloaded_images_enchanted/*" --metadata "/content/downloaded_images_enchanted/metadata.csv" 
```

 After removing that, the `#%%shell` command ran and seemed much more promising than before, it looked exactly like what was happening in class when things were running smoothly with the sample datasets. I help my breath until... 
 
 Another error message. This one caught me off guard, though, because I thought everything was working as intended. I went back through each command box to see if there was anything I missed before I saw it.
 
```
!source activate pixplot_test; pip install ipykernel
```

The one command I hadn't run in my own trials, the one I only ran when I was using the sample datasets. With an eye-twitch, I ran the single line of code, re-ran the `#%%shell` box, and... 

```
2024-10-28 21:44:40.029397: Done!
```

The gasp I gusp. There they were! One of the GeoCities neighbourhood datasets visualized once again in a different model.

![[dataset visual.gif]]

The Orange Data Mining tool produced a grid that looked like this
![[Pasted image 20241028182743.png]]

Compared to PixPlot, that generated this:
![[Pasted image 20241028182817.png]]
![[Pasted image 20241028183205.png]]
The clusters are similar but flipped, which makes me think about how each visualization model was trained and how different the measurements of distance are. 

Trying to figure out what similarities these images have beyond colour is fun, such as "cluster 5" that has everything from *Kelton's NeoPets Kingdom* to *Paper Airplane - The Paper Air Machines* instructional page for crafting the ultimate paper airplane. 

![[Pasted image 20241028183859.png]]

The visualization of a GeoCities dataset is so cool for this exact reason. All of these images are coming from one neighbourhood under a (mostly) cohesive theme of being by kids/for kids, but being 1. the internet, and 2. a broad theme, there is bound to be tons of variance between each page. The data visualization allows us to look for connections between each image, whether it be aesthetics, content, or something else.

This is one way we can look at historical datasets, so hopefully can inspire and help think about some potential ideas. 