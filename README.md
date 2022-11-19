<div align='center'>

# Doctors Portal
</div>

<p align='left'><i>[Client Section]</i></p>

## `MODULE LIST`
- 71-1 Module introduction and project setup
- 71-2 Setup react router dom layout and routes
- 71-3 Introduction to Daisy UI to use default NavBar
- 71-4 Create simple Top Banner Using Hero component
- 71-5 Make Info Card Dynamic with dynamic CSS Class
- 71-6 Responsive Grid for services section
- 71-7 Pop image out of the section in Appointment section
- 71-8 Add Testimonials with Avatar and fake data
- 72-1 Module Introduction, Recap and Appointment Page
- 72-2 Create Appointment Banner using React Day Picker
- 72-3 Lift up state to share data and Available Appointment Component
- 72-4 Appointment Options and available slots with conditional rendering
- 72-5 Display a modal from on booking click with dynamic data
- 72-6 Create Booking form inside Booking modal
- 72-7 (Recap) Modal data and state interactions
- 72-8 Module summary and Close Modal
- 73-1 Module Introduction and react hook form setup
- 73-2 Setup Login page, and Firebase Project setup
- 73-3 Explore React hook form validation, error handling
- 73-4 (Recap) React hook form to create the Sign up Form
- 73-5 Use RegEx validation in React Hook form
- 73-6 (Recap) Create Auth Context and implement user sign up
- 73-7 (Recap) Implement Login and auth state observer
- 73-8 (Recap) Update Username and conditional sign out
- 73-9 Private Route and redirect user to the page they wanted to go
- 74-3 Simple Overview of React Query and load data
- 74-4 API naming convention and save Booking to database
- 74-5 (Interesting) Find available time slots for a day
- 74-6 (Recap) Load available time slots based on the date
- 74-8 Limit one booking per user per treatment per day
- 75-1 Create Dashboard route with Drawer and Nested Route
- 75-2 Display User specific Appointments using Data Table
- 75-3 Save Registered user information in the database
- 75-5 (Recap) Send JWT token to back end for verification
- 75-6 (Recap) Verify JWT Token and create custom hook
- 75-7 Load all users on the Dashboard page

## `PACKAGES`
#### 1. Create [React](https://reactjs.org/) App
```bash
npx create-react-app your-project-name
```

#### 2. [React Router](https://reactrouter.com/en/main)
```bash
npm install react-router-dom
```


#### 3. Install [Tailwind CSS]((https://tailwindcss.com/docs/guides/create-react-app))
```bash
npm install -D tailwindcss postcss autoprefixer

npx tailwindcss init -p
```

- Configure your template paths.
  Please check and open <i>tailwind.config.js</i> file and replace the code.
    ```bash
        content: [
            "./src/**/*.{js,jsx,ts,tsx}",
        ],
    ```

- Add the Tailwind directives to your CSS <br>
<small>goto ./src/index.css file and open. Then paste the code at the top</small>
    ```bash
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
    ```

#### 4. [DaisyUI](https://daisyui.com/)
```bash
npm i daisyui
```
and then go and open <i>tailwind.config.js</i> and replace the code.

```bash
plugins:
[require("daisyui")],
```

#### 5. [React DayPicker](https://react-day-picker.js.org/)
```bash
npm install react-day-picker date-fns
```

and then go to <i>index.js</i> and paste.
```bash
import 'react-day-picker/dist/style.css';
```


#### 6. [React - Hook](https://react-hook-form.com/)
```bash
npm install react-hook-form
```

#### 7. [React - Hot Toast](https://react-hot-toast.com/docs)
```bash
npm install react-hot-toast
```


#### 7. [Tanstack Query](https://tanstack.com/)
```bash
npm i @tanstack/react-query
```


