# Echo Emotion Detection

## 💡 Inspiration

Emotion is one of the most confusing and complex part of humans and to this day noone fully understands it. That said, from what we do know, we know that in order to stay in a good mood there are different things that we can do, watch tv, read a book, or listen to music... Music, that IT! That is how we narrowed our idea to music and emotion. The first question was how do we detect the emotion of our users? Well, as artificial intelligence continous to rise and dominate the data science industry, it only seemed fair that we integrate out own artificial intelligence model. The first step in our journey was the emotion detection with the AI Model so here it check it out!

## 💻 What it does

Here are some of our final results!:
![](https://cdn.discordapp.com/attachments/796218966729162784/802984948784431104/unknown.png)

- Open up Real Time Emotion Detection and the computer will start getting a recording of your face via the webcam
- The webcam video stream will be broken up frame by frame and each frame will detect the amount of faces and where each face is located
- Then each face will be cropped out based on their location in the image
- The model will be given each of these cropped out faces (gray scaled) and will output the emotion.
- Finally, a reactangle will be drawn around your face for each frame and your emotion will be outputted on top!

## 🔨 How we built it

1. We had to come up with a data source as this project relies heavily on the data (any AI requires a suffiect amount of GOOD data).
2. We then had to figure out how to properly preprocess the mess of data we had.
3. Next, we had to create a model from scratch using Tensorflow Keras.
4. Finally, we trained our model and created the video functions using opencv :)


If you want to check out our [Google Colab](https://colab.research.google.com/drive/1Aq_fdZ4jZLoxh5_f7GJ5fohazRqF8QVq?usp=sharing), here it is!


## 🧠 Challenges we ran into
Data Preprocessing was a difficulty specifically for me because I had never actually worked on preprocessing images in this format. My teamate was really helpful in this and worked me through how to preprocess this. I then worked on creating a seqential CNN model using keras layers where we experienced another challenger, which was creating a perfect layer structure. The model was created and tweaked many many times as we kept training and tweaking multiple times a day.

## 🏅 Accomplishments that we're proud of

We are proud of the fact that our model has over a 65% accuracy when detecting emotions, as this was one of the first large scale Artificial Intelligence projects we had worked on. We are also proud of the fact that we were able to succesfully integrate opencv with our model. 

## 📖 What we learned

We learned a lot, but specifically we learned a lot about data preprocessing images and the architecture of CNNs. We also got to learn about the opencv camera software and played around a lot with that.

## 🔜 What's next for _Echo_

Currently in production is the website for Echo, which will take in the users emotion, and reccomend music based on their emotions. This is being built using Django and React and we hope to have it available for commerical use by the end of this year :)/

## Try It OUT!
_IN PRODUCTION AT THE MOMENT_
