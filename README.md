# enVision
enVision is a free-to-use online web service that will help you plan out your trip in advance! See how full your destination is before arriving and stop wandering aimlessly around the full parking lot hoping to get a space. With enVision, you won't waste any more time arriving at a venue, only to find it crowded with no room for you and your friends.

Our project features several feeds of various popular locations around Kingston! Each feed will also have an estimate of the number of people and compare to an approximate maximum capacity, telling you if the space is barren or crowded. It will also recommend various times to arrive that are typically less crowded to help you better plan your trip.


# Code
Oh, our repository looks a bit barren? Here's all of our code.

<a href="https://www.envirovision.tech">Website</a>

<a href="https://github.com/sunyshore/srcnn">Satellite Image Upscaling</a>

<a href="https://github.com/RelativelyFine/Parking-Detection">Parking Image Analysis</a>


# How It Works
Our project uses municipal <a href="https://www.cityofkingston.ca/explore/webcams">live feeds of the City of Kingston</a>.

The AI model is trained on a dataset of public satellite imagery which we used Convolutional Neural Networks to upscale <b><a href="https://github.com/sunyshore/srcnn">here</a></b>. Then, we compared multiple Computer Vision models, and chose between Transformers, CNN, and R-CNN models to perform image analysis.

We registered the domain <b><a href="https://www.envirovision.tech">envirovision.tech</a></b> with Domain.com, courtesy of the QHACKS/MLH discount!

We used <b>Velo by Wix</b> to integrate some features of our project.


# Our Team
Backend: David C.

Frontend: Dan D.

AI: Mercy D.

UI/UX: Amy C.

