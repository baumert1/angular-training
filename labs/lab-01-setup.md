# Lab one - Setup and install dependencies

### Checkout the Github repository

- Checkout project from Github

```
git clone https://github.com/objectpartners/angular-timesheet.git
```

- You should get output similar to below:

```javascript
Cloning into 'angular-training'...
remote: Counting objects: 3003, done.
remote: Compressing objects: 100% (1458/1458), done.
remote: Total 3003 (delta 1413), reused 2684 (delta 1256)
Receiving objects: 100% (3003/3003), 1.44 MiB | 1.15 MiB/s, done.
Resolving deltas: 100% (1413/1413), done.
Checking connectivity... done.
```

- Change directories to the lab main directory.

```
cd angular-timesheet
```

- Now let's checkout the `lab-1-setup` branch.

```
git checkout lab-1-setup
```

### Install the application dependencies

- Install the NPM dependencies

```
npm install
```

- Install the Bower dependencies

```
bower install
```
- Compile the `less` and template files.

```
grunt development
```

### Run the application and view the start screen

- In a console window, run:

```
grunt runapp:development
```

- This kicks off a Node server and serves up our `index.html` page.

- Open your browser and navigate to http://localhost:3000.

- Verify that you see the welcome page.

- Now let's check out our project's structure so we know what goes where.
