
* banlist.dat: stores the IPs/Subnets of banned nodes
* axe.conf: contains configuration settings for axed or axe-qt
* axed.pid: stores the process id of axed while running
* blocks/blk000??.dat: block data (custom, 128 MiB per file);
* blocks/rev000??.dat; block undo data (custom);
* blocks/index/*; block index (LevelDB);
* chainstate/*; block chain state database (LevelDB);
* database/*: BDB database environment; only used for wallet
* db.log: wallet database log file
* debug.log: contains debug information and general logging generated by axed or axe-qt
* fee_estimates.dat: stores statistics used to estimate minimum transaction fees and priorities required for confirmation;
* governance.dat: stores data for governance obgects
* masternode.conf: contains configuration settings for remote masternodes
* mncache.dat: stores data for masternode list
* mnpayments.dat: stores data for masternode payments
* netfulfilled.dat: stores data about recently made network requests
* peers.dat: peer IP address database (custom format); since 0.7.0
* wallet.dat: personal wallet (BDB) with keys and transactions
* .cookie: session RPC authentication cookie (written at start when cookie authentication is used, deleted on shutdown):
* onion_private_key: cached Tor hidden service private key for `-listenonion`
