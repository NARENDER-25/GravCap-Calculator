# GravCap - Gravimetric Storage Capacity Calculator.

GravCap is a Python tool designed to calculate the gravimetric storage capacity of hydrogen molecules adsorbed on the materials. This utility determines the theoretical weight-based storage capacity.

## Features
- Provides the weight percent (wt%) of H2 molecules in the system.
- Calculates molar mass contributions of user-defined atomic compositions from **mendeleev library**.
- User-friendly command-line interface.

## Installation
To install GravCap, clone the repository and use `pip` to install it:
```bash
pip install GravCap
```

## Usage
Once installed, you can run the GravCap tool from the command line:

```bash
GravCap
```

### Example Input 
1. Run the command `GravCap`
2. Enter the number of H2 molecules:
   Enter the number of H2 molecules: 
3. Enter the number of atomic species in your system:
   Enter the total number of  atomic species in your system: n number (if your system has B, O, Li then the number of species should be 3. Don't include H2 molecules)
4. For each atomic species :
   Enter atomic symbol for element 1: atomic symbol of species 1
   Enter the total number of atoms for species 1
   Enter the atomic symbol for element 2: atomic symbol of species 2
   Enter the total number of atoms for species 2
5. The script will calculate and display the molar mass and weight percent of H2.

## Author
- **Narender Kumar**
- **PhD Fellow**
- **Department of Physics**
- **United Arab Emirates University, UAE**  
  Email: bansalnarender25@gmail.com

## License
This project is licensed under the MIT License.

## Dependencies
- `mendeleev` (for atomic weight data)

## Contributing
Contributions are welcome! If you'd like to contribute, please fork the repository and submit a pull request.

## Contact
For any questions or feedback, please contact the author at bansalnarender25@gmail.com
