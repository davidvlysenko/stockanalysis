Every US stock has an “open” price, corresponding to the market open, and a “close” price, corresponding to the market close. Measuring the move between the open and close prices isn’t a perfect metric for which stocks were most actively traded, but it’s a decent proxy.

The attached spreadsheet has two tabs: “open_prices” and “close_prices”. Each tab contains a list of stocks (speci¬cally, those recently included in the S&P500) and their open/close prices (in addition to other information about each stock). We would like you to create a macro called “largest_mover” that finds the stock with the largest move, up or down, in percentage terms, and pops up a message box that says:

“Largest move was +/- X.XX% in XYZ Equity”

The macro should work even if the spreadsheet changes at some point. For example, stocks may be added to or removed from the index, and sometimes additional columns are added. We guarantee there will always be “Product” and “Price” columns in the first row of both of these tabs, so please use these as references for where to find the necessary information.

The macro should not modify the workbook in any way, even if it reverts those changes later.
