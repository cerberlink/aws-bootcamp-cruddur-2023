# Week 0 — Billing and Architecture

## Required Tasks

### Install & Verify the AWS CLI

I had followed the intruction on the [AWS CLI Documentation](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html). Also, I installed AWS CLI in IDE, which is gitpod, and local machine for MacOS. I configured the AWS CLI in local and gitpod using env.
![Screenshot 2023-02-16 at 12 29 04 PM](https://user-images.githubusercontent.com/11153290/219479986-4bcef2de-2ba2-4a03-ba44-a6251c717d36.png)
![Screenshot 2023-02-16 at 12 50 26 PM](https://user-images.githubusercontent.com/11153290/219484094-96f41792-44d3-4d0e-bee8-b3007d1b31ff.png)

```
aws command help
```
you see the following AWS services above. 

Furthermore, I am able to show the configuration for aws iam in the local machine. 
![Screenshot 2023-02-16 at 12 37 59 PM](https://user-images.githubusercontent.com/11153290/219481682-4b6d5c3d-5a65-4b6a-b484-76a680f26335.png)

### Create a budget via AWS Console
Creating a budget and alarm in the console is easy step to set up.
![Screenshot 2023-02-16 at 12 40 52 PM](https://user-images.githubusercontent.com/11153290/219482220-d49a9b27-ae27-4274-94b9-7e6589ef90c8.png)

### Conceptual Architectural Design
![Screenshot 2023-02-16 at 12 44 16 PM](https://user-images.githubusercontent.com/11153290/219482809-e54317b7-4eef-472a-a446-ebdeb907a6e5.png)
[Conceptual Design - Lucid](https://lucid.app/lucidchart/7e7c9de6-ec9c-4028-bb74-33819af2f0ed/edit?viewport_loc=-5%2C61%2C1886%2C1413%2C0_0&invitationId=inv_93532eb1-4aa7-4008-9d30-e0f551885970)

### Logical Architectural Design
![Screenshot 2023-02-16 at 12 44 37 PM](https://user-images.githubusercontent.com/11153290/219482820-6429f1df-48ce-4bff-a55b-4b188f71a0fd.png)
[Logical Design - Lucid](https://lucid.app/lucidchart/d0374876-b716-4d97-accc-9e862e503327/edit?viewport_loc=-67%2C77%2C1973%2C1527%2C0_0&invitationId=inv_ed083802-f368-4518-951c-310f9e433599)
