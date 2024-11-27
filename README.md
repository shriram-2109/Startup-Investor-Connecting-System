# Capital Catalyst - A Startup-Investor Connecting System
Capital Catalyst is a platform that connects startups with potential investors, facilitating investment opportunities through a user-friendly interface.

## Working of our project : 

#### 1. Clone the repository

```bash
git clone https://github.com/shriram-2109/Startup-Investor-Connecting-System.git
```

#### 2. Install all the required packages

```bash
pip install -r requirements.txt
```

#### 3. Connect SQL database(PostgreSQL) with app.py 

![database](https://github.com/shriram-2109/Startup-Investor-Connecting-System/blob/main/images/database.png)

We have created database in the name "postgres".
```bash
 conn = psycopg2.connect(host="localhost", user="postgres", password="your-password", dbname="postgres")
```

#### 4. Usage

```bash
streamlit run app.py
```

#### 5. Output 

##### Home Page
![home](https://github.com/shriram-2109/Startup-Investor-Connecting-System/blob/main/images/home.png)

##### Input 
![input](https://github.com/shriram-2109/Startup-Investor-Connecting-System/blob/main/images/input.png)

##### List of potential startups to invest in
![out1](https://github.com/shriram-2109/Startup-Investor-Connecting-System/blob/main/images/out1.png)
![out2](https://github.com/shriram-2109/Startup-Investor-Connecting-System/blob/main/images/out2.png)
![out3](https://github.com/shriram-2109/Startup-Investor-Connecting-System/blob/main/images/out3.png)

#### 6. Walkthrough :
[video](https://github.com/user-attachments/assets/649c5ce5-37a2-4367-b708-43dbcd592a54)
