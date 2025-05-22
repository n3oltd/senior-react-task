## Coding Task (React)

This coding task is for a frontend developer and assumes that you are familiar with React.

Your task is to build a simple UI which consumes the provided API and demonstrates the below functionality.

There is no absolute time limit and we won't judge you on how long it took you to complete, however we would suggest you spend no more than 4 hours on this task. We wouldn't ask you to do this task if we didn't already think you looked like a good candidate, so we really appreciate the time you put into this.

### General Instructions

- Use version control
- Please use latest **React** for this project
- Use **Ant Design** or  **Shadcn/ui with Tailwind**.
- You are not required to use a state management library.
- Use any toolchain you wish, but make sure you provide a **README** so we know how to run your app.

### The Task

Please build a simple UI which allows the user to view donation items and create new donation items.

A donation item is an item which can be donated towards by a donor, similar to a product in an e-commerce setting.

Using React, please build a simple UI (single page) which integrates with the API provided. The user should be able to:

- View a list of the current donation items. Please show:
  - Donation item Name
  - Reference (e.g. DI1001)
  - Price
  - Status
  - Location
  - Theme
- Filter the donation items by their Status
- Add a new donation item

To create a donation item, pass the following properties:

| Property | Description                                                   | Validation                                                                                   | Required on Create Request |
| -------- | ------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | -------------------------- |
| Name     | A descriptive name of the donation item                       | - Length between 1-200 <br> - Must be unique                                                 | Yes                        |
| Location | The id of the location where this donation will be spent      | - Must be valid location                                                                     | Yes                        |
| Theme    | The id of the theme towards which this donation will be spent | - Must be valid theme                                                                        | Yes                        |
| Price    | The suggested amount in GBP (£) for this donation item        | - Must be a number/decimal if provided <br> - Currency must be GBP <br> - Amount must be > 0 | No                         |

### The API

All API endpoints are accessible and documented at:

https://n3o-coding-task-react.azurewebsites.net/swagger/index.html

You can use the /reset endpoint to reset the in-memory database.



### Evaluation 

As part of the evaluation, we will be focusing on the following aspects:
- Form Handling / Validation
- Code quality and project structure
- Attention to detail
- UI/UX implementation and responsiveness
- Problem-solving approach
- Readability and maintainability of your code

### Submitting

Please share your solution by sharing the link to the repo.

We look forward to seeing your work!

If you have any questions please feel free to get in touch.
