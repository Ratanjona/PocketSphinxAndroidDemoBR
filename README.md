# PocketSphinxAndroidDemoBR
PocketSphinx Android Demo configured to work with Brazilian Portuguese language

It uses CMU Sphinx's (http://cmusphinx.sourceforge.net/) PocketSphinx for Android with the acoustic model "Constituição 1.0" for Brazilian Portuguese from FalaBrasil (http://www.laps.ufpa.br/falabrasil/). It also uses the text corpus "ceten" from FalaBrasil to create the Statistical Language Model using the CMUCLMTK tool.

Because the acoustic model has only 9 hours of audio from one speaker only, and the requirements for a multiple speaker recognizer is 50 hours from 200 different speakers, the recognition is currently not very good. I believe it can be improved with the use of a more appropriate acoustic model.
