# Fix your bib

This snipplet uses regex and Python to fix my references. In this example I wanted to put uppes case letters in the title in curle brackets, to ensure that place names are compiled correctly. 

The script can easliy be modified for your needs. 

Example: 

  @Article{Argus2011,
    author  = {Argus, Donald F. and Blewitt, Geoffrey and Peltier, W. Richard and Kreemer, Corn{\'{e}}},
    title   = {Rise of the Ellsworth mountains and parts of the East Antarctic coast observed with GPS},
    journal = {Geophysical Research Letters},
    year    = {2011},
    volume  = {38},
    number  = {16},
    pages   = {3--7},
    issn    = {0094-8276},
    doi     = {10.1029/2011GL048025},
    file    = {Argus2011.pdf:Argus2011.pdf:PDF},
  }

 Can result in: 
*Rise of the ellsworth mountains and parts of the east antarctic coast observed with gps*



  @Article{Argus2011,
    author  = {Argus, Donald F. and Blewitt, Geoffrey and Peltier, W. Richard and Kreemer, Corn{\'{e}}},
    title   = {{R}ise of the {E}llsworth mountains and parts of the {E}ast {A}ntarctic coast observed with {GPS}},
    journal = {Geophysical Research Letters},
    year    = {2011},
    volume  = {38},
    number  = {16},
    pages   = {3--7},
    issn    = {0094-8276},
    doi     = {10.1029/2011GL048025},
    file    = {Argus2011.pdf:Argus2011.pdf:PDF},
  }
