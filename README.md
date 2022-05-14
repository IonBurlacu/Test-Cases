# Test cases

## 1. Test the "Search" feature functionnality
### Description
#### *Test the login by using correct credentials.*
### Steps to reproduce
#### *1. Go to login.wordpress.org*
#### *2. Add correct user/pass*
#### *3. Observe if user can login*
### Expected results
#### *User shoud be able to login.*
### Test data
#### *User: test*
#### *Pass: 123*

## 2. Test login with wrong credentials
### Description
#### *Test the login by using wrong credentials.*
### Steps to reproduce
#### *1. Go to login.wordpress.org*
#### *2. Add wrong user/pass*
#### *3. Observe if user can login*
### Expected results
#### *User shoud not be able to login.*
### Test data
#### *User: data*
#### *Pass: 456*

## 3. Test login with no credentials
### Description
#### *Test the login by not using any credentials.*
### Steps to reproduce
#### *1. Go to login.wordpress.org*
#### *2. Do not add any credentials*
#### *3. Observe if user can login*
### Expected results
#### *User shoud not be able to login.*

## 4. Test "Remember me" feature with correct credentials
### Description
#### *Test the "Remember me" functionality by using correct credentials.*
### Steps to reproduce
#### *1. Go to login.wordpress.org*
#### *2. Add correct user/pass*
#### *3. Click on  "Remember me" check box*
#### *4. Click Login*
#### *5. Click Logout*
#### *6. Go back to login.wordpress.org*
#### *7. Observe if user is logged in automatically*
### Expected results
#### *User should be logged in automatically.*
### Test data
#### *User: test*
#### *Pass: 123*

## 5. Test "Search" feature functionality
### Description
#### *Test the "Search" feature functionality with correct product name. *
### Steps to reproduce
#### *1. Go to emag.ro*
#### *2. Type a correct product name in "Search" box*
#### *3. Observe if the correct product is found*
### Expected results
#### *User should be able to find the correct product.*
### Test data
#### *Product name: trimmer*

## 6. Test "Search" feature autocomplete functionality
### Description
#### *Test the "Search" feature's autocomplete functionality.*
### Steps to reproduce
#### *1. Go to emag.ro*
#### *2. Start typing "trimm" in "Search" box*
#### *3. Observe if autocomplete works*
### Expected results
#### *User should get an autocomplete suggestion for trimmer.*
### Test data
#### *Product name: trimm*

## 7. Test "Search" functionality with wrong product name
### Description
#### *Test the "Search" feature functionality when wrong product name is typed.*
### Steps to reproduce
#### *1. Go to emag.ro*
#### *2. Add wrong product name*
#### *3. Observe the result*
### Expected results
#### *User should get an "0 rezultate pentru: A56435DS" message.*
### Test data
#### *Product name: A56435DS*
