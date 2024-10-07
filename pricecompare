def calculate_price_differences(current_price, all_time_high, all_time_low):
    # Calculate the percentage difference from the all-time high
    high_diff = ((all_time_high - current_price) / all_time_high) * 100
    
    # Calculate the percentage difference from the all-time low
    low_diff = ((current_price - all_time_low) / all_time_low) * 100
    
    return high_diff, low_diff

# Example usage:
current_price = 20000
all_time_high = 30000
all_time_low = 10000

high_diff, low_diff = calculate_price_differences(current_price, all_time_high, all_time_low)

print(f"The current price is {high_diff:.2f}% lower than the all-time high.")
print(f"The current price is {low_diff:.2f}% higher than the all-time low.")
