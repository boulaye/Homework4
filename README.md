Homework4
=========

the Word Counter Program

----------------------------

Your program should count how many times each word appears and display the most frequently occurring word, along with how many times it occurs. For instance, here is how it might interact with the user:


Enter the name of the file: gettysburg.txt
The most frequent word is and occuring 2 times

You must start your program out with a function called main(), and a function call to main() that looks like this:

def main():
    fileName = input("Enter the name of the file: ")
    loadWords(fileName)
    [mstfrqWrd,mstfrqCnt] = findMostFrequentWord()
    print("The most frequent word is", mstfrqWrd, "occuring", mstfrqCnt, "times")
    return

main()
 
