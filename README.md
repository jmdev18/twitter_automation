# twitter_automation
Simple Twitter Automation Examples
What's the point?
Ever wonder how there are so many Tweets being posted every minute? 

Well, the simpler answer is that there is a ton of people on Twitter all the time. However, the more complex one involves that a lot of those users are either automating a lot of the interactions or paying a service provider to push content to Twitter for advertisement and brand awareness, etc to Twitter on behalf of the user. These providers themselves are using automation and progamming languages in order to accomplish the same thing. 

How hard is it really to be able to create my own little tweeting machine? It turns out, not very hard. As you can see on the right, you can make a ton of noise with not a ton of effort. Let's take a look.

What do we need for this...
For this exercise, we are going to need a computer, Python installed on that computer, and a developer environment (PyCharm). If you are familiar with the Python programming language and you have another dev. environment that you prefer that is ok too. 
 
For installing Python and PyCharm, there is a ton of tutorial and videos on youtube. You must install Python first and PyCharm after.
 
Now for this exercise...

Twitter Automation Starting Guide!!!

1. Signup for a Twitter developer account.

Navigate to www.developer.twitter.com, create a developer account. See capture below...

![](img/step_1.png)

2. Create a Twitter app.

Don’t worry, no actual code is needed, yet. All that is necessary here is to fill out the information and answer the questions that will aid the Twitter admins who are reviewing your app request. Try to make your answers as descriptive as possible. Approval can take a couple of days, while you are waiting you can go ahead and install python and the development environment on your machine.

![](img/step_2.png)

3. Find your Keys and Tokens

Once your app creation request is approved you will be notified via email. Alternatively, you can come back to the site and check the status. At this point, you will need to go into the app by clicking on the name and in the app options find the Keys and Tokens tab. There will be 4 long strings of letters and numbers. For this exercise, we will need all 4. Keep in mind that the Access token and secret are only visible when you first create them, so make sure you copy and paste them somewhere. 

4. Download and install Python and the dev. environment. 

Links to where to find and download Python and PyCharm provided here... 

https://python.org/downloads/

https://www.jetbrains.com/pycharm/download/

To download python you can simply go to link above and download the correct version based on your OS. For Linux based OS there are other ways to download python, I will assume you know what those are, or else you can just google: download python 3 on Linux. After downloading python 3 (not 2.xx –also I never download the latest, I usually stay 1 or 2 versions behind the latest) install it, default parameters are fine. 

Next, and this will be the most challenging part of this exercise aside from the coding portion, you will need to download a developer environment in which you will use the python code provided to automate Twitter updates and interactions. I recommend using, in my opinion, what I believe to be the best and most intuitive environment out there –PyCharm. You can download it from the link provided above. You do not need the professional version, the community version will suffice. There are installation instructions on the site. Once downloaded, you will be asked to create a new project upon the first time opening PyCharm. You can name this project whatever you like. It is very important to make sure that you have a python interpreter selected for this project. Here is how to check...

Go to File > Settings > Project: “name” > Python Interpreter. Make sure that the Python Interpreter path is filled with the location where you installed python. If this is blank, click on the cogwheel on the right and add the path on the prompt window. See below capture for reference...

![](img/step_4.png)
