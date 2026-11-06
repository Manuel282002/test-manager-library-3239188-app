# Manager Library — Frontend App (React)

This repository houses the reactive user interface for **Manager Library**, built with **React** based on the user stories provided in the specification.

##  Developed Components
The application is modularly structured within the `src/` directory:
- **`BookList.jsx`:** Responsible for tabulating the active book catalog, enabling dynamic search by text matching, and interacting cleanly with the `/api/v1/books` contract parameters.
- **`LoanForm.jsx`:** An intelligent form for operational loan registration. It reactively handles business exceptions, blocking transactions that exceed the 1-to-3 item limit or input duplicate books.
- **`App.jsx`:** The main orchestrator that integrates and distributes the system views into a clean administrative dashboard layout.
