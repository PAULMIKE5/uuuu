const TronWeb = require('tronweb');
const express = require('express');
const app = express();
const port = 3000;

const tronWeb = new TronWeb({
  fullHost: 'https://api.trongrid.io',
});

// Define a route for getting account details
app.get('/account/:address', async (req, res) => {
  try {
    const address = req.params.address;
    const account = await tronWeb.trx.getAccount(address);
    res.json(account);
  } catch (error) {
    res.status(500).json({ error: error.message });
  }
});

// Define a route for getting transaction details
app.get('/transaction/:txid', async (req, res) => {
  try {
    const txid = req.params.txid;
    const transaction = await tronWeb.trx.getTransaction(txid);
    res.json(transaction);
  } catch (error) {
    res.status(500).json({ error: error.message });
  }
});

// Start the server
app.listen(port, () => {
  console.log(`Tron API listening at http://localhost:${port}`);
});
