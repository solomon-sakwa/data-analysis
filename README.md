import matplotlib.pyplot as plt

# Data: Yearly distribution of malaria-positive cases
years = ["2011", "2012", "2013", "2014", "2015"]
case_distribution = [33, 13, 15, 14, 25]  # Percentage contribution of each year

# Define colors for better visualization
colors = ["red", "blue", "green", "purple", "orange"]

# Create the pie chart
plt.figure(figsize=(7, 7))
plt.pie(case_distribution, labels=years, autopct='%1.1f%%', colors=colors, startangle=140, shadow=True, wedgeprops={'edgecolor': 'black'})

# Title and display
plt.title("Malaria Positive Cases Distribution by Year (2011-2015)")
plt.show()
