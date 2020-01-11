# HOUSTON v4

# Note:  This version was forked from the original to allow an unsecure connection to your OriginTrail node.  By using this you accept all risks associated with not having a secure connection to your node when making changes.

Houston is a visual user interface for your [OriginTrail](https://origintrail.io "OriginTrail") Node that makes operating it easy for everyone.

## Features
- Setup the node configuration and pricing
- Display all balances on *Management wallet* and *Operational wallet* as well as your *profile* (ERC725 identity)
- Add/remove new management wallets and operational wallets from your profile
- *Deposit ETH* to your Operational wallet
- *Deposit TRAC tokens* to your profile
- *Withdraw* earned token from your profile to your Management wallet 

## How to run Houston?
1. Open your terminal
2. Clone the project to your local machine by running: 

```
git clone https://github.com/Guinnessstache/houston-v4.git
```

3. Enter "houston-v4" folder.
4. When inside the folder please run the following command and wait for the process to be finished: 
```
npm install
```
5. After the installation process is finished run the following command: 
```
npm run houston
```

If Houston app is started you should be seeing the following in your terminal: 
```
-----------------------------------------------
 DONE  Compiled successfully in 9882ms                                                                                                                                                                                                                       
  App running at:
  - Local:   http://localhost:8080/
  - Network: http://xxx.xx.xx.xx:8080/

  Note that the development build is not optimized.
  To create a production build, run npm run build.
 ------------------------------------------------
```
5. Your Houston app is now ready for use. Open your browser and navigate to http://localhost:8080/



## Development instructions




### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
