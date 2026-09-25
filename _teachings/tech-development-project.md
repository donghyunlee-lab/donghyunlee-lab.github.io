---
layout: course
title: Technology Development Research Project
description: Each student turns a problem they choose into a working service and learns to explain why it works. We build with Claude Code, in class, every week.
course_code: M04112201
term: Fall 2026
audience: Year 3 · 3 credits
time: Wed 15:00-17:50 (periods 7, 8, 9)
location: Room 2605
instructor: Donghyun Lee
department: Social Science & AI, HUFS
contact: donghyun.lee@hufs.ac.kr
highlights:
  - No exams
  - Individual projects
  - Built in class every week

schedule_title: Weekly plan
schedule_note: The work grows in size as the semester goes on. Weeks with a deliverable end in a submission and a demo.
schedule:
  - weeks: Week 1
    topic: Course format and AI use
    description: What you will produce, how individual grading works, and what you are responsible for explaining.
  - weeks: Weeks 2-3
    topic: Personal homepage and web basics
    description: Information structure, HTML and CSS basics, writing and checking AI requests, Git, a README, and your first deployment.
  - weeks: Weeks 4-5
    topic: Problem definition and scope
    description: A guest lecture on problem definition. You then choose your target user, core flow, and definition of done.
    deliverable: "Week 5: personal homepage due"
  - weeks: Weeks 6-8
    topic: Core features and midterm MVP
    description: Design the user flow and data, build in small steps, and reproduce errors.
    deliverable: "Week 8: midterm MVP and individual demo"
  - weeks: Weeks 9-12
    topic: User feedback and quality
    description: A guest lecture on AI-assisted development, user testing, fix priorities, and checks on sources, personal data, and security.
    deliverable: "Week 12: beta check"
  - weeks: Weeks 13-14
    topic: Deployment and documentation
    description: Make sure someone new can run your service, then prepare your portfolio and presentation.
  - weeks: Week 15
    topic: Final demo and retrospective
    description: Explain the problem, how the service works, how you verified it, and where it falls short, then take questions.
    deliverable: "Week 15: final project due"

grading_note: There are no exams, and every item is graded individually. Design taste, lines of code, commit counts, and prompt counts do not affect your grade. Every project is graded on the same criteria.
grading:
  - when: Ongoing
    item: Attendance
    check: University attendance rules
    weight: 10%
  - when: Ongoing
    item: Participation
    check: In-class development, three-line logs, peer feedback
    weight: 10%
  - when: Week 5
    item: Personal homepage
    check: Public URL, repository, responsive layout, README
    weight: 20%
  - when: Week 8
    item: Midterm MVP
    check: A deployed build with a working core flow, and how you verified it
    weight: 20%
  - when: Week 15
    item: Final project
    check: Final deployment, repository, verification log, demo and retrospective
    weight: 40%

showcase_note: Homepages and services from this course, shared with each student's permission. Students run their own sites, and any project comes down on request.
showcase:
  - title: Donghyun Lee AI Group
    url: https://donghyunlee-lab.github.io/
    summary: A sample card showing how student projects will appear here once students give permission.
    example: true
---

## What you will build

You leave the course with two things. Both run at a public URL, and other people can use them.

- A personal homepage with your introduction, interests, and links to your work. You build it in weeks 2-3 and keep adding your project and retrospective until the end of the semester.
- A working service for a user and a problem you choose. You build the core flow, test it with real users, fix what breaks, and deploy it.

## What you will learn

- Define the user, the problem, the core flows, and a definition of done before writing code.
- Write requests that state the goal, the context, and the completion criteria, then read and run the agent's changes before accepting them.
- Diagnose failures by reproducing them and checking boundary conditions and logs, and confirm each fix under the conditions that exposed it.
- Handle data sources, personal information, and secrets responsibly, and collect feedback from at least three real users.
- Deploy a reproducible service with a README, and explain your design decisions, your verification evidence, and the remaining limits.

## What the course leaves out

- Midterm and final exams
- Group projects with a shared grade
- Lectures that walk through programming syntax in order
- Summary reports on theory
- Paid APIs, payments, or complex authentication
- Projects that handle real sensitive personal data

## A 150-minute class

Most of the time goes to building. During development, the instructor moves around the room and helps wherever you are stuck.

| Part                     | Minutes | What happens                                      |
| ------------------------ | ------- | ------------------------------------------------- |
| Opening                  | 10      | The day's goal and definition of done             |
| Mini-lecture and demo    | 25      | The criteria you will use this week               |
| Development and coaching | 85      | You work on your own project                      |
| Demo and feedback        | 25      | Classmates try your work                          |
| Personal log             | 5       | What you did, how you checked it, what comes next |

Breaks are extra. The log is three lines, and you do not submit your full AI conversation.

## Project tracks

Pick one of four directions. Each starts from a social science interest and ends in a tool people can use.

| Track                            | Examples                                                                                                 |
| -------------------------------- | -------------------------------------------------------------------------------------------------------- |
| Public and social data explorers | Youth employment and population change, living indicators for foreign residents, commuting time and cost |
| Campus and community information | Scholarships and extracurriculars, exchange-student life, campus facilities and events                   |
| Social science research tools    | Survey CSV checker, interview tagging board, literature evidence cards                                   |
| Comparison and simulation tools  | Commuting options, student event budgets, time-use scenarios                                             |

<!-- course:sections -->

## Is this course for you?

The course fits you if you:

- want to build a tool for a problem you have run into
- want a public project to show before you graduate
- want to use AI for development and still judge the results yourself
- learn more from building and fixing than from exams

What you need:

- Your own laptop.
- Access to Claude Code, through a supported subscription or institutional access. We set up installation and login together in week 1.
- No prior web development experience. Week 2 starts from how the web works, then HTML and CSS.
- Readiness to build during class every week.

## FAQ

{% details I have never written code. Can I take this course? %}
Yes. In week 2 we cover how the internet works and how to edit HTML and CSS, and you build your first homepage in that class. You cannot hand in AI output as is, though. You need to run it, check it, and explain what you changed and why.
{% enddetails %}

{% details Is this a group project? %}
No. Deliverables and grades are individual. You sit in studio groups of three or four, try each other's work, and give feedback, but there are no shared grades or group reports.
{% enddetails %}

{% details Can I use AI? How much? %}
You can use Claude Code and official documentation on every assignment. You are responsible for running and verifying the results and for explaining your design and changes. You do not submit your full chat history. Keep secret keys and real personal data out of prompts, repositories, and deployments.
{% enddetails %}

{% details I don't know what to build yet. %}
The week 4 guest lecture and week 5 coaching help you narrow it down. To start, you need one type of user and one problem. A scope you can finish this semester matters more than a big idea.
{% enddetails %}

{% details How much time outside class does it take? %}
Most development happens during the 150-minute class. Deliverable weeks (5, 8, and 15) need extra preparation.
{% enddetails %}

{% details What are the guest lectures? %}
Two are fixed: problem definition and product scope in week 4, and AI-assisted development with code review, testing, and security in week 9. A third, on portfolios and presenting your service in week 13, is optional. Dates may shift depending on the speakers.
{% enddetails %}

<p class="course-note">Based on the Fall 2026 offering. The schedule and guest lectures may change.</p>
