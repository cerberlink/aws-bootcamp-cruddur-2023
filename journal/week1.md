# Week 1 — App Containerization

## Required Tasks

In the future, I will keep all of workflow in the main branch. Also, thats nice documentation when I can configure the extension using `gitpod.yml` Please refer to this [link](https://www.gitpod.io/docs/references/ides-and-editors/vscode-extensions)

## Docker
In summary of docker, acantril explained clearly about the crucial architectural docker. I was played around it to get an idea last weekend. Everything in gitpod went good. I used ```docker run --rm -p 4567:4567 -it -e FRONTEND_URL='*' -e BACKEND_URL='*' backend-flask``` and its good.


## Frontend and Backend Implementation for Notification Service
![Screenshot 2023-02-23 at 2 16 01 PM](https://user-images.githubusercontent.com/11153290/221061194-ab4c350f-0c24-4abb-901d-411d5490362a.png)
![Screenshot 2023-02-23 at 2 16 09 PM](https://user-images.githubusercontent.com/11153290/221061204-266e1386-324e-4dd3-985a-6ffc399ab379.png)
![Screenshot 2023-02-23 at 4 12 28 PM](https://user-images.githubusercontent.com/11153290/221061212-e7abfe83-9d82-4414-aefc-cd69dc22071f.png)

## Connect DynamoDB and Postresql
Thats challegned for me when I missed something to command postgresql. In the video, it did not work for my side so I figured out how to resolve an issue. Until I saw someone leaving a commment under the video. The command is `psql -h localhost -U postgres`. That command I used works for my side so I am able to connect psql client. Please refer to this [link](https://www.youtube.com/watch?v=CbQNMaa6zTg&list=PLBfufR7vyJJ7k25byhRXJldB5AiwgNnWv&index=32)
