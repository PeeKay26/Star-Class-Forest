# Star-Class-Forest
## Automated Star Classification with Random Forest

### Data Features
- **_RAJ2000**: Right ascension (deg)
- **_DEC2000**: Declination (deg)
- **HIP**: Identifier
- **RAhms**: Right ascension (hr, min, sec)
- **DEdms**: Declination (deg, min, sec)
- **Vmag**: Apparent magnitude aka. m (magnitude)
- **Plx**: Parallax (marcsec), distance to star = 1/parallax
- **e_Plx**: Parallax error
- **B-V**: the color index of a star, calculated as the difference between its apparent magnitudes in the B (blue) and V (visible) photometric bands. It provides insight into the star's temperature and spectral characteristics:
    - Blue stars (hotter) have smaller B-V values (negative or near zero).
    - Reddish stars (cooler) have larger B-V values (positive).
- **Notes**
- **SpType**: The spectral type classifies stars based on their surface temperature and luminosity, represented by a letter and optional Roman numeral:
    - **I, II, III**: Giants - Large and luminous stars at various stages of evolution.
    - **IV, V, VI**: Dwarfs - Main sequence stars (V), subgiants (IV), and subdwarfs (VI).
    - **VII**: White dwarfs - Small, dense stars near the end of their life cycle.
    - *None*: Special stars that do not fit the giant/dwarf classification scheme neatly.

*(Source: The Hipparcos and Tycho Catalogues)*