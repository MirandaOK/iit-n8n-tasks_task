![Alt text](/labs/l10/solutions/IIT-10A-1.png)
1- I created a new workflow and named it L10_ExerciseA_MirandaOK

![Alt text](/labs/l10/solutions/IIT-10A-2.png)
![Alt text](/labs/l10/solutions/IIT-10A-3.png)
![Alt text](/labs/l10/solutions/IIT-10A-4.png)
2- I added a HTTPS request and configured it
![Alt text](/labs/l10/solutions/IIT-10A-5.png)
![Alt text](/labs/l10/solutions/IIT-10A-6.pn6g)
![Alt text](/labs/l10/solutions/IIT-10A-7.png)
3- I added a set node and a respond to webhook node (I consulted chatGPT about set node)
![Alt text](/labs/l10/solutions/IIT-10A-8.png)
![Alt text](/labs/l10/solutions/IIT-10A-9.png)
4- I tested it successfully
Example JSON output:
{
"topic":"programmers",
"style":"one-liner",
"temperature":"0.7",
"joke":"Why do programmers prefer dark mode?\n\nBecause light attracts bugs!"
}
