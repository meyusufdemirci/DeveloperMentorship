This document includes the skills every developer should have, popular subjetcs and most asked questions.  

# Skills

- [Technical Skills](#technical-skills)
  - [Self Development](#self-development)
  - [Architectures](#architectures)
  - [Tests](#tests)
  - [Localization](#localization)
- [Soft Skills](#soft-skills)
  - [Self Confidence](#self-confidence)
  - [Email Usage](#email-usage)
  - [Resume](#resume)
  - [Time Management](#time-management)
  
# Subjects
- [Freelance](#freelance)
  
## Technical Skills
The skills you should have them to develop yourself in the technical area you are in.

### Self Development
Software development is a marathon never ends. When you find out how to learn yourself, you will not get tired in the marathon.

- Make meaningful Google searches such as `ios swift how to handle button click`, `ios swiftui binding vs state`. Google is the best way to get answers about the issue you are facing with. The great search brings the best solution
- Always have a side project besides your work at the office. You are free to integrate new features into your project because you are the boss!
- Internet has a lot of qualified articles, benefit them! Make 15 mins reading time every day just before starting the work
- Build open-source projects even if they are small ones. Publish them to everyone in the package management systems. [Example side project ideas for iOS development](https://github.com/demirciy/ExampleProjectIdeas)

### Architectures
In software frameworks, mostly the most important subject is the architecture of the software. The most two known architectures are MVC and MVVM.

- MVC: Model View Controller
  - Model: stores data such as UserModel, MovieModel. It mostly represents the data that fetched from backend
  - View: the part the end-user sees. It is also the view part of the controller
  - Controller: the logic part of the view. Logic process, database communication, helper functions is stored
- MVVM: Model View View-Model
  - Model: the same as MVC
  - View: the same as MVC. In addition, it includes the controller, not only view
  - View Model: the logic part of the view. Assume that it is a helper of the controller. It stores the logic process in the controller, hence controller will be lighter

### Tests
Every software has some weaknesses to be covered by the software team. That's why the teams needs tests. There are two the most common/known tests, Unit and UI.

- Unit Test: is for testing the logic part of the software. Assume that we have a function which is called `sum` to sum two integers by given as parameters. The function returns the sum of these two integers. In our test method, we basically passes parameters to the sum function and expect the right result 
- UI Test: is used mostly in front end technologies such as mobile, web. We basically provide a screenshot of a screen, which is accepted as the perfect responsive design. We create a test method to take screenshots of other devices and compares the screenshots with the perfect one. If the difference is too much, the test fails

### Localization
Software products might aim to different countries/languages. We somehow must localize the texts in the product.  
In most cases, developers start with English and assume that its localized file name is **en.string**. In this file, texts are stored by key-value principle. For example, `hello: Hello World!`. To support Spanish, all we need to do is creating another file which is named **es.string**. We use the same key but different value here. `hello: Hola Mundo!`.  
I assume that you have a manager/helper to choose the exact localization file by the language.

## Soft Skills
They are the skills you need out of the technical area. They are essential as much as technical skills.
  
### Self Confidence
It is needed to show/promote yourself. You should balance it, not too much, not too less.  

There are some tricks to gain some self confidence,
- Put real, professional, friendly, cool profile pictures on social profiles such as Linkedin, Twitter, GitHub, Medium, etc.
- Make social profiles public
- Share your knowledge on social profiles
- Be aware of your skills
- Do not call yourself Junior everytime

### Email Usage
When you want to start a conversation that is essential/serious, email comes to help.

Here are some tips/information about how the email works,
- The receiver can see CC, not BCC
- Put your manager to CC in case the email contains essential information/decision
- Use `Reply All` all the time. If there are some people in the CC and you don't use Reply All, they will be gone from the conversation
- Ask the recruiter to send you the job contract via email. It shows you are professional and you will get the offer in a serious way.
- Fill the email message like you write an essay
- Start the email with `Hello`, `Hi XXX`, end it with `Best Regards`, `Have a Good Day`
- Tell the situation as clear as you can

### Resume
Your resume is your first impression that must be great to make the further steps easier for you.

There are some common thoughts most of the developers agree with,
- Find a cool template. It does not have to be colorful, just cool. Hire a designer to build one for you
- Make it consistent, font, colors, alignment
- It's highly recommended that it should not over a single page. No HR person is looking forward to reading your all resume carefully. Make their work easier
- Order sections by importance. Generally, the order from top to bottom is, personal information(e-mail, place), about(telling yourself), experience, projects, skills, certificates, education. Some of the sections might be more powerful than others, move them to upper
- No one needs your private personal information, such as long address, gsm, married or not. You don't have to put them in your resume
- Adapt your picture by the continent. The companies are in United States don't prefer pictures in your resume. They only care about your skills, not look. Other countries are not strict as in United States
- Put a picture that shows your professionality, sincerity. Don't be look like too formal or informal, just normal. Of course, smile :)
- Do not score your skills. It make looks you amateur. You might have limited knowledge in the area you score yourself. How can you score yourself then? Let others score you
- Use specific keywords are related to your technology domain. Use them in the projects, experience sections. HR looks for them
- Do not pass the about section without telling yourself in. HR is the first person he/she will have a look at your resume. You are supposed to impress him/her first. Tell your soft skills, hobbies in the about section.
- Write the resume in English

### Time Management
Time is the asset that you can not buy with anything(even bitcoin).

Punctuality is the value on the people you meet, hang out with. If you arrive the meeting cafe or attend the video conference on time, you become trustworthy which is the key to being surrounded by qualified people.

Some tricks to manage your time smartly,
- Use calendar for every kind of event, meetings with friends, hiking, deadlines(credit card/loan last payment date), etc. You can not attend two meetings at the same time :) Plan your day before
- Use reminders to not miss anything important. `send the document to xxx`, `call xxx`, `take xxx`
- Prioritize the jobs. Difficult ones first because you will have enough patience and motivation at the start
- Use the kanban board in Trello to manage your projects(especially the freelance ones). [Guide for the kanban board in Trello](https://getnave.com/blog/trello-kanban-boards/)

## Freelance
### Which freelancer platforms are there?
The popular ones are [Upwork](https://www.upwork.com) and [Fiverr](https://www.fiverr.com)
### When is the best time to start freelancing?
Since freelancing is based on experience mostly, you should have at least 2 years of experience in the domain
### How can I calculate the price of a project?
You should estimate the development duration(as hour) of the project first. Multiply the duration with your hourly rate. You can also %25 increase the last price to give a buffer for non-expected bugs/works
