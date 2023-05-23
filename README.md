# Micro-Service

Directions of use:

1.First download the code off the git hub and and the folder to the project that you want the micro service to interact with.

2.Make sure you have a file called sort.py, also make a text file called sorting_preference.txt. This will be used to tell the program if you want to sort by date or if you want to sort by name. This will be done via command line input.

3.Once you ensure the exsitance of those files you will also need to have a Json file name times_api.json with the data for the articles you want to have sorted. Note that this is the starting Json and the articles in it do not need to be ordered.

4.You will also need one more Json file to finally be able to use the program and achieve the correct results. That last file is another Json called sorted_articles.json and this is where all the sorted articles information will be stored after the program has completed.
<so it goes sorting_preference.txt->sort.py->times_api.json->sort.py->sorted_articles.json>
  This is the order that the files will interact with each other.

5. After you have all the needed files all you will need to do is cd into the folder holding the code in a differnt terminal shell and run the command (python ./sort.py).

6.From this point you can choose how you want them to be ordered by inputing one of the two options given above.

7.After step 6 the program will run and edit the sorted_articles.json that you can then pull from for your own project. it only edits the order and does not reformat the information so there nothing to worry about there.

Video Link: https://youtu.be/e88Euozl8zI

UML Diagram: https://docs.google.com/document/d/1jSj6Mpsj9yqoLxaD1fmDb8crxLYO4GjDbcTDUhCXWTA/edit

