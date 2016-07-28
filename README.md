# trutify
web app (based on ethereum smart contract) for transffering and tracking ownership of luxury and highly traded goods


App uses local dev ethereum node server (https://github.com/blockapps/bloc)

install
```sh
npm install
```

generate first user (admin)
```sh
bloc genkey
```

compile and deploy contract
```sh
bloc compile Trutify
bloc upload Trutify
```

run local server
```sh
bloc start
```

open website

trutify-ui/index.html
