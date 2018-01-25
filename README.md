# aethos-client-core
AethOS client core library

This library contains the most commonly used code for AethOS client applications.

This project uses webpack to create Dll bundles.  After building the bundles copy the dist files to the appropriate location (or symolically link them).

*TODO What's the best approach?*

## Installation


```
git clone https://github.com/aethosio/aethos-client-core.git
cd aethos-client-core
npm install
```

Additional global dependencies:

nps (used for running scripts via node start without bloating your package.json)
```
sudo npm install -g nps
```

*TODO Is there a better way other than installing this globally?*

## Build

To build the bundles, run this:

```
npm start build
```

