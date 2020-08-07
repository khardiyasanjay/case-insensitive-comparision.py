# case-insensitive-comparision.py

current_users = ['shiva','Jhon','raku']
new_users = ['radha','jhon','rama']

for new_users in new_users:
	if new_users.lower() in current_users.lower():
		print(new_users + " srry taken")a
		
	else:
		print(new_users + " welcome") 
    
    
#attributeError:'list' object has no attribute 'lower'    ???    
