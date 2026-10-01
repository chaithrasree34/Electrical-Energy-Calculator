# Electrical-Energy-Calculator
# Electrical Energy Calculator

# Input values
power = float(input("Enter power in watts (W): "))
time = float(input("Enter time in hours (h): "))

# Calculate energy
energy_wh = power * time
energy_kwh = energy_wh / 1000

# Display result
print("\nElectrical Energy Calculation")
print("Energy =", energy_wh, "Wh")
print("Energy =", energy_kwh, "kWh")