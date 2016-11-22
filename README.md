# Simple_Ant_Vowel_code
The simplest way you can use to Antivowel a message

text= input("Enter a text\n  ")
vowel=("a","i","u","e","o")
new_text=""
for v in text:
    if v not in vowel:
        new_text+=v
        
print(new_text)
