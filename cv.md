 # CV by Natalya Makarova

## *Contact information:*
 - **mail**: maknatosh@gmail.com
 - **github**: Rednata
 - **discord-RSSchool**: Нати(@Rednata)
 - **phone**: XX-XXX-XXXXX

## *About me*
My main work experience is sales. But over time, it stopped to bring joy for me. I wanted to create something and see the results of this process, and not sell.
I like to learn new things, systematize knowledge and apply it in practice.

## *My skills*
- Python
- HTML
- CSS
- VS Code
- Figma
- PyCharm

## *Courses*
- Python for beginners (Stepik.org, two certificates) 

## *Code example*
Write a function that takes in a string of one or more words, and returns the same string, but with all five or more letter words reversed. Strings passed in will consist of only letters and spaces.   
Examples:   
spinWords( "Hey fellow warriors" ) => returns "Hey wollef sroirraw"   
spinWords( "This is a test") => returns "This is a test"   
spinWords( "This is another test" )=> returns "This is rehtona test"

```
def spin_words(sentence):
    a = list(sentence.split())
    for i in range(len(a)):
        if len(a[i])>=5:
          a[i] = a[i][::-1]
    return ' '.join(a)
```

## *Languages*
English (A1)