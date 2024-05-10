import matplotlib.pyplot as plt

# Sample data (x-axis, y-axis)
x = [1, 2, 3, 4, 5]
y = [3, 7, 1, 10, 2]

# Create the plot
plt.plot(x, y)  # Plot the line using x and y data

# Customize the plot
plt.xlabel("X-axis Label")  # Label for the x-axis
plt.ylabel("Y-axis Label")  # Label for the y-axis
plt.title("Line Plot Title")  # Title for the plot
plt.grid(True)  # Add gridlines for better readability (optional)

# Display the plot
plt.show()
