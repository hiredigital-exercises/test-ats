# Task
The goal of the task is to showcase some campaigns in our platform. Each campaign consists of several projects that collectively make up that campaign. We need to create **two pages**, one containing a list of campaigns, and another of the detail of that campaign (and thus a list of projects in that campaign).


# Details and Limitations
1. We need to be able to update project information for each campaign.
    - Edits need to be save on debounce.
    - Inputs must be placed on the actual page (the user should not have to click an 'Edit button').
    - You must have a technique for handling many inputs on a single page.

2. You must use QuillJS on `proposal` and `notes` fields.
    - Each of the fields should expand in height based on the amount of content.
    - Use the default toolbar provided.

3. You must use functional components and hooks and the latest version of React.

4. These pages must also work on IE11.

5. You can use any technique you wish to save / preserve the data, but it should be in a way that can be done without the need of a backend server.

6. You should deploy the code to Vercel to demo. 

7. Add both functional and unit tests for the pages and components you make

8. For the components you create, you should also create Storybook examples.


# Data provided

You can find the necessary dummy data in the `data folder`
```
/data
    /campaign_list.json
    /campaign_1.json
    /campaign_2.json
    /campaign_3.json
    /campaign_4.json
    /campaign_5.json
    /campaign_6.json
    /campaign_7.json
    /campaign_8.json
```

We have provided a `campaign_list.json` which contains a list of campaigns as well as number of files entitled `campaign_[x].json` which contains the list of projects in a campaign.
