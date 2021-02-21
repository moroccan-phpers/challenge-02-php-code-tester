# Moroccan PHPers

The largest and first PHP community in Morocco.

`Facebook`: https://www.facebook.com/groups/moroccanphpers

`Youtube`: https://www.youtube.com/channel/UCAi3S634OzGKcp1fpHN6yBQ

## Infrastructure design

As part of the interview process, the company **Acme** challenges their applicants by solving some code challenges. So far 
each applicant receives the code challenge per email, solves it and sends back his solution per email in `.zip` format. 
The recruiting team runs firstly some test commands on the solution to make sure it's working before investigating time.

The company wants to improve this process, as they can not for example track when each applicant started and finished the challenge.
So they have decided to build their own platform, where the applicant can write his solution and after hitting the submit button, a series of test commands 
should run automatically without the intervention of any person of the recruiting process.

The frontend part is already implemented by the frontend developers. 
Your task as software engineer, is to design the architecture for the whole backend without implementing it.

##Things to consider

- Each code challenge has its own test classes.
- The same code challenge can be solved by many applicants at the same time.
- For the first step, they want to  allow only challenges in `PHP`.
- Applicants can not submit their solution as guests. They must be logged in (email, password).
- Security

## How to submit your solution?

1 - First of all and after cloning this repo, create your own branch.
> To guarrantee a unique branch name and prevent conflicts,
please name your branch after your email address. `example: git checkout -b anass.rakibi@gmail.com`
>
> Other formats won't be considered. In addition, pushing to the develop branch is not allowed.

2 - Add a `SOLUTION.md` file to your branch, where you write your remarks and explain your solution (if needed). 
It would be better to enforce your solution with design schemas.

## Important notices.

1 - To have enough time to review your solution, I set the next friday: 19-02-2021 at 22:00 (Moroccan Time) to be the deadline for submitting your solution

2 - All solutions will be reviewed and discussed in a live session. Want to be part of it? get in touch with me (anass.rakibi@gmail.com) or through facebook.

