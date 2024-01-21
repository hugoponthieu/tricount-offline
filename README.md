# tricount-offline
This version of tricount is a self hosted solution to spread evenly expenses in a group. 

Requirements:
Being able to launch the command:
```zsh
docker compose up
```

First of all clone this repository:
```zsh
git clone https://github.com/hugoponthieu/tricount-offline.git
```

Then open a shell in this freshly cloned directory: 
```zsh
docker compose up
```

You should be able to open a web browser and access the app on http://localhost:8080

Warning: This app will use ports 5432, 3000 and 8080 on localhost. If one of those ports is taken the app will fail launching.