Files description:
- 'Анализ' and 'Обучение' are codes, which were made as a part of educational practice at the computer science department in SPbGETU "LETI".
The purpose of these works were to get an anaerobic threashold with machine learning methods based on medical dataset of sportsmen's anaerobic threashold.
The future realisation would be able to predict anaerobic threashold for pacients with hard diseases, who can't pass the whole test by traditional ways.
-- INS_Kalman - code of my graduation work. A main sense is to clarify coordinates of Inertial Navigation System, which error is accumulates significantly over time,
by the camera an Aruco markers. Cordinates of camera calculated relatively Aruco marker were represented in INS coordinate system and were the input parameters
of Kalman's filter. The output of filter were clarified coordinates in case to correct INS's output coordinates.
-- mat_to_tif_convert - also a part of educational practice at the computer science department in SPbGETU "LETI". It is a preparatory code to convert .mat files to .tiff,
cause the structure of bacillus images was given by 3 dimensionals. Next step was separating the image by mask of bacillus (on one plate were several types of bacillus).
The future gole of project is to apply NN in order to characterize some bacillus by camera without difficult laboratory researches with mycroscope.