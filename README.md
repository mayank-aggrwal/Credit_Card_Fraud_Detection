# 💻 Credit Card Fraud Detection

[![](https://img.shields.io/badge/python-3.8.5-blue)](https://python.org/downloads/)

Detecting Credit Card fraudulent transactions using Machine Learning
It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.

Dataset used is from Kaggle - https://www.kaggle.com/mlg-ulb/creditcardfraud
The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.
Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

## Installation
1. Make sure python3 and git is installed.
Install Python :
From [official website](https://www.python.org/downloads/)
2. Clone this repository to your local machine.
3. Run the following command for installing all the required dependencies all at once-

4. Download the dataset file creditcard.csv from Kaggle link provided above.
5. Run fraud_detection.ipynb in a jupyter notebook
```bash
jupyter notebook fraud_detection.ipynb
```

## Additional instructions

### Install Python :
From [official website](https://www.python.org/downloads/)


### To check version of Python :
```bash
py --version
python --version
```

### Create a virtual environment :
```bash
py -m venv blog_app
```

### To activate virtual-environment :
```bash
.\Scripts\activate
```

### To deactivate virtual-environment :
```bash
.\Scripts\deactivate
```

### To check python is used in virtualenv :
```bash
pip -V
```
If you are running the virtual env, it'll show the path to the environment's location.

### To install a package in virtual environment :
```bash
py -m pip install package_name
```

### To install django :
```bash
py -m pip install django
django --version
```

### To check django version :
```bash
py -m django --version
```

### To start a new app :
```bash
python manage.py startapp your_app_name
```
Then make an entry for the app in the INSTALLED_APPS section in settings.py
Include URL's of your new app using include() in url.py (main app)

### While activating if terminal shows, "running scripts is disabled on this system"
There are 4 policy levels to choose from. From most secure to most insecure:
1. Restricted: No Powershell scripts can be run. This is the default setting.
2. AllSigned: Scripts can be run, but all must have a digital signature. Even if you wrote the script yourself on the local computer.
3. RemoteSigned: Locally-written scripts can be run. But scripts from outside (email, IM, Internet) must be signed by a trusted publisher.
4. Unrestricted: Any script will run. Regardless of who created them or whether they are signed. 

    To view the current systemwide Execution Policy setting :
    ```bash
    Get-ExecutionPolicy
    ```

    To set execution policy :
    ```bash
    Set-ExecutionPolicy remotesigned
    ```

### Touch alternative in windows powershell :
```bash
$null > file_name.cpp
```

### Configure GIT :
```bash
git config --global user.email "user_mail"
git config --global user.name "user_name"
```

###### NOTE: Make .gitignore file after initialising the GIT repository
<br>

### To run the application server :
```bash
python manage.py runserver
```

### For migrating the models to the database :
```bash
python manage.py makemigrations
python manage.py migrate
```

### While making a POST request through a form to the server, include :
```python
{% csrf_token %}
```

### To checkout a particular branch:
```bash
git checkout <branch-name>
```

### To list all the branches in the git repository:
```bash
git branch -a
```
### To lists all the modules installed for the project:
```bash
py -m pip freeze
py -m pip list
```

### To merge a branch into master branch:
> Change to master branch
```bash
git checkout master
git merge <branch-name>
```

### To see branch graphs in git:
```bash
git log --graph --oneline --decorate --all
```

### To see all remotes
```bash
git remote -v
```

### To push all branches to remote repository
```bash
git push --all <remote-origin>
```

### To add a new remote to push changes to
```bash
git remote add new-remote-origin-name https://github.com/user_name/repo.git
```

### If you happen to delete db.sqlite3 file, run:
```bash
python manage.py migrate
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)