# Derivatives using Taylor Series
This MATLAB application calculates the derivative at a specified point using:

1. x values - The points at which the function is evaluated.
2. f values or a function - The corresponding function values or the function itself.
3. h (tolerance or precision) - The step size used to approximate the derivative.

Application built using MATLAB's App Designer and requires the Symbolic Math Toolbox.

<img src="https://github.com/user-attachments/assets/a70b5712-26b2-4013-9770-6ffca3a0a239">

## Prerequisites
Before running this program, ensure you have the following installed:

- MATLAB (R2021a or later recommended)
- Symbolic Math Toolbox (required for symbolic computations)

### Installing the Symbolic Math Toolbox
1. Go to the Home tab in MATLAB.
2. Click on Add-Ons and search for "Symbolic Math Toolbox".
    <img src="https://github.com/user-attachments/assets/908480ed-84c2-4db5-9c39-ccff68855844">
    <img src="https://github.com/user-attachments/assets/12eecaaa-3c1a-4459-9d57-79f4e0933a80">
4. Click Install to add it to your MATLAB installation.

## Getting Started

1. Clone repository.
    ```bash
    git clone https://github.com/leovergaramarq/derivatives_using_taylor_series.git
    ```
2. In MATLAB, from the Home tab, click Open and browse the `derivative_calculator.mlapp` file.

   <img src="https://github.com/user-attachments/assets/d9efe481-cbad-4834-a2cb-7d68e9f34400">
   
   Alternatively, you can double-click the `derivative_calculator.mlapp` file in your file explorer and open it with with MATLAB.
2. Run the application by clicking the Run button in the App Designer.
3. In the application interface:
    1. Input the x values.
    2. Input the f values (or select the function if applicable).
    3. Specify the value of h (precision).
    4. Specify the derivative order.
    5. Indicate the point around which to find the derivative.
    6. Click Go to compute the derivative at the specified point.

    <img src="https://github.com/user-attachments/assets/b183714d-f4f1-4dbb-8f4a-fa83c935cf8a">
