# impledge_coding
coding tasks
                                                  Overview of the Program:
1.The program reads words from input files Input_01.txt and Input_02.txt.

2.It defines a function check_compounded_words that checks if a word can be compounded from smaller words in the list.
3.The function find_longest_compounded_words processes the input file to find the longest and second longest compounded words.
4.It sorts the words by length in descending order for efficient processing.
5.The program measures the time taken to process the input file.
6.Finally, it displays the results including the longest and second longest compounded words along with the processing time.                                                                                
                                                     Steps to Execute the Code:
1.Ensure you have the input files:
2.Make sure you have the input files Input_01.txt and Input_02.txt available at the specified file paths (/content/Input_01.txt and /content/Input_02.txt respectively).
Copy and Paste the Code:
Open a Python Environment:
3.You can use an Integrated Development Environment (IDE) like Jupyter Notebook, Google Colab, or a Python script editor.
Execute the code. You can typically do this by pressing the "Run" or "Execute" button in your chosen Python environment.
Observe the Output:After running the code, the program will process the input files and display the results in the console.
                                                     
                                                     Design and Decisions:
1.The program uses a Trie-like approach to efficiently check if a word can be compounded from smaller words in the list. This is implemented using the TrieNode class.
2.Sorting the words by length in descending order allows the program to quickly find the longest compounded words.
3.The program uses a set (word_set) to perform faster lookups during the word processing.
4.It utilizes a straightforward console output for displaying the results.
5.The code is designed to be modular and easy to understand, with clear function names and comments for readability.
6.The program handles empty strings as compounded words.
7.The file paths for input files (input_file_01 and input_file_02) are specified at the beginning of the program and should be updated with the correct file paths before running.

                                                        Approach:
Read the input file and split it into a list of words.
Convert the list of words to a set (word_set) for efficient lookup.
Sort the words by length in descending order.
Iterate through the sorted words and check if they can be compounded.
Track the longest and second longest compounded words.
Measure the time taken for processing.
Display the results in the console.                                    


