# Concatenate
#Write a function that takes a tuple of strings and concatenates them, separating each string with a space.

def concatenate_strings(input_tuple):
    
    final_string = ""
    
    for i in input_tuple:
        
        final_string  +=  str(i) + " "
        
    final_string = final_string.rstrip()
        
    return final_string
