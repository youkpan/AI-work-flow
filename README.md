Hi ~ Welcome to experience the latest AI enterprise service product: Visual AI Workflow Design Studio!
As the prospects for AI-assisted office work become increasingly broad, how will it be realized? How to design a suitable automation operation method for each workflow. This is the direction we have always wanted to push. We also hope to provide everyone with a design tool that can be quickly used and connected to the work environment.
  Now, we are pleased to introduce to you our AI workflow design tool. With the help of various AI modules, you can quickly start designing your AI automation process.
  Here you can:
  ●No programming required, just use flowchart tools, drag and drop, and connect to complete AI automation design work!
  ●Feel the convenience and intuitiveness of graphical AI debugging, debug and view the AI running process step by step, and accurately control every design link.
  ●Can design complex and diverse AI automation systems:
  For example: super personal assistant (by retrieving personal information, searching the Internet for information, plug-in system, splicing the complete information step by step, and outputting the content you need), designing a set of automated workflows suitable for your own business, automatically creating task cycles for execution, and universal Intelligence (general intelligent design requires a lot of preliminary debugging work, and our visualization studio can more easily align human-machine collaboration), intelligent conferences, intelligent audio and video processing and other systems.
Online experience: https://ai.zyinfo.pro/ai-work-flow/dist/?userid=test
Development interface introduction (please use 1920x1080 resolution):
The overall interface consists of the calculation module (in the upper left area, relevant modules can be dragged to the design drawing), design interface, debugging area, data management area, etc.
Introduction to flow chart design:

Introduction to simple design flow chart
This is the simplest flow chart, with the start logo on the left and the end logo on the far right.
  This example: We first let AI generate a string, then let the judgment module perform AI calculation judgment, and finally print the output based on the judgment result. Of course, you can also add a module to wait for user input. At this time, users can upload files on the ai.zyinfo.pro display smart assistant interface to participate in related processing.
For AI processing and judgment modules (double-clicking the module will open this detailed setting):
We can set code execution (for example, we can control the number of loops in the AI processing flow).
  AI processing part:
You can configure the AI processing system (multiple AI processing models such as Tongyi Qianwen), and at the same time, the results of the previous step and the previous n steps can be put into the context for processing. You can add the words: {input text} to the prompt word (do not omit {}). The system automatically replaces, {input text} is equivalent to {previous result}.
How to enter text content?
AI processing modules can use {someVar} to represent user input. At the same time, the user input can be calculated in the js code (javascript language) part. someVar = user input.
The currently processed prompt word is the current message to the AI system.
The maximum token is not recommended to exceed 2000.
Associated documents, databases, and plug-ins:
Just fill in the relevant information. The retrieved relevant information is automatically completed into the context during processing, with a maximum of 15 pieces of content per item. The plug-in id can be viewed in Zhenying Smart Assistant ai.zyinfo.pro:
After copying, multiple plug-ins are separated by,.
  For example: 5e8d0b379f42c2f80f10315230e3b881,b66bc14337c9714105aa1c7bee1ce62d
  Please note: For functions that require information retrieval, the server-side retrieval plug-in must be called, such as document association, file, chat database, etc.
Debug mode:
Click the Debug button in the lower left corner to enter debugging mode. At this time, you can see the results of each step of AI processing, making it easy to adjust the prompt words.
The judgment method of the judgment module:
If AI judgment is not used, only the js code judgment value is obtained
  If AI is used to add judgment, if the module has js code: then judge whether the js code judgment is true and the AI judgment result is true (AI output includes: true, yes (must be the first word), true (not case sensitive)) , the result is TRUE. If there is no js code, the AI output result will be used to judge.
  The judgment output module can use a time-based billing model, which can be cheaper in long text processing (for example, after the context length exceeds 2000 tokens).
About variables and code:
  Variables entered by the user are stored globally. The AI system can output js code and execute it automatically. jscode example. If you need AI to output executable js code, it must be included in the script tag. The results of the AI output module are stored in the results_list list. Results_list does not contain the displayed partial output results.
AI service recharge link: https://zyinfo.pro/pay/pay.php.
The exciting visual AI processing system design work has begun, and the exhibition will help you step into the wave of AI to AGI general intelligence!
appendix:
  Advanced example:
Loop summarizing the given text
  Process introduction:
  1. Get input
  2. Intercept the first 100 Chinese characters and assign them to text1. And output the contents of text1.
  The final output content of the AI processing module = the content after AI processing + the content output by the js code segment.
  3. Determine the output content length or the length of text1
  4. Summarize and output the text
  5. Print the processed text to the result column
  6. Cycle again
