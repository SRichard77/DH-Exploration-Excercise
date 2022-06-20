**Name:** Skylar Richard

**Date:** June 17 2022

#### Wget 

For the DH exploration exercise, I used Wget to pull Abbie Bright's 86 page diary from [Kansas Memory](https://www.kansasmemory.org/).

**Challenges that I faced and what I did to help:** 

It was difficult to navigate Wget and I ran into a few problems. My fellow classmate, Kaliyah, and myself worked through Wget again together like we did for Part Two, to help each other out in navigating it as it can be a tad overwhelming and confusing. The first issue I ran into was when I used this command in the terminal: wget https://www.kansasmemory.org/item/223662. This url was the one from the main page of the diary on the website. When I entered this, in the directory was a document that led to this:

![](https://github.com/SRichard77/DH-Exploration-Exercise/blob/b1fca45bb582f3a85b39981d5b21b4a3b7ac1a69/DH%20exploration%20Wget%20error%201.png)

Following this, I attempted this command at the terminal: Wget https://www.kansasmemory.org/item/223662/text. The url that I used here is the url for the text version of Abbie Bright's diary. This pulled something, however, when I opened it, it led to this: 

![](https://github.com/SRichard77/DH-Exploration-Exercise/blob/27a875f0518caa5cc6ea6f1c1342b7c80ecdfa08/DH%20exploration%20Wget%20error%202.png)

After encountering these errors, I went back to the [Wget Tutorial](https://craftingdh.netlify.app/tutorials/wget/#basic-usage) on the class website and used what I learned from Part Two, and I inspected the images of the diary and found the numbers and format of their urls. From this, I created a list of urls in Sublime Text with all 86 pages as I was having a hard time using Python to generate a list of urls, so this was easier for me to tackle, even though it was more time consuming. I saved the file as urls.txt and put it into my folder for Abbie Bright's diaries. I then went back to the terminal from the folder, and used this command: 'wget -i urls.txt -r --no-parent -nd -w 2 --limit-rate=100k' to pull the 86 page diary from [Kansas Memory](https://www.kansasmemory.org/). Finally, it worked! 

![](https://github.com/SRichard77/DH-Exploration-Exercise/blob/a57cfaf0a40130fae69881dc1a0fd0507b6d7198/DH%20exploratoin%20Wget%20success.png)

#### Voyant

I used Voyant to explore the data from Abbie Bright's diary. 

**Challenges that I faced and what I did to help:** 

At first, I attempted to upload the jpg files of the diary that I pulled to my Mac using Wget. When I did this, I got the following error message: 

![](https://github.com/SRichard77/DH-Exploration-Exercise/blob/fbb081f53575aa3a06441c2c3d230f39e15345b1/jpg%20error%20Voyant.png)

After taking some time to think of how I should go about this, and how to get the diary into Voyant, I found that on the [Kansas Memory website](https://www.kansasmemory.org/item/223662/text) there was an option to choose the Text version of the diary. I then copied this url: https://www.kansasmemory.org/item/223662/text for the text version of the diary into Voyant, and it worked! 

#### Point Maps with Google 

Seeing as in Abbie Bright's diary, she mentions several different locations that she travelled to, I decided to make a map on Google with what I learned from Part Three. 



