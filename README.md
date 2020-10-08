## Task

The goal of this task to create an applicant tracking system (ATS) in React. This applicant tracking system will consist of a list of jobs, as well as a detail page for each job with its applicants and their applications. The UX of the pages are up to you, so use your best judgement as to how to put the pages together.

Structure of the models used will be as follows:

#### Customer
```
id
uuid
name, string
```

#### Job
```
id
uuid
title, string
picture, url
requirements, html text
date, date
salary, number
location, string
client, one of (customer)
```

#### Applicant
```
id
uuid
name, string
picture, url
email, email
phone, string
location, string
application, html text
status, one of (draft, submitted, accepted, rejected)
notes, html text
job, one of (job)
```

## Evaluation

The task will be evaluated on code structure and quality, test quality, and page performance. UX will be judged based on logical flow, ease of use, for the end user, which in this case, will be a person on the "agency" side who is managing multiple clients. This test will not be evaluated on a UX for clients (who will create jobs), or talents (that will be applying for them).

## Details and Limitations

1. You must use functional components and hooks and the latest version of React.
2. These pages must also work on IE11.
3. Data must be editable, and saved to LocalStorage.
4. Prefill with dummy data of your choice, with at least 5 clients, 20 jobs, and 20 applicants each.
5. Deploy code in a working demo to Vercel. 
6. Add functional and unit tests for the pages and components you make. You can make use of any test library.
