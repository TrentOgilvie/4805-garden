I chose to use perchance.org to generate images of my historical prompt: 1996 Mount Everest Disaster.

That is exactly how I inputted it to perchance, and I found my results to be a bit lackluster. Over and over again I was generating the same grid of images with usually a small group of people wearing red mountaineering suits and a non-descript mountain in the background. There weren't any clear Everest indicators like I expected there to be (prayer flags or basecamp tents), nor were there any "disaster" vibes. Nothing gruesome to be found. 

I stuck with it and generated 11 grids (66 total photos) before running them through the google collab notebook.

My first hiccup was an issue with the formatting of my images, the code was seeking out .png images to slice but all of mine were .jpg. I couldn't understand why the all_images folder was being created but nothing was actually happening with my data until Dr. Graham went through the process himself and called out the one line of code. After I switched it to be compatible with my image format, the code successfully split up my grid screenshots and I was left with 66 individual images. 

Everything went smoothly with the subsequent coding and installs until I was met with the python element. Unfortunately, python makes my brain melt a bit and I uninstalled it in a fit of rage a few weeks ago. I had to go through the steps to reinstall it and was baffled when I still couldn't get it to run in command prompt. When running python it would bring up the Microsoft store and try to get me to install it again, so I decided to just google it. I found a whole thread of people saying that you need to change the pathing in your system, until one person said to just try "py" instead of python. 

It worked, but I still couldn't get the server running for whatever reason.

I thought it was a total flop until I realized that pixplot was, in fact, still running and working within the google collab notebook. So even though I couldn't yet explore the visualization in all its glory, I could look at it on a shrunken scale within the notebook and found some interesting clusters.

One thing I noticed is that on either end of the visualization were two similar images in concept: one person centered in the middle of the frame with a mountain in the background. The only clear difference was one seemed to be on the ascent whereas the other was on the descent. The fact that this was enough to differentiate and create such a divide in the space is pretty cool; the perspective change was noticeable enough for it to be on either side of the grid, furthest from each other. 