Automatically complete short play scripts
Tips: 
  Press F2 to enter the next step during debugging
  After selecting the module, press F9 to set the debugging breakpoint. After setting, press F4 to quickly run to the breakpoint. Press F4 again to continue running.
  The system automatically replaces "${var_name}" in the js code and prompt words with the value of the global variable var_name.
  Tips for using the mobile terminal: Be sure to turn on the desktop version of the website mode for browsing, and landscape orientation is recommended. Click Examples->Advanced Examples. Long press the module to set relevant parameters, click connection mode, and then click two modules one after another to connect. Click on the edge of the module to enter parameter settings (it may take a few more clicks).
  Small bug: After dragging the module, it may appear in the upper left corner of the design drawing. If there is a small chance that the arrow is not displayed, you can drag the module slightly to redraw it.
  Welcome to make suggestions to us: WeChat youkpanzh Showcase Visual AI Workflow Design Studio Instructions for Use

Hi ~ Welcome to experience the latest AI enterprise service product: Visual AI Workflow Design Studio!
Image: https://uploader.shimo.im/f/5CmDC3hS4lIcH2CN.png!thumbnail?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJleHAiOjE3MTI2NTgyMjEsImZpbGVHVUlEI joiUjEzamRNTW9tMWZyOGVrNSIsImlhdCI6MTcxMjY1NzkyMSwiaXNzIjoidXBsb2FkZXJfYWNjZXNzX3Jlc291cmNlIiwidXNlcklkIjoxMzAwNzk1OX0.vYojF9WZo3RxVxTMF3ImAhD_8RQXZbnj qYYaxSUsuTM
As the prospects for AI-assisted office work become increasingly broad, how will it be realized? How to design a suitable automation operation method for each workflow. This is the direction we have always wanted to push. We also hope to provide everyone with a design tool that can be quickly used and connected to the work environment.
Now, we are pleased to introduce to you our AI workflow design tool. With the help of various AI modules, you can quickly start designing your AI automation process.
Here you can:
● No programming is required, just use the flowchart tool, drag and drop, and connect to complete the AI automation design work!
● Feel the convenience and intuitiveness of graphical AI debugging, debug and view the AI running process step by step, and accurately control every design link.
● Can design complex and diverse AI automation systems:
For example: super personal assistant (by retrieving personal information, searching the Internet for information, plug-in system, splicing the complete information step by step, and outputting the content you need), designing a set of automated workflows suitable for your own business, automatically creating task cycles for execution, and universal Intelligence (general intelligent design requires a lot of preliminary debugging work, and our visualization studio can more easily align human-machine collaboration), intelligent conferences, intelligent audio and video processing and other systems.
	
Online experience: https://ai.zyinfo.pro/ai-work-flow/dist/?userid=test

Development interface introduction (please use 1920x1080 resolution):
Image: https://uploader.shimo.im/f/HOWNbAfFWk76UMZl.png!thumbnail?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJleHAiOjE3MTI2NTgyMjEsImZpbGVHVUlEIjoi UjEzamRNTW9tMWZyOGVrNSIsImlhdCI6MTcxMjY1NzkyMSwiaXNzIjoidXBsb2FkZXJfYWNjZXNzX3Jlc291cmNlIiwidXNlcklkIjoxMzAwNzk1OX0.vYojF9WZo3RxVxTMF3ImAhD_8RQXZbnjqY YaxSUsuTM
The overall interface consists of the calculation module (in the upper left area, relevant modules can be dragged to the design drawing), design interface, debugging area, data management area and other parts.

Introduction to flow chart design:
Image: https://uploader.shimo.im/f/fqaZwTwGm2MStAUY.png!thumbnail?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJleHAiOjE3MTI2NTgyMjEsImZpbGVHVUlEI joiUjEzamRNTW9tMWZyOGVrNSIsImlhdCI6MTcxMjY1NzkyMSwiaXNzIjoidXBsb2FkZXJfYWNjZXNzX3Jlc291cmNlIiwidXNlcklkIjoxMzAwNzk1OX0.vYojF9WZo3RxVxTMF3ImAhD_8RQXZbnj qYYaxSUsuTM
Introduction to simple design flow chart
This is the simplest flow chart, with the start logo on the left and the end logo on the far right.
This example: We first let AI generate a string, then let the judgment module perform AI calculation judgment, and finally print the output based on the judgment result. Of course, you can also add a module to wait for user input. At this time, users can upload files on the ai.zyinfo.pro display smart assistant interface to participate in related processing.

