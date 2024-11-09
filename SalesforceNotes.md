# Salesforce Technologies

## Salesforce User Exerience

- Initially salesforce classic was used. The classic UI was created using Visualforce pages.
  - Visualforce is a proprietary markup language used by Salesforce to create custom user interfaces for mobile and web apps.
- The new UI is called Lightning Experience. It is a modern user interface with a focus on speed and productivity.
  - The salesforce lightning platform UI is built using Aura Components and Lightning Web Components.
    - Aura components are produced by Salesforce and are used to build the Lightning Experience UI. It is more stable
  - Lightning Web Components framework is introduced by Salesforce in 2019. It is a modern framework for building web components using HTML, CSS, and JavaScript.
    - It is faster than Aur framework as it is created using the latest web standards.

## Salesforce Back End

- Salesforce backend is built using Apex.
- Salesforce uses Oracle as its database. However, we do not have direct access to the database. We can only access the database using SOQL and SOSL queries.
  - Objects are tables where records are stored.
  - Apex is used for CRUD operations on objects.
  - Some other tools that can interact directly with the salesforce database
    - Workflow Rules
    - Process Builder
    - Visual Flows
    - Approval Processes

## Salesforce Database

- Salesforce uses Oracle as its database.
- All data is stored in tabluar format

## Declarative Tools in Salesforce

- Used to create applications without writing code.
- Main focus on your problem solving skills and business logic.
- List of declarative tools
  - Workflow Rules
    - One of the oldest automation tools in Salesforce
    - Used to send email alerts, outbound messages
    - Create task
    - Update task
    - Unable to change child record
  - Process Builder
    - Supports all the features of workflow rules except outbound messages
    - We can set up multiple steps
    - More actions are available
    - Can update child records
    - However, we cannot delete any record
    - We cannot update unrelated records
  - Visual Flows
    - Most powerful declarative tool in Salesforce
    - Can execute axpex classes
    - Can execute lightning components
    - We acan write almost all types of logic
    - Similar to writing apex code
    - However, it is slower than apex
    - It is not recommended to use visual flows for complex logic
    - Debugging is difficult in visual flows in some cases
