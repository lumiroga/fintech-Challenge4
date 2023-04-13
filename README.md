# Challenge IV | Risk Return |Fintech <img src="https://instructure-uploads-pdx.s3.us-west-2.amazonaws.com/account_150420000000000001/attachments/590996/columbia.png" height="48" width="48">

---

This is the 4th challenge for Quantitative Analysis.
The idea is to create different analysis metrics to evaluate 4 different portfolios considering the S&P 500 index as a base.

The program is based on a Jupyter Lab file which process the four funds and the S&P 500 INDEX from October 2014 to September 2020.

The evaluated funds are: 

- **PAULSON & CO.INC.**            
- **SOROS FUND MANAGEMENT LLC**    
- **TIGER GLOBAL MANAGEMENT LLC**    
- **S&P 500**                        
- **BERKSHIRE HATHAWAY INC**   

Information is obtained in file: [Funds data set](./Resources/whale_navs.csv)

---

## Libraries Used

The main language is Python embeded in Jupyter lab

### jupyter

This modules creates a notebook and processes a python kernel.

### pandas

Library that handles Dataframes and Series to process data, filter, create statistics

### matplotlib

Library to plot graphs

### pathlib

This module helps abstracting the OS discrepancies between folder structures and files.

### Numpy

This module helpswith Math calculations, particulary Square Root for Annualized Standar Deviation

---

## Usage

To run program just open the terminal (anaconda needs to be installed) and type the following

``` bash
$ git clone https://github.com/lumiroga/fintech-Challenge3.git
$ cd fintech-Challenge4
$ jupyter lab 

```

Open a browser with the displayed URL in Jupyter

Look for *risk_return.ipnyb* file and open it.

---
# Analysis Description

## Quantitative Analysis 

The Quantitative Analysis proved S&P 500 is out performing the remaining 4 funds.



## Analyze the Volatility

The Quantitative Analysis proved **BERKSHIRE HATHAWAY INC** is the most volatile fund and **Tiger Global** the least volatile


## Analyze the Risk

The Risk Analysis shows the S&P 500 has the most risk, meanwhile, the Berkshire Hathaway Fund is the most risky of the funds. The pattern doesn't change much when the Standard Deviation (risk) is annualized or in a 21 days rolling window.

## Risk Return Profile

The Risk Return Profile explains that even if Berkshire Hathaway is the most risky portfolio, it gives the best Sharpe Ratio, even better than S&P 500, so it is a better investment option at least from the current metrics.

## Diversify Portfolio

When looking at the covariance we see that the 2nd best fund (considering Sharpe Ratio) is the least sensitive to S&P 500 changes. And looking at the volatility at the beginning of the challenge, we can tell **Tiger Global** seems to be the best investment option judging from the information we get at the challenge.


## Contributors

[lumiroga](https://github.com/lumiroga)

---

## License

* mpl-2.0 | Mozilla Public License 2.0