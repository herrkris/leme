# Synopsis 
   This program parses a funny file, calls calculix and maps the output to the given parameters.

# Examples
   This command iterates over the parameters in the given file and maps them to the output file.

   `leme input.dat output.dat`

   Other examples:

   `leme -p gap -s 0 -e 8 -S 0.25 output.dat`

# Usage 
   `leme [options] [input.dat] output.dat`

   For help use: `leme -h`

# Options
`-p, --parameter      Defines over which parameter the programm should iterate  
-s, --start NUM      Number from where to start the iteration  
-e, --end NUM        Numbere where to stop the iteration  
-S, --steps NUM      Iteration steps  
-c, --calculix FILE  Specifies the CalculiX binary  
-h, --help           Displays help message  
-v, --version        Display the version, then exit  
-q, --quiet          Output as little as possible, overrides verbose  
-V, --verbose        Verbose output`

# Author
   Kristof Dreier <kontakt@kristofdreier.de>  
   Vito Pasquariello <vito.pasquariello@mtu.com>

# Copyright
   Copyright (c) 20011 Kristof Dreier & Vito Pasquariello.  
   Licensed under the MIT License: <http://www.opensource.org/licenses/mit-license.php>