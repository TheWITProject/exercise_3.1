## Summary
You will be designing a schema for a to do list application. Please create your schema with visual tool like [Ziteboard](ziteboard.com) or [Figma](https://www.figma.com/login), and add a screencap of your final schema to this this project directory. Once you are done with this exercise, please push your code and open a PR with the following name: `<YOUR_NAME>_exercise_3.1`.

## Instructions
Design a schema for a to do list application.

<details>
<summary>Every to do list application needs tasks. Let's start with a Task table. What fields should Task have?</summary>

- Primary Key
- Name
- Description
- Priority
- Due Date
- Completed

</details>


<details>
<summary>Let's make sure we can also handle multiple projects and assignees. What kind of tables should we add to our schema for this? What fields should they have?</summary>

Project
- Primary Key
- Name
- Description

User
- Name
- Email

</details>

<details>
<summary>What kind of validations should we place on our fields?</summary>

- Task - Due Dates cannot be before today
- Task - Priority must be a number between 1 and 5
- Task - Completed should be a boolean.

</details>

<details>
<summary>How can we represent the relationships between our tables?</summary>

- Projects and Tasks may be one-to-many or many-to-many
- Users and Tasks can be one-to-many or many-to-many

</details>

<details>
<summary>What else can we add to our schema? Start with a feature or functionality you want to your add. What tables do you need to support that feature?</summary>

- How might we represent sub tasks?
- How might we represent teams?

</details>

## To-Do List Scheme on Figma 
https://www.figma.com/file/xUcFv6T3CapTyDvqvRBudQ/WIT-Exercise-3.1-To-Do-List?node-id=0%3A1 
