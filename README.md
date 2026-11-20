# Daily sales pipeline

An online shop exports its data every night as files. The finance team wants a daily sales report they can trust.

## What's in this repo

- `data/orders.csv`: one row per order version
- `data/customers.json`: customer master data, including country
- `pipeline/`: your code goes here
- `tests/`: your tests go here

Treat the files like a real export from a production system.

## Your task

Build a small pipeline that:

1. Loads both files.
2. Prepares the data so it is fit for a finance report.
3. Writes `output/daily_sales.csv` with the columns `date, country, order_count, sales_eur`.
4. Has tests for the parts you think matter most.

Use any AI coding agent you like. You own the result: accept, change or reject anything the agent suggests. At the end you'll walk us through the code, so be ready to explain every part of it. Unfinished is fine; tell us what you would do next.

## Setup

```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
pytest
```
