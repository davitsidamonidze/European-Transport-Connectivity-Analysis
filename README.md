# European-Transport-Connectivity-Analysis
To Compare how well different European regions are connected:  road density travel time to major cities regional accessibility
import pandas as pd
import matplotlib.pyplot as plt
map of transport density
comparison: Western vs Eastern Europe
accessibility gaps

# sample dataset (you can replace with real one)
data = {
    "country": ["Germany", "France", "Poland", "Romania"],
    "road_density": [1.8, 1.5, 1.2, 0.8]
}

df = pd.DataFrame(data)

plt.bar(df["country"], df["road_density"])
plt.title("Road Density Comparison in Europe")
plt.xlabel("Country")
plt.ylabel("Road Density (km/km²)")
plt.show()
