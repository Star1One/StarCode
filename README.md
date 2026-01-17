

# React App

## 📚 Adding books to the list using **json-server**

This book list app is built using **React**.

---

### 🛠 Configuration

In this App, we are going to have a list of books that we can use and be able to add and delete them.

We first created a list for books, where we can add new books and also delete or hide them.

We use **json-server** to do things and we are able to save books or add and remove from the list.

The add book form is displayed as a **modal**.

### 🔸 After download:

```terminal
    npx json-server --watch data/db.json port3000

    npm run start
```

Everything is ready now.

---

#### 🔹 App Advantage:

- Add a book to the list.

- Save & Delete from json-server.

- Show & hide items.

---

### 📸 Screenshots

![Weather App Screenshot](image/book-list.jpg)


---


# ReadMe

---


# 🌐 Local weather app

## 🔸 About the Project:

This weather app is built using **Vanilla JavaScript** and displays real-time weather conditions.

### Current weather data
- Weather App using OpenWeatherMap API & ip-api.com

  - 🔗 https://openweathermap.org/api
  - 🔗 https://ip-api.com

- A weather app made using OpenWeatherMap API in Vanilla JavaScript.

- The app tells the current temperature in Celsius, Fahrenheit, and Kelvin, as well as some additional information like Location Timezone, WeatherMain(Icon), WeatherDescription.

## ⚙️ Configuration
- If you want to use the OpenWeatherMap API, you need to get an API key. To set up your API key, follow these steps:

- Go to the OpenWeatherMap website: 🔗 https://openweathermap.org/
- Sign up for a free account or log in if you already have an account.
- Once logged in, go to your profile and navigate to the "API Keys" section.
- Generate a new API_key and copy it. 

- In the project directory, find the app.js file. Inside this file, you will find a constant called API_KEY. Replace the value 'API_KEY' with your actual API key that you received from OpenWeatherMap.

---

#### ✨ The app shows:

- Current temperature in **Celsius, Fahrenheit, and Kelvin**
- Location **timezone**
- Weather condition **icon**
- Weather **humidity**
- Weather **description**
- Real-time local **clock**

---

### 📸 Screenshots

![Weather App Screenshot](icon/weather2.jpg)


---


---


---



# 📚 JavaScript & SQL Server Book List App

## Add a book to the list

 This book list app is built using **Vanilla JavaScript** and **SQL Server** to save data.

---

### ⚙️ Configuration

Below is a clear, step-by-step beginner-friendly guide that shows exactly how to do the following:

**1.** Please download app file and database file.

**2.** You must use SQL Server authentication.

**3.** Open the server.js file and set your SQL Server authentication username and password.

**4.** If you are using a different port, Update the URL in **origin** in the server.js file.

**5.** Go to the project path on your system.

**6.** Open **Git Bash, CMD or PowerSell** in your project folder.

Example:
```bash
cd D:\project\Book-List-Sql>
node server.js
``` 
#### Attention:

**7.** If you don't have Node.js you need to install it.

**8.** How to install Node.js?

- 🔗 https://nodejs.org

**9.** After installing Node, in **bash, cmd, powerSell** :

#### Install dependencies

```bash
npm install
node server.js
```

**10.** Run everything from server.js.

**11.** Add (attach) a SQL Server **database** file

**12.** In SQL Server, select and run database file(List), and open the tables file select dbo.tblBookList.

```sql
use [List]

select * from tblBookList
```

**13.** Now you can see the SQL table.

**14.** Run **index.html** in the JavaScript App. 

**15.** You will see the list of seven books from both the app and SQL Server table.

**16.** Everything is now ready to start.

---

#### 🔹 App Advantage:

- Save data in SQL Server table

- Add a book to the list

- Show and hide the book list

- Delete books

- Search for books

---

### 📸 Screenshots

![Weather App Screenshot](images/bookList.jpg)