For AI processing and judgment modules (double-clicking the module will open this detailed setting):
Image: https://uploader.shimo.im/f/WzDwfnRLdd8nutee.png!thumbnail?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJleHAiOjE3MTI2NTgyMjEsImZpbGVHVUlEIjoiU jEzamRNTW9tMWZyOGVrNSIsImlhdCI6MTcxMjY1NzkyMSwiaXNzIjoidXBsb2FkZXJfYWNjZXNzX3Jlc291cmNlIiwidXNlcklkIjoxMzAwNzk1OX0.vYojF9WZo3RxVxTMF3ImAhD_8RQXZbnjqYY axSUsuTM
We can set code execution (for example, we can control the number of loops in the AI processing flow).
AI processing part:
Image: https://uploader.shimo.im/f/gYuHg0PXGszXhSFg.png!thumbnail?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJleHAiOjE3MTI2NTgyMjEsImZpbGVHVUl EIjoiUjEzamRNTW9tMWZyOGVrNSIsImlhdCI6MTcxMjY1NzkyMSwiaXNzIjoidXBsb2FkZXJfYWNjZXNzX3Jlc291cmNlIiwidXNlcklkIjoxMzAwNzk1OX0.vYojF9WZo3RxVxTMF3ImAhD_8RQXZbn jqYYaxSUsuTM
You can configure the AI processing system (multiple AI processing models such as Tongyi Qianwen), and at the same time, the results of the previous step and the previous n steps can be put into the context for processing. You can add the words: {input text} to the prompt word (do not omit {}). The system automatically replaces, {input text} is equivalent to {previous result}.
	
How to enter text content?
Image: https://uploader.shimo.im/f/fRsJfWY48TaFKmC9.png!thumbnail?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJleHAiOjE3MTI2NTgyMjEsImZpbGVHVUlEIjoiUjEzamRNTW9tMWZyOGVrNSIsImlhdCI6MTcxMjY1NzkyMSwiaXNzIjoidXB sb2FkZXJfYWNjZXNzX3Jlc291cmNlIiwidXNlcklkIjoxMzAwNzk1OX0.vYojF9WZo3RxVxTMF3ImAhD_8RQXZbnjqYYaxSUsuTM
AI processing modules can use {someVar} to represent user input. At the same time, the user input can be calculated in the js code (javascript language) part. someVar = user input.
	
The currently processed prompt word is the current message to the AI system.
The maximum token is not recommended to exceed 2000.
Associated documents, databases, and plug-ins:
Image: https://uploader.shimo.im/f/ab3RfmSkrDHBaLJA.png!thumbnail?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJleHAiOjE3MTI2NTgyMjEsImZpbGVHVUlEIjo iUjEzamRNTW9tMWZyOGVrNSIsImlhdCI6MTcxMjY1NzkyMSwiaXNzIjoidXBsb2FkZXJfYWNjZXNzX3Jlc291cmNlIiwidXNlcklkIjoxMzAwNzk1OX0.vYojF9WZo3RxVxTMF3ImAhD_8RQXZbnjq YYaxSUsuTM
Just fill in the relevant information. The retrieved relevant information is automatically completed into the context during processing, with a maximum of 15 pieces of content per item. The plug-in id can be viewed in Zhenying Smart Assistant ai.zyinfo.pro:
Image: https://uploader.shimo.im/f/hFyFZqd1yFcUPqTH.png!thumbnail?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJleHAiOjE3MTI2NTgyMjEsImZpbGVHVUlEI joiUjEzamRNTW9tMWZyOGVrNSIsImlhdCI6MTcxMjY1NzkyMSwiaXNzIjoidXBsb2FkZXJfYWNjZXNzX3Jlc291cmNlIiwidXNlcklkIjoxMzAwNzk1OX0.vYojF9WZo3RxVxTMF3ImAhD_8RQXZbnj qYYaxSUsuTM
Image: https://uploader.shimo.im/f/9zX2z1pxhBeCeosK.png!thumbnail?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJleHAiOjE3MTI2NTgyMjEsImZpbGVHVUlEI joiUjEzamRNTW9tMWZyOGVrNSIsImlhdCI6MTcxMjY1NzkyMSwiaXNzIjoidXBsb2FkZXJfYWNjZXNzX3Jlc291cmNlIiwidXNlcklkIjoxMzAwNzk1OX0.vYojF9WZo3RxVxTMF3ImAhD_8RQXZbnj qYYaxSUsuTM
After copying, multiple plug-ins are separated by,.
For example: 5e8d0b379f42c2f80f10315230e3b881,b66bc14337c9714105aa1c7bee1ce62d
Please note: For functions that require information retrieval, the server-side retrieval plug-in must be called, such as document association, file, chat database, etc.

