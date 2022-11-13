<div align='center'>

# Doctors Portal
</div>

<p align='left'><i>[Client Section]</i></p>

## `MODULE LIST`
- 71-1 Module introduction and project setup


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

