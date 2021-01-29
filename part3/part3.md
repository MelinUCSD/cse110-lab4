# Part 3
1. DevTools - Debugging  
***What was the bug?*** The function *calculateSum()* is doing a string concatenation instead of an arithmetic sum. This happens because both num1 and num2 are strings.  
***How would you fix this?*** To solve this problem we need to cast the variables num1 and num2 to integers by doing parseInt(num1) and parseInt(num2), respectively.

2. DevTools - Network Tab  
***What is the name of the new json file?*** The name is citylots.json.  
***Which file initiated the download of the new file*** par2.js initiated the fetch of the json file.  
***What is its size?*** The size is 11.7KB
***How long did it take to download?*** It took 1.44 seconds.
***What was your User-Agent for the browser that made the request?***  The User-Agent used Mozilla/5.0 (Macintosh; Intel Mac OS X 11_1_0) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/88.0.4324.96 Safari/537.36
***In the response, what type of server did it come from?*** The server type is Apache.  
***When was the file last modified?*** The last time the file was modified was Tue, 26 Jan 2021 22:14:13 GMT.
***What was the content type of the file*** The content of file was application/json.  
***Which method inside the initiating file made the request?*** The function that made the call was fetchData.