Debug mode:
Image: https://uploader.shimo.im/f/XtelJSURB9Z8D1Fr.png!thumbnail?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJleHAiOjE3MTI2NTgyMjEsImZpbGVHVUlEIjoiU jEzamRNTW9tMWZyOGVrNSIsImlhdCI6MTcxMjY1NzkyMSwiaXNzIjoidXBsb2FkZXJfYWNjZXNzX3Jlc291cmNlIiwidXNlcklkIjoxMzAwNzk1OX0.vYojF9WZo3RxVxTMF3ImAhD_8RQXZbnjqYY axSUsuTM
Click the Debug button in the lower left corner to enter debugging mode. At this time, you can see the results of each step of AI processing, making it easy to adjust the prompt words.
The judgment method of the judgment module:
If AI judgment is not used, only the js code judgment value is obtained
If AI is used to add judgment, if the module has js code: then judge whether the js code judgment is true and the AI judgment result is true (AI output includes: true, yes (must be the first word), true (not case sensitive)) , the result is TRUE. If there is no js code, the AI output result will be used to judge.
The judgment output module can use a time-based billing model, which can be cheaper in long text processing (for example, after the context length exceeds 2000 tokens).
	
About variables and code:
Variables entered by the user are stored globally. The AI system can output js code and execute it automatically. <script>jscode example</script>. If you need AI to output executable js code, it must be included in the script tag. The results of the AI output module are stored in the results_list list. Results_list does not contain the displayed partial output results.

AI service recharge link: https://zyinfo.pro/pay/pay.php.

The exciting visual AI processing system design work has begun, and the exhibition will help you step into the wave of AI to AGI general intelligence!


appendix:
Advanced example:
Image: https://uploader.shimo.im/f/F8GMgXQivT42h2ku.png!thumbnail?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJleHAiOjE3MTI2NTgyMjEsImZpbGVHVUlEIjo iUjEzamRNTW9tMWZyOGVrNSIsImlhdCI6MTcxMjY1NzkyMSwiaXNzIjoidXBsb2FkZXJfYWNjZXNzX3Jlc291cmNlIiwidXNlcklkIjoxMzAwNzk1OX0.vYojF9WZo3RxVxTMF3ImAhD_8RQXZbnjq YYaxSUsuTM
Loop summarizing the given text
Process introduction:
1. Get input
2. Intercept the first 100 Chinese characters and assign them to text1. And output the contents of text1.
The final output content of the AI processing module = the content after AI processing + the content output by the js code segment.
3. Determine the output content length or the length of text1
4. Summarize and output the text
5. Print the processed text to the result column
6. Cycle again

Image: https://uploader.shimo.im/f/wCn43TM7XLdsg5tv.png!thumbnail?accessToken=eyJhbGciOiJIUzI1NiIsImtpZCI6ImRlZmF1bHQiLCJ0eXAiOiJKV1QifQ.eyJleHAiOjE3MTI2NTgyMjEsImZpbGVHVUlEI joiUjEzamRNTW9tMWZyOGVrNSIsImlhdCI6MTcxMjY1NzkyMSwiaXNzIjoidXBsb2FkZXJfYWNjZXNzX3Jlc291cmNlIiwidXNlcklkIjoxMzAwNzk1OX0.vYojF9WZo3RxVxTMF3ImAhD_8RQXZbnj qYYaxSUsuTM
Automatically complete short play scripts

Tips: 
Press F2 to enter the next step during debugging
After selecting the module, press F9 to set the debugging breakpoint. After setting, press F4 to quickly run to the breakpoint. Press F4 again to continue running.
The system automatically replaces "${var_name}" in the js code and prompt words with the value of the global variable var_name.
Tips for using the mobile terminal: Be sure to turn on the desktop version of the website mode for browsing, and landscape orientation is recommended. Click Examples->Advanced Examples. Long press the module to set relevant parameters, click connection mode, and then click two modules one after another to connect. Click on the edge of the module to enter parameter settings (it may take a few more clicks).
Small bug: After dragging the module, it may appear in the upper left corner of the design drawing. If there is a small chance that the arrow is not displayed, you can drag the module slightly to redraw it.
Welcome to make suggestions to us: WeChat youkpan
