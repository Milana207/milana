# milana

# Assumptions -  
    # Data is clean and consitent with reliable data for Analysis
    # Price cloumns like current_price and cost_price are in unit - Rupees
    # Stock and quantity_sold are of integers data type
    # sku is unique column to identify different products
    
# Approach
    # Below Approach used to arrive at the required solution
    # Read the 2 csv files using python pandas data frames and read_csv function
    # Merged 2 files to have consolidated data based on unique column "sku"
    # Iterated the series of dataframe using a for loop 
    # Checked the rules applicable based on the conditions given for each product
    # Mandatory check on Minimum profit is performed
    # Using round() rounded the new price to 2 decimal value
    # converted the new updated_prices list to df with units mentioned for old and new price column
    # finally created the output file updated_prices.csv
