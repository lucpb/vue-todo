tags: #docs

### Back to [[docs]]


---

## 1. Setup Project Environment
- Install required tools (Node.js, PostgreSQL, Git, editor, etc.).  
- Initialize Git repository.  
- Setup folder structure for frontend, backend, and documentation.  
- Configure `.gitignore` and environment files.  

---

## 2. Requirements & Pseudocode
- Define features and acceptance criteria.  
- Write **pseudocode** for backend logic, API routes, and data flow.  
- Outline user interactions in plain language before coding.  

---

## 3. Frontend Wireframing
- Sketch UI components and page layouts (see `frontend-wireframe`).  
- Map component hierarchy (parent/child components).  
- Validate flow against user requirements.  

---

## 4. Database Schema Design
- Define tables, fields, and relationships (see `database-schema`).  
- Ensure normalization and constraints are clear.  
- Plan for migrations and seed data.  

---

## 5. Backend Setup
- Initialize Express app.  
- Define routes and controllers.  
- Connect database and configure ORM/query builder.  
- Write initial API stubs for frontend integration.  

---

## 6. Git Branching
- Create a new branch for each feature (`feature/auth`, `feature/ui-tasklist`).  
- Commit often with meaningful messages.  
- Push branch and sync with `dev`.  

---

## 7. Development
- Implement one feature at a time.  
- Use pseudocode and wireframes as guides.  
- Test frontend-backend integration as you build.  

---

## 8. Testing
- Write unit tests for backend functions.  
- Add integration tests for APIs.  
- Perform UI/UX testing on frontend flows.  
- Fix bugs before PR.  

---

## 9. Pull Request & Code Review
- Open PR from feature branch → `dev`.  
- Write clear PR description with Trello link.  
- Request review and make revisions.  

---

## 10. Deployment
- Merge into `main` after PR approval.  
- Run CI/CD pipeline (see `deployment` doc).  
- Deploy to staging → production.  
- Run smoke tests in production.  


