
# JS
JS is a single threaded programming language that means it can do one thing at a time.  

Assume we have  an app for download videos  
1-search on video.  
2-watch the the video.  
3-download the video.  

now assume you want to search about another video to download it actually you can't do that until Finish downloading the video in the third step because the the js is a single threaded progrmming , this thing led us to know another thing in js (synchronous and asynchronous ).  

synchronous mean that the time is very importnat to excute instructions in your programming that mean your programming will excute  step by step and you will wait until finish downloading the video to search another video but to solve issue you can use asynchrounus because the time is not important to excute instructions how will happen that ?  

In your browser you have V8 engin to excute your code and the v8 engin has  
1-stack to store your instructins which  will be   implementd like search video the first step and watch the video in the second step and these step they don't a lot of time to implemented them.  

2-webAPI when you have instruction need a lot of time to implemented it like the third step you need a lot of time to download the vedio in this case the v8 engin will move the instruction from stack to webAPI then move it from webAPI to 3-queue and the insruction will wait in queue until the stack became empty then it will implemented.  
All of this cycle called Events loop and the result called callback function so callback function mean the result from asynchronous insruction ,and you can consider promis like asynchronous but with diffirent shape.  



