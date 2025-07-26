# Blockhouse Notebook Analysis


## The notebook will be used for the following analysis:
<ul>
  <li> Adding the three bidding tickers in queues</li>
  <li>Calculate the ground truth slippage </li>
  <li> Model the order book with a normal log distribution as written in the answer </li>
  <li> Calculate the slippage given a normal log distribution </li>
  <li> Compare the error percentage in the ground truth and the modelled distribution </li>
</ul>

  Please keep in mind that due to the nature of the data (3 tickers only), the observations and modelling should do fine, 
    but it could do better with more (realistic) data
    
> [!NOTE]
> Please note that there is no need to run anything, as everything is already outputted in the Jupyter Notebook. Only follow the rest of the README if you want to run the file yourself.
  ---

## Environment:

<ul>
  <li>
    Python 3.13.4
  </li>
  <li>
    Ubuntu 22.04
  </li>
</ul>

---

## Installing Requirements

In order to avoid global dependencies conflicts, it is recommended to use a venv before running the requirements.

```bash
pip install -r "requirements.txt"
```

---

## Running the notebook

Simply, open the notebook, press Run > Run All Cells.

