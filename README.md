
# RuleForge

<img width="959" alt="p1(dark)" src="https://github.com/user-attachments/assets/e17ed6aa-a479-4294-8a1b-09f455e46549">


This project is a 3-tier rule engine application designed to determine user eligibility based on attributes such as **age**, **department**, **income**, **spend**, etc. The system uses **Abstract Syntax Tree (AST)** to represent conditional rules, allowing dynamic creation, combination, and modification of these rules.

## Objective

The application evaluates complex rules dynamically based on a user's data attributes. The system provides APIs for:
- Creating rules and converting them into ASTs.
- Combining multiple rules efficiently.
- Evaluating rules against user data.

## Key Features
- **AST Representation**: Uses AST (Abstract Syntax Tree) to define and evaluate rules.
- **Rule Creation**: Dynamically create rules from strings and represent them in AST form.
- **Rule Combination**: Efficiently combine multiple rules while avoiding redundant checks.
- **Rule Evaluation**: Evaluate rules against a user’s data to determine eligibility.

---
## Functionalities

### For Users:
- **Rule Creation**: Create conditional rules using a simple UI and convert them into Abstract Syntax Trees (AST).
- **Rule Modification**: Modify existing rules by changing operators, operand values, or adding/removing sub-expressions within the AST.
- **Rule Evaluation**: Evaluate rules against user attributes (like age, department, salary, experience) to determine eligibility.
- **Dynamic Rule Combination**: Combine multiple rules into a single AST while minimizing redundant checks using efficient strategies.
  
### For Administrators:
- **Rule Management**: Manage a catalog of user-defined rules, including creating, updating, and deleting rules.
- **View Rule Details**: View detailed representations of rules in AST format for validation and debugging purposes.
  
### General Features:
- **Simple UI**: User-friendly interface for creating and managing rules.
- **API Integration**: Well-defined API endpoints for creating, combining, and evaluating rules.
- **Data Persistence**: Store rules and metadata in a PostgreSQL database to ensure persistence and retrieval.
- **Error Handling**: Implement error handling for invalid rule strings or data formats to ensure robust application behavior.
- **Validation**: Validate attributes to ensure they conform to predefined criteria in the rule catalog.
---
## Snapshots:

### Light Theme:
<img width="959" alt="p1" src="https://github.com/user-attachments/assets/daf22079-0680-4b26-aae9-cf6478a63186">

### Rules Details:
<img width="943" alt="p2" src="https://github.com/user-attachments/assets/2e556085-b162-49d3-b125-09bb144c0efe">

### Create Rule:
<img width="954" alt="p4" src="https://github.com/user-attachments/assets/0fccfbef-caca-472d-996c-efaacdca8858">

### Evaluate Rule:
<img width="959" alt="p3" src="https://github.com/user-attachments/assets/b5e2a38b-9b6e-46aa-a1c8-190b5c07a5bc">

### Database:
<img width="958" alt="p6" src="https://github.com/user-attachments/assets/e26ced63-1c75-4f89-8879-f55219676801">
---

## Installation & Setup

### Steps to Set Up the Project Locally:

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```bash
   cd rule-engine
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Set up environment variables:
   Create a `.env` file with the following keys:
   ```bash
   DB_URL=<your_database_url>
   ```

5. Run the project:
   ```bash
   npm run dev
   ```

---

## Tech Stack

- **Frontend**: Simple UI (React.js or similar)
- **Backend**: Node.js with Express.js
- **Database**: PostgreSQL
- **Rule Engine**: Abstract Syntax Tree (AST)
- **Deployment**: Docker or a cloud service (optional)

---

## Contact

For any questions or contributions, feel free to reach out via:
- [LinkedIn](https://www.linkedin.com/)
- [Email](mailto:youremail@example.com)

---

