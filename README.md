# SML-ASSIGNMENT-3-QUESTION-1
import pandas as pd

# Assuming df is your DataFrame containing the California housing data
latitude_mean = df['latitude'].mean()
latitude_std = df['latitude'].std()

total_rooms_mean = df['total_rooms'].mean()
total_rooms_std = df['total_rooms'].std()

house_median_age_mean = df['house_median_age'].mean()
house_median_age_std = df['house_median_age'].std()

total_bedrooms_mean = df['total_bedrooms'].mean()
total_bedrooms_std = df['total_bedrooms'].std()

print(f"Latitude: Mean={latitude_mean}, Std={latitude_std}")
print(f"Total Rooms: Mean={total_rooms_mean}, Std={total_rooms_std}")
print(f"House Median Age: Mean={house_median_age_mean}, Std={house_median_age_std}")
print(f"Total Bedrooms: Mean={total_bedrooms_mean}, Std={total_bedrooms_std}")
