# Problem Set 5

Follow the instructions below to get the project up and running on your machine

##### 1. Cloning the repository

Navigate to your `workspace` directory and run the following command:
```
git clone https://github.com/JakobMakovac/PS5.git
```
Then move to the cloned directory: 
```
cd ./PS5
```

##### 2. Setting up Python virtual environment
We will be using the python virtual environment to simplify the libraries we are going to use for our project, so run the following command to create the environment:
```
python -m venv ./venv
```
Next we need to activate the virtual environment:
##### 2.1 MacOS
To activate the virtual environment run the following command and move to 2.3:
```
source venv/bin/activate
```
##### 2.2 Windows
To activate the virtual environment run the following command and move to 2.3:
```
venv/bin/activate
```
If you encounter an error that says something like this:
```
+ CategoryInfo : SecurityError: (:) [], PSSecurityException
+ FullyQualifiedErrorId : UnauthorizedAccess
```
move to 2.2.1
##### 2.2.1 Setting the permissions on Windows
Open your terminal (Powershell / Command Prompt) as administrator. Right click -> open as Admin
Then run the following command:
```
Set-ExecutionPolicy RemoteSigned
```
and confirm with `Y` if necessary. After that return to your editor and return to 2.2.
##### 2.3 Verify the virtual env is active
The prompt on your terminal should display the active environment like this:
![image](https://github.com/JakobMakovac/PS5/assets/13966429/78877abe-7c3f-4832-a52f-e0f120dc161c)

##### 3. Installing the libraries
Simply run the following command:
```
python -m pip install -r requirements.txt
```
which will install all the libraries we specified in the `requirements.txt` file

##### 4. Verify the project is running correctly
Run the project with:
```
python ./ps5.py
```
You should see this window open:
![image](https://github.com/JakobMakovac/PS5/assets/13966429/1f16b983-020f-448f-af97-fe2cd2acad66)

And the following error in the terminal:
`Polling . . . name 'NewsStory' is not defined`

This means that the project is working and we can start implementing the missing classes. Good luck!
