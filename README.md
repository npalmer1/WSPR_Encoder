This encoder takes advantage of the following programs:
    Joseph Taylor, K1JT: nhash.c, nhash.h
        https://sourceforge.net/p/wsjt/wsjtx/ci/master/tree/lib/wsprd

    James Peroulas: wspr.cpp
        https://github.com/JamesP6000/WsprryPi

References:
G4JNT: The WSPR Coding Process
    http://www.g4jnt.com/wspr_coding_process.pdf

VA7NRM: Inside WSPR, JT65 and JT9 Weak-signal HF Modes
    http://archive.nsarc.ca/hf/jt_modes.pdf

Author: BD1ES

21 FEB 2020:
    Released to the Gist:
        https://gist.github.com/bd1es/a782e2529b8289288fadd35e407f6440
31 MAR 2020:
    Replaced the parity table with an algorithm introduced by Sean Anderson:
        http://graphics.stanford.edu/~seander/bithacks.html#ParityParallel
  
	Minor modification by G4GCI June 2025 to ensure correct msg type selected for 4 digit locators
