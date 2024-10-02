
# SQL Canvas
*a sql notebook*


SQL Canvas is a lightweight but powerful SQL tool with a notebook interface. 

- There's no **sign up** and **no install**
    - For editing CSVs, JSON, XLSX files, we've integrated [js-xlsx](https://github.com/SheetJS/js-xlsx), and [sql.js](https://github.com/kripken/sql.js/) so you can query data entirely locally in your browser
    - For connecting to **PostgreSQL**, **MySQL**, or **BigQuery**, just run a single command in your terminal to open a bridge that allows Franchise to directly connect to your database. Your data never touches a third party server.
- Chart with a single click
- Compare queries side by side
    - With our [unique notebook layout engine](https://github.com/antimatter15/breadloaf), you can drag and drop cells on the same line to compare views.
    
# Running Locally (Development Mode)
There's an online version of franchise [right here](https://franchise.cloud). There are also instructions for building franchise to static files [here](https://github.com/HVF/franchise/blob/master/DEPLOYING_LOCALLY.md).

Otherwise, here's how to run franchise in development mode:

0. **If you don't have `npm` or `yarn`, install** [yarn](https://yarnpkg.com/en/docs/install).

1. **Open up a terminal and run**

    ```bash
    git clone --depth 1 https://github.com/HVF/franchise.git
    ```

2. **cd into the project directory**
    ```bash
    cd SQL Canvas
    ```

3. **Install the project dependencies**
    ```bash
    yarn install
    ```

    (you can also run `npm install`)

4. **Start the dev server**
    ```bash
    yarn start
    ```

    (you can also run `npm start`)

5. **Open up a browser and go to** `http://localhost:3000`

6. **Edit some files in `SQL Canvas/src`.**
    
    When you save your edits, and the browser will automatically reload.

7. (optional) **Add a bunch of great functionality and send a PR!**

---


