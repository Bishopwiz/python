
def symbol():
    syn=input('enter:')
    if syn == '(' or syn == ')' or syn == '((' or syn == '))' or syn == '{{' or syn == '}}' or syn == '[[' or syn == ']]':
        print('false')
    elif syn == '()' or syn == '[]' or syn == '{}':
        print('true')
    else:
        print('void')
    return
