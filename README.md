# symptPred
    diagnostics program that diagnoses the user based on symptom and area of body

    This uses a dataset from Kaggle to find out what diseases have what type of symptoms.
    With that dataset in a CSV, I used used Pandas to put it in a pandas Dataframe.
    That dataframe is then manipulated and sorted through to match a users input.

    The users input is based on a body part of where so called ailment is and the types in two symptoms.
    The program will output a diagnosis based off of rarity of the disease and display two columns of 
    diseases depending on the rarity.
    It will also inform if this diagnosis is something that the use should worry about or is life threatening.
    The diagnoisis adds additional information about the diagnosis and will explain what needs to be done 
    alongside the treatments neccessary to combat the diagnoisi.
