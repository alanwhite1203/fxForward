# Currency Forward Introduction and Valuation Guide #


	Overview
A currency forward or FX forward contract is an agreement that allows the buyer to lock in an exchange rate the day on which the agreement is signed for a transaction that will be completed later. Forward contracts are one of the main methods used to hedge against exchange rate volatility, as they avoid the impact of currency fluctuation over the period covered by the contract. 

A currency forward or FX forward is a contract agreement between two parties to exchange a certain amount of a currency for another currency at a fixed exchange rate on a fixed future date. Currency forwards are effective hedging vehicles that allow buyers to indicate the exact amount to be exchanged and the date on which to settle in the forward contract. 

By locking into a forward contract to sell a currency, the seller sets a future exchange rate with no upfront cost. Currency forward settlement can either be on a cash or a delivery basis, provided that the option is mutually acceptable and has been specified beforehand in the contract. Forward contracts are one of the main methods used to hedge against exchange rate volatility, as they avoid the impact of currency fluctuation over the period covered by the contract.
Currency forwards are over-the-counter (OTC) instruments. Unlike standardized FX future, a FX forward can be tailored to a particular amount and delivery period. If an investor will receive a cashflow denominated in a foreign currency on some future date, that investor can lock in the current exchange rate by entering into an offsetting currency forward position that expires on the date of the cashflow. 
The currency forward contracts are usually used by exporters and importers to hedge their foreign currency payments from exchange rate fluctuations.  By using FX forward contracts, investors can protect costs on products and services purchased abroad and protect profit margins on products and services sold abroad by locking-in exchange rates as much as years in advance
Currency forwards can also be used to speculate and, by incurring a risk, attempt to profit from rising or falling exchange rates. A currency forward contract has credit risk. In the case that one of the parties is unable to fulfill its obligation, the other party will have to sign another contract with a third party, thus being exposed to market risk at that time. By locking-in the exchange rates at which the currency will be bought, the party forfeits the opportunity of profiting from a favorable exchange rate movement. This presentation gives an overview of currency forwards and valuation model. 



	Currency Forward or FX Forward Introduction
	A currency forward or FX forward is an agreement between two parties to exchange a certain amount of a currency for another currency at a fixed exchange rate on a fixed future date.
	Currency forwards are over-the-counter (OTC) instruments,
	Unlike standardized FX future, a FX forward can be tailored to a particular amount and delivery period. 
	By locking into a forward contract to sell a currency, the seller sets a future exchange rate with no upfront cost.
	Currency forward settlement can either be on a cash or a delivery basis, provided that the option is mutually acceptable and has been specified beforehand in the contract.
	Forward contracts are one of the main methods used to hedge against exchange rate volatility, as they avoid the impact of currency fluctuation over the period covered by the contract.


	The Use of Currency Forwards
	Currency forwards are an effective hedging vehicle and also allow buyers to indicate the exact amount to be exchanged and the date on which to settle in the forward contract.
	If an investor will receive a cashflow denominated in a foreign currency on some future date, that investor can lock in the current exchange rate by entering into an offsetting currency forward position that expires on the date of the cashflow.
	Currency forwards can also be used to speculate and, by incurring a risk, attempt to profit from rising or falling exchange rates.
	by using FX forward contracts, investors can protect costs on products and services purchased abroad and protect profit margins on products and services sold abroad lock-in exchange rates as much as years in advance
	The currency forward contracts are usually used by exporters and importers to hedge their foreign currency payments from exchange rate fluctuations.
	A currency forward contract has credit risk. In the case that one of the parties is unable to fulfill its obligation, the other party will have to sign another contract with a third party, thus being exposed to market risk at that time.
	By locking-in the exchange rates at which the currency will be bought, the party forfeits the opportunity of profiting from a favorable exchange rate movement. 


	Forex Market Convention
	One of the biggest sources of confusion for those new to the FX market is the market convention. We need to make clear the meaning of the following terms in the forex market first.

	FX quotation: the quotation EUR/USD 1.25 means that one Euro is exchanged for 1.25 USD. Here EUR (nominator) is the base or primary currency and USD (denominator) is the quote currency. One can convert any amount of base currency to quote currency by
QuoteCurrencyAmount = FxRate * BaseCurrencyAmount

	Spot Days: The spot date or value date is the day the two parties actually exchange the two currencies. In other words, a currency pair requires a specification of the number of days between the quotation date (trade date) and the Spot Date on which the exchange is to take place at that quote. Spot days can be different for each currency pair, although typically it is two business days.

	Holidays: Each currency pair has a set of holidays associated with it. The holidays of a currency pair is the union of the holidays of the two currencies.


	Forward FX Rate
Given spot rate X_s , spot date T_s and forward date T, the FX forward rate can be represented as


{■(X_f=X_s  (D_b (T_s,T))/(D_q (T_s,T))                 if  T≥T_s@X_f=X_s  (D_q (T,T_s))/(D_b (T,T_s))                 if  T<T_s )┤
where
	X_s  	the spot FX rate quoted as base/quote
	t 	the valuation date
	T_s 	the spot date (several days after the valuation date)
	T 	the forward date
	D_b (T_s,T) 	the discount factor of base currency from spot date to forward date
	D_q (T_s,T) 	the discount factor of quote currency from spot date to forward date


	

	Valuation


The present value of an FX forward contract is given by

PV(t)=N_b D_b (t,T) X_0-N_q D_q (t,T)
where
	t 	the valuation date
	T 	the payment date
	X_s 	the spot FX rate quoted base/quote
	D_b (t,T) 	the discount factor of base currency from valuation date to forward date
	D_q (t,T) 	the discount factor of quote currency from valuation date to forward date
	N_b 	the notional principal amount for base currency
	N_q 	the notional principal amount for quote currency



	A Real World Example

Delivery Type	Delivery
Leg One Currency	USD
Leg One Notional	120750
Leg Two Currency	CNY
Leg Two Notional	826050.75
Net Price	6.841
Buy Sell	Buy
Base Currency	USD
Underlying Currency	CNY
Quotation	USD/CNY
Trade Date	10/25/2016
Maturity Date	2/26/2018



References:

https://finpricing.com/lib/EqWarrant.html

https://bitbucket.org/cmrm11/fxforward/downloads/FxForward-19.pdf

