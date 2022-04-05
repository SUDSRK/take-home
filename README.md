# Take-home Tasks for Food Darzee
___
Hello, If you have received this test or stumbled upon it then we're likely in the process chatting with you about a Developer role at Food Darzee, or you are interested in working with us.

In order to move forward, we'd like to know a little about how you work. This contains a set of instructions that can demonstrate your skills and abilities.

These are NOT coding tasks. The goal of these tasks are to give you an asynchronous medium for demonstrating how you would break down a set of user stories and requirements into something akin to a rapid POC/spike. There is no grading or scoring, nor is it pass-fail, rather these are meant to serve a sample of your reductive thought processes as an engineer.

## First, a few words about why these tasks

We know that the technical hiring processes in our industry are generally broken. 
We also know that there are mixed opinions on take-home tasks in general. 
The primary reasons we ask candidates of all levels to complete these tasks are as follows.

* These tasks allow you to show off your skills at a time/place that works for you.
* Take-home tasks allow you to work at your own pace. We intentionally structure these to take around 8-12ish hours of time and ask that you limit your investment to no more than the suggested time, however you are free to break this into as many sessions as you wish.
* It matches the nature of our work. Most being an engineer on a remote team is self-directed exploration of a problem, followed by period(s) of cyclic work/edit/review, followed by submission for review and approval by your peers. Async tasks allow you to do the same.
* It eliminates the performance anxiety of forced-pairing with someone whom you've just met.
* It allows you to use the tools, languages, and frameworks where you are the most productive.


## General Instructions

1. Choose an exercise directory that matches your primary domain. This is the area in which you feel the most comfortable and have the highest degree of mastery
    * [frontend](frontend/README.md)
    * [backend](backend/README.md)
2. Read the `instructions.md` file in the matching directory. Be sure to read the instructions carefully and ask any clarifying questions either via [GitHub Issues](https://github.com/FoodDarzee/take-home/issues) or by emailing hr@fooddarzee.com
3. Create a new **private repository** for your exercise and add [Wenceslaus Dsilva](https://github.com/deadmantfa) as private collaborators.
4. Complete as much of the exercise as you can in 8-12 hours or less. Unless otherwise specified in the `instructions.md` document, you can use any language, framework, or toolchain you wish, although ideally this would be PHP, Python, Javascript, and SQL (purely because those are the languages we used to build Food Darzee and will be the most familiar with)
5. Be sure to include the following in your submission 
    1. A `README.md` with the following information
        1. **A few screenshots of the finished product.** Show off that work!
        2. The exercise you choose and why
        3. A short explanation of what you built
        4. How to test/demo/run (if applicable)
            1. NOTE: a 'working' exercise is awesome, however it is *NOT* a hard requirement. We mean it!
        5. Any feedback/notes (i.e. if something was hard, confusing, frustrating, etc)
        6. Anything else you'd like us to know about your submission
    2. A ROADMAP.md with what you would add/change if you had more time. Dream big.
    3. A super-simple test suite if applicable (even one test is a bonus)
    4. Some form of lightweight technical documentation (code comments are fine)
6. When complete, email a link to the repository and any special instructions to hr@fooddarzee.com
7. Sit back and relax. We'll review your submission and get back to you within 72 hours

## How we review
Your task will be reviewed by one of our developers. We do take into consideration your experience level

**We value quality over feature-completeness.** It is fine to leave things aside provided you call them out in your project's README. The goal of this code sample is to help us identify what you consider production-ready code. You should consider this code ready for final review with your colleague, i.e. this would be the last step before deploying to production.

The aspects of your code we will assess include:

* Architecture: How clean the code is and the project structure
* Clarity: does the README clearly and concisely explains the problem and solution? Are technical tradeoffs explained?
* Correctness: does the application do what was asked? If there is anything missing, does the README explain why it is missing?
* Code quality: is the code simple, easy to understand, and maintainable? Are there any code smells or other red flags? Does object-oriented code follows principles such as the single responsibility principle? Is the coding style consistent with the language's guidelines? Is it consistent throughout the codebase?
* Security: are there any obvious vulnerability?
* Technical choices: do choices of libraries, databases, architecture etc. seem appropriate for the chosen application?

Bonus point (those items are optional):

* UX: is the web interface understandable and pleasing to use? Is the API intuitive?
* Scalability: will technical choices scale well? If not, is there a discussion of those choices in the README?
* Production-readiness: does the code include monitoring? logging? proper error handling?
