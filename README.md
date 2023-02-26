# Minecraft-Colab-Github

Get started with:
[![Open Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://githubtocolab.com/Labnann/Minecraft-Colab-Github/blob/main/minecraft-colab.ipynb)

# Instructions:
Open the aforementioned link and you shall see:
```
Set Up Credentials: Put them inside the quote
github_username = "" #Put your github username here
ngrok_token=""       #Get it here: https://dashboard.ngrok.com/get-started/your-authtoken
github_token = ""    #Create yours here: https://github.com/settings/tokens
github_repo = ""     #Create a new GitHub Repo, if it does not exist and put in the format: "Repo_UserName/RepoName"
```

Put your github username in the quotes. Like this:
```
github_username="Labnann"
```
You will need a github account for this. This is the person who commits or saves game changes.


Similarly fill up ngrok_token. You will need an Ngrok account for this. Try getting it from [here](https://dashboard.ngrok.com/get-started/your-authtoken).

Then fill up like this:
```
ngrok_token="22Auwzd8KTCT_Vh5w__JUST_COPY_PASTE__vp8q195vXySfVQoc"
```

For github to identify you properly you will need an authtoken. Which you can get from [here](https://github.com/settings/tokens).
Then fill up like this:
```
github_token = "ghg_aetjeatjeioataiehtea214af"  
```

Create a github repo for storing minecraft if you haven't already. Put the repository like this:
```
github_repo="RepositoryUserName/RepositoryName"
```

For example:
```
github_repo="Labnann/LabnannMinecraft"
```

Click on run button  for the first two cells sequentially. You should see the server running. 
Ouput from the first cell will also tell you the ip address for connection. Like this:
```
tcp.ngrok.io:13345
```
Use the ip address to connect to the game.


Feel free to open an issue if it is hard to understand. Contributions are welcome.
