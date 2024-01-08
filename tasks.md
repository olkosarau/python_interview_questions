# TASKS

### Как преобразовать словарь в список?

1. - my_dict = {1: 'a', 2: 'b', 3: 'c'}  
my_list = [*my_dict.items()]
   - dict_data = {1: 'a', 2: 'b', 3: 'c'}   
result = []  
for key, val in dict_data.items():  
        result.append(key)  
        result.append(val)
   
### Как определить сколько раз буква встречается в строке?

1. - Для всех букв в строке s  {c:s.count(c) for c in set(s)}
   - from collections import Counter  
letter_counting = Counter(string)
   