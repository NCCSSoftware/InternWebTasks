# Learning Laravel Roadmap Week 3-4
Expected daily commitment: 5 hours
Total duration: 2 weeks (60 hours total)

## Week 3: Authentication and Basic Features (30 hours)

### Day 1-2: Authentication Setup (10 hours)
- Setup Laravel Sanctum for authentication [Read Guide][sanctum]
    - Install and configure Sanctum
    - Create basic authentication endpoints
    - Test token generation
- Implement login/register system
    - Create auth controllers
    - Setup email verification
    - Add password reset functionality

### Day 3-4: User Management (10 hours)
- Create role system [Read Guide][laravel-auth]
    - Add roles table migration
    - Create role middleware
    - Implement basic admin/user roles
- Setup user profile management
    - Create profile update functionality
    - Add avatar upload feature
    - Implement password change

### Day 5-6: Database Relations (10 hours)
- Implement relationships [Read Guide][eloquent]
    - Setup User-Todo relationship
    - Create categories for todos
    - Add proper soft deletes
    - Test all relationships

## Week 4: UI Implementation and API Development (30 hours)

<details>
<summary>Full Stack Track</summary>

#### Day 1-2: Frontend Setup (10 hours)
- Setup Tailwind and Soft UI [Read Guide][soft-ui]
    - Install Tailwind CSS
    - Configure Soft UI Dashboard
    - Setup basic layout components
- Configure Livewire [Read Guide][livewire]
    - Create base components
    - Setup event listeners
    - Add real-time validation

#### Day 3-4: UI Components (10 hours)
- Create dashboard components
    - Todo list component with filtering
    - Todo creation modal
    - Category management
    - User profile page
- Implement Soft UI elements
    - Navigation sidebar
    - Stats cards
    - Data tables
    - Action buttons

#### Day 5-6: Advanced Features (10 hours)
- Add interactive features
    - Real-time updates
    - Search functionality
    - Filtering system
    - Activity logging
</details>

<details>
<summary>API Track</summary>

#### Day 1-2: API Structure (10 hours)
- Setup API architecture [Read Guide][api-structure]
    - Create API routes
    - Setup versioning
    - Implement rate limiting
    - Add authentication middleware

#### Day 3-4: API Development (10 hours)
- Implement CRUD endpoints
    - Todo management
    - Category management
    - User management
    - Add proper validation

#### Day 5-6: Testing & Documentation (10 hours)
- Write API tests [Read Guide][testing]
    - Create feature tests
    - Add unit tests
    - Test authentication
- Document API endpoints
    - Create Postman collection
    - Add request examples
    - Include environment variables
    - Export and share collection
</details>

### Required Features for Both Tracks
1. User Management
   - Registration with email verification
   - Login with remember me
   - Password reset
   - Profile management

2. Todo Management
   - CRUD operations
   - Categories with color coding
   - Due dates
   - Priority levels (Low, Medium, High)
   - Status tracking

3. Dashboard Features
   - Todo statistics
   - Recent activities
   - Category overview
   - Search and filters

### Technical Requirements
- Follow PSR-12 coding standards
- Implement proper error handling
- Add request validation
- Use repository pattern
- Write clean, documented code
- Use proper Git workflow
- Complete Postman collection documentation

[sanctum]: https://laravel.com/docs/10.x/sanctum "Laravel Sanctum Documentation"
[laravel-auth]: https://laravel.com/docs/10.x/authentication "Laravel Authentication"
[eloquent]: https://laravel.com/docs/10.x/eloquent-relationships "Eloquent Relationships"
[soft-ui]: https://www.creative-tim.com/learning-lab/tailwind/html/quick-start/soft-ui-dashboard/ "Soft UI Dashboard"
[livewire]: https://livewire.laravel.com/docs/quickstart "Livewire Quickstart"
[api-structure]: https://laravel.com/docs/10.x/controllers#api-resource-routes "API Resource Routes"
[testing]: https://laravel.com/docs/10.x/http-tests "HTTP Tests"

### Daily Progress Requirements
- Commit code at least once per day
- Document any issues or blockers
- Review and test previous day's work
- Seek help if stuck for more than 2 hours

### Evaluation Criteria
1. Code quality and organization
2. Feature completeness
3. UI/UX implementation
4. Testing coverage
5. Documentation quality
6. Git commit history

### Deadline: Jan 5, 2025, 00:00 (Nepal Time +5:45)

    PS: After completing these tasks, actual project work will start. So, make sure you understand the concepts and implement them properly.
