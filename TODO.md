# TODO - Complete Many-To-Many Relationships Lab

## Plan

### Step 1: Update server/models.py
- [ ] Add association table `employee_meetings` for many-to-many relationship between employees and meetings
- [ ] Create `Employee` model with relationships to meetings, assignments, and association proxy for projects
- [ ] Create `Meeting` model with relationship to employees
- [ ] Create `Project` model with relationship to assignments and association proxy for employees
- [ ] Create `Assignment` model for many-to-many relationship with attributes between employee and project

### Step 2: Run database migrations
- [ ] Initialize migration if needed
- [ ] Create and run migrations for the new models

### Step 3: Update server/seed.py
- [ ] Import all necessary models and the association table
- [ ] Delete data from all tables in correct order
- [ ] Add seed data for employees
- [ ] Add seed data for meetings
- [ ] Add seed data for projects
- [ ] Add many-to-many relationships between employees and meetings
- [ ] Add assignments (employee-project relationships)

### Step 4: Run the seed script
- [ ] Execute `python seed.py` to populate the database

### Step 5: Run tests
- [ ] Execute tests to verify everything passes

