gamess.16.x is a modified version of gamess 2014

It creates several files that may be used for ADC or home-made CI codes

fort.321 ormas ci states (build on DETERMINANTS (not CSFs))

h1eMO.txt 1e int in MO basis ! works for RHF and ROHF (needs CC run)
fort.222 moint unformatted (intindex int) ! works for RHF and ROHF (needs CC run)
fort.223 moint formatted (intindex int)

fort.79 aoint formatted (intindex1 int1 intindex2 int2)
fort.80 aoint unformatted (intindex1 int1 intindex2 int2)
fort.82 number of aoint formatted

h1eAO.txt 1e int in AO basis
overlapAO.txt overlap int in AO basis
dipAO.txt dipole (X,Y,Z) int in AO basis ! use $ELMOM  IEMOM=1 IEMINT=1 $END

mocoef.txt MO coefficient (consistent with moint file) 
HForbenergy.txt, orbital1.txt,  orbital2.txt = orbital info for ADC code
