**Task A:**

![Alt text](/labs/l9/n8n-s1.png)
1- I created a new workflow and named it L9_ExerciseA_MirandaOK

![Alt text](/labs/l9/n8n-s3.png)
![Alt text](/labs/l9/n8nA-1pop.png)
2- I added a webhook node and a code node and pasted the code into the code node

![Alt text](/labs/l9/n8n-s4.png)
![Alt text](/labs/l9/n8nA-2pop.png)
3- I added a Respond to Webhook node and saved the workflow

![Alt text](/labs/l9/n8n-s5.png)
4- I tested the workflow without a parameter

![Alt text](/labs/l9/n8n-s6.png)
5- I tested the workflow with event name Meeting

![Alt text](/labs/l9/n8n-s7.png)
6- I used curl with command curl "localhost:5678/webhook-test/event?event=Lecture" and later activated the workflow